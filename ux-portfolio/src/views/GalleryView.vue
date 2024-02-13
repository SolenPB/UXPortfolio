<template>
    <div class="home">
      <PortFolio />
    </div>
  </template>
  
  <script>
  // @ is an alias to /src
  import PortFolio from '@/components/PortFolio.vue'
  
  export default {
    name: 'GalleryView',
    components: {
      PortFolio
    }
  }
  </script>
  