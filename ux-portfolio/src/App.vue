<template>
  <nav>
    <router-link to="/">Accueil</router-link> 
    <router-link to="/about">À propos</router-link> 
    <router-link to="/gallery">Portfolio</router-link>
  </nav>
  <router-view/>
  <footer>
    Hello ! Mon footer très prochainement !
  </footer>
</template>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
}

nav {
  padding: 30px;

  a {
    font-weight: bold;
    color: #2c3e50;
    margin-left: 30px;

    &.router-link-exact-active {
      color: blue;
    }
  }
}
</style>
