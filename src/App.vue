<template>
  <div id="navbar">
    <nav-bar></nav-bar>
  </div>
</template>

<script>
import navbar from './components/navbar.vue'

export default {
  name: 'app',
  components: {
    'nav-bar' : navbar
  }
}
</script>

<style>
  #navbar {
    font-family: 'Lato' , sans-serif;
  }
</style>
