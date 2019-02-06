<template>
  <transition name="fade">
    <div class="detalle">
      <h2>{{imagenSeleccionada.nombre}}</h2>
      <img :src="imagenSeleccionada.grande">
      <em>{{imagenSeleccionada.descripcion}}</em>
    </div>
  </transition>
</template>

<script>
export default {
  props: ["imagenSeleccionada"]
};
</script>

<style>
.fade-enter-active,
.fade-leave-active {
  transition: opacity 5s;
}

.fade-enter,
.fade-leave-to {
  opacity: 0;
}
</style>
