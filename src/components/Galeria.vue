<template>
  <div class="galeria">
    <image-list :images="images"></image-list>
  </div>
</template>
<script>
import ImageList from "./ImageList.vue";

export default {
  components: { ImageList },
  data() {
    return {
      images: [
        {
          thumbnail: "https://videotutoriales.com/egipto01.png",
          grande: "https://videotutoriales.com/egipto01b.png",
          descripcion: "Imagen 1 descripción",
          nombre: "Nombre Imagen 1"
        },
        {
          thumbnail: "https://videotutoriales.com/egipto02.png",
          grande: "https://videotutoriales.com/egipto02b.png",
          descripcion: "Imagen 2 descripción",
          nombre: "Nombre Imagen 2"
        },
        {
          thumbnail: "https://videotutoriales.com/egipto03.png",
          grande: "https://videotutoriales.com/egipto03b.png",
          descripcion: "Imagen 3 descripción",
          nombre: "Nombre Imagen 3"
        },
        {
          thumbnail: "https://videotutoriales.com/egipto04.png",
          grande: "https://videotutoriales.com/egipto04b.png",
          descripcion: "Imagen 4 descripción",
          nombre: "Nombre Imagen 4"
        },
        {
          thumbnail: "https://videotutoriales.com/egipto05.png",
          grande: "https://videotutoriales.com/egipto05b.png",
          descripcion: "Imagen 5 descripción",
          nombre: "Nombre Imagen 5"
        },
        {
          thumbnail: "https://videotutoriales.com/egipto06.png",
          grande: "https://videotutoriales.com/egipto06b.png",
          descripcion: "Imagen 6 descripción",
          nombre: "Nombre Imagen 6"
        },
        {
          thumbnail: "https://videotutoriales.com/egipto07.png",
          grande: "https://videotutoriales.com/egipto07b.png",
          descripcion: "Imagen 7 descripción",
          nombre: "Nombre Imagen 7"
        },
        {
          thumbnail: "https://videotutoriales.com/egipto08.png",
          grande: "https://videotutoriales.com/egipto08b.png",
          descripcion: "Imagen 8 descripción",
          nombre: "Nombre Imagen 8"
        }
      ]
    };
  }
};
</script>

<style>
img {
  box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2), 0 6px 20px 0 rgba(0, 0, 0, 0.19);
  margin-bottom: 20px;
}
img:hover {
  filter: gray;
  -webkit-filter: grayscale(1);
}
</style>