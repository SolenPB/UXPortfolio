<template>
  <div class="home">
    <NavLink />
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
