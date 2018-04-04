<template>
  <div>
    <div id="navbar">
      <nav-bar></nav-bar>
    </div>
    
    <div id="jumbotron">
      <jumbo-1></jumbo-1>
      <jumbo-2></jumbo-2>
    </div>
  </div>

</template>

<script>
import navbar from './components/navbar.vue'
import jumbo1 from './components/jumbo-1.vue'
import jumbo2 from './components/jumbo-2.vue'

export default {
  name: 'app',
  components: {
    'nav-bar' : navbar,
    'jumbo-1' : jumbo1,
    'jumbo-2' : jumbo2
  }
}
</script>

<style>
  #navbar {
    font-family: 'Lato' , sans-serif;
  }
  #jumbotron {
    font-family: 'Lato' , 'Nanum Gothic Coding', monospace;
  }
</style>
