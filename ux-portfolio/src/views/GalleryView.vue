<template>
    <div class="home">
      <Gallery />
    </div>
  </template>
  
  <script>
  // @ is an alias to /src
  import Gallery from '@/components/Gallery.vue'
  
  export default {
    name: 'GalleryView',
    components: {
      Gallery
    }
  }
  </script>
  