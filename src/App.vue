<template>
  <div id="app">
    <Barra/>
    <router-view/>
  </div>
</template>

<script>
import Barra from "@/components/Barra.vue";
export default {
  name: "app",
  components: {
    Barra
  }
};
</script>