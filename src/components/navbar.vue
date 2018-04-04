<template>
  <div class="navbar">
    <b-navbar toggleable="md" fixed="top">
      <b-navbar-toggle target="nav_collapse"></b-navbar-toggle>

      <b-navbar-brand id="brand" href="#">IGLS 인천글로벌리더십스쿨</b-navbar-brand>

      <b-collapse is-nav id="nav_collapse">
        <b-navbar-nav class="ml-auto">
          <div>
            <b-nav-text id="menu"><a href="#carousel">소개</a></b-nav-text>
            <b-nav-text id="menu"><a href="#jumbotron">설명</a></b-nav-text>
            <b-nav-text id="submit"><a href="http://www.janghakin.or.kr/index.php">지원하러가기</a></b-nav-text>
          </div>
          <!-- <b-row align-v="center">
              <b-nav-item href="#carousel">소개</b-nav-item>
              <b-nav-item href="#jumbotron">설명</b-nav-item>
              <b-nav-item id="submit" href="http://www.janghakin.or.kr/index.php">지원하러가기</b-nav-item>
          </b-row> -->
        </b-navbar-nav>
      </b-collapse>
    </b-navbar>
  </div>
</template>

<script>
export default {
  
}
</script>

<style>
  .navbar {
    height: 80px;
    background: linear-gradient(to right, #4286f5, #01bea4);
  }
  #brand {
    padding-left: 50px;
    color: #ffffff;
    font-weight: bold;
  }
  #nav_collapse {
    padding-right: 50px;
    font-size: 16px;
  }
  #menu {
    padding: 0px 30px 0px 30px;
  }
  #menu a {
    text-decoration: none;
    color: #ffffff;
    opacity: 0.6;
    transition: 1;
  }
  #menu a:hover {
    opacity: 0.8;
    transition: 1;
  }
  #submit {
    padding: 5px 30px 5px 30px;
    border-radius: 20px;
    border: solid 3px #ffffff;
    box-sizing: border-box;
  }
  #submit a {
    text-decoration: none;
    color: #ffffff;
    opacity: 0.6;
    transition: 1;
  }
  #submit a:hover {
    opacity: 0.8;
    transition: 1;
  }
</style>
