<template>
  <div id="footer">
    <div id="head">
      <p id="header">IGLS Global Leadership School</p>
      <div id="etc">
        <p>Contact me </br> psm0102psm@gmail.com</p>
        <p>Sponsered by</p>
      </div>
    </div>

    <b-container id="foot">
      <b-row>
        <b-col>
          <b-img src="../assets/logo1.png" fluid alt="Fluid image" />
        </b-col>
        <b-col>
          <b-img src="../assets/logo2.png" fluid alt="Fluid image" />
        </b-col>
        <b-col>이헌섭교수님</b-col>
        <b-col>그 외 모든 수료자분들</b-col>
      </b-row>

      <div id="copyright">
        <p>made by Sangmin</p>
      </div>
    </b-container>
  </div>
</template>
<script>
export default {
  
}
</script>
<style>
  #footer {
    opacity: 0.51;
    background-image: linear-gradient(to right, #4286f5, #01bea4);
  }
  #head {
    padding: 25px 0px 40px 100px;
    color: #ffffff;
  }
  #head #header {
    font-size: 56px;
  }
  #head #etc {
    font-size: 20px;
  }
  #foot {
    text-align: center;
    padding-bottom: 100px;
    color: #ffffff;
  }
  #copyright {
    float: right;
    padding-top: 60px;
    padding-right: 30px;
  }
</style>
