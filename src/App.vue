<template >
  <div class="card">
<Navbar/>
  </div>
</template>

<script>

import Navbar from './components/Navbar.vue'
export default {
  name: 'App',
  components: {
  Navbar
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  margin: 0;
  box-sizing: border-box;
  min-width: 100%;
  
}


</style>
