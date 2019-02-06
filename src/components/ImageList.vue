<template>
  <div class="container mt-4">
    <single-image :imagen-seleccionada="imagenSeleccionada"/>
    <div class="row">
      <div v-for="imagen in images" :key="imagen.id" class="col-md-3 col-sm-4 col-6">
        <a href="#">
          <img class="img-fluid" :src="imagen.thumbnail" @click="detalles(imagen)">
        </a>
      </div>
    </div>
  </div>
</template>
<script>
import SingleImage from "./SingleImage.vue"
export default {
  components: { SingleImage },
  props: ["images"],
  data() {
    return { imagenSeleccionada: "" };
  },
  methods: {
    detalles: function(imagen) {
      this.imagenSeleccionada = imagen;
    }
  }
};
</script>

<style>
</style>