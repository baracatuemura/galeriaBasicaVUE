<template>
  <div class="home">
    <galeria mensaje/>
  </div>
</template>

<script>
// @ is an alias to /src
import Galeria from '@/components/Galeria.vue'

export default {
  name: 'home',
  components: {
    Galeria
  }
}
</script>
