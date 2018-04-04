<template>
  <div class="image text-center">
    <b-img src="../assets/image2.jpg" class="image1 img-responsive" alt="Responsive image" />
    <div class="caption">
      <h1><span>I</span>ncheon <span>G</span>lobal <span>L</span>eadership <span>S</span>chool</h1>
    </div>
  </div>
</template>
<script>
export default {
  
}
</script>
<style>
  .image {
    position: relative;
  }
  .image1 {
    width: 100%;
    height: 700px;
    opacity: 0.7;
  }
  .caption {
    position: absolute;
    top: 35%;
    left: 0;
    width: 100%;
    color: #ffffff;
  }
  .caption span {
    color: #4286f5;
  }
</style>
