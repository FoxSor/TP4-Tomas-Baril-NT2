<template>
  <div id="app" class="container-fluid mt-3">
    <div class="jumbotron">
      <Navbar />
      <router-view></router-view>
    </div>
  </div>
</template>

<script>
import Navbar from './componentes/Navbar.vue'

export default {
  name: 'App',
  components: {
    Navbar
  }
}
</script>

<style>
#app {
}

h1 {
  color: blue;
}

.jumbotron {
  padding: 26px !important;
}

</style>
