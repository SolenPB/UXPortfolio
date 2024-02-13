<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <NavLink msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
// @ is an alias to /src
import NavLink from '@/components/NavLink.vue'

export default {
  name: 'HomeView',
  components: {
    NavLink
  }
}
</script>
