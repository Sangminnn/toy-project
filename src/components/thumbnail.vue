<template>
  <div id="thumb">
    <h1 id="name">주요 활동</h1>
    
    <div class="d-flex justify-content-around">
        <b-img class="img-responsive col-md-5 col-sm-4 col-xs-2" v-on:click="focusOn"
        id="img1" width=500 height=300 src="../assets/back.jpg">
          <div class="text" v-if="focus === 'on'">
            <h1>안녕하세요</h1>
          </div>
        </b-img>

        <b-img class="col-md-5 col-sm-4 col-xs-2" v-on:click="focusOn"
        id="img2" width=500 height=300 src="../assets/ima3.jpg">
          <div class="text" v-if="focus === 'on'">
            <h1>안녕하세요</h1>
          </div>
        </b-img>

    </div>
  </div>
</template>
<script>
export default {
  data () {
    return {
      focus: "off"
    }
  },
  methods: {
    focusOn () {
      focus = "on"
    },
    focusOff () {
      focus = "off"
    }
  }
}
</script>
<style>
  #thumb {
    height: 500px;
    color: #01bea4;
  }

  #name {
    padding: 25px 0px 40px 40px;
    font-weight: bold;
  }

  div #img1, div #img2 {
    border-radius: 20px;
    opacity: 0.8;
    transition: 0.5s;
  }
  div #img1:hover, div #img2:hover {
    opacity: 0.9;
    transition: 0.5s;
  }
</style>