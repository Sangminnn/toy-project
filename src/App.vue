<template>
  <div>
    <div id="navbar">
      <nav-bar></nav-bar>
    </div>
    
    <div id="mainImage">
      <main-image></main-image>
    </div>

    <div class="thumbnail">
      <thumbnail></thumbnail>
    </div>

    <div id="jumbotron">
      <jumbo-1></jumbo-1>
      <jumbo-2></jumbo-2>
    </div>

    <div id="card">
      <card></card>
    </div>
    
    <div id="sponsor">
      <foot></foot>
    </div>
  </div>

</template>

<script>
import navbar from './components/navbar.vue'
import mainImage from './components/mainImage.vue'
import thumbnail from './components/thumbnail.vue'
import jumbo1 from './components/jumbo-1.vue'
import jumbo2 from './components/jumbo-2.vue'
import card from './components/card.vue'
import foot from './components/footer.vue'

export default {
  name: 'app',
  components: {
    'nav-bar' : navbar,
    'main-image' : mainImage,
    'thumbnail' : thumbnail,
    'jumbo-1' : jumbo1,
    'jumbo-2' : jumbo2,
    'card' : card,
    'foot' : foot
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
  #card {
    padding-bottom: 100px;
    font-family: 'Lato' , 'Nanum Gothic Coding', sans-serif;
  }
  #sponsor {
    font-family: 'Lato' ,'Open Sans', sans-serif;
  }
</style>
