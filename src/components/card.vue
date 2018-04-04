<template>
  <div class="pl-5 pr-5 d-flex justify-content-around text-secondary">
    <b-card img-src="../assets/image2.jpg"
            img-alt="Image"
            img-top
            tag="article"
            style="max-width: 16rem; max-height: 500px"
            class="mb-2"
            id="card-in">
      <p class="title">괌 어학연수</p>
      <p class="card-text">
        제5기 인천글로벌리더쉽스쿨의 마지막, 괌 어학연수입니다.
      </p>
      <b-button id="btn" href="http://www.janghakin.or.kr/board/view.php?code=gallery&cat=&sq=3258&page=1&s_fld=&s_txt=" >자세히 보기</b-button>
    </b-card>

    <b-card img-src="../assets/back.jpg"
            img-alt="Image"
            img-top
            tag="article"
            style="max-width: 16rem;"
            class="mb-2"
            id="card-in">
      <p class="title">교동도 봉사활동</p>
      <p class="card-text">
        교동도에 계신 분들에게 1학기동안의 가르침을 실천하러 봉사활동을 다녀왔습니다.
      </p>
    <b-button id="btn" href="#">더 알아보기</b-button>
    </b-card>

    <b-card img-src="../assets/back.jpg"
            img-alt="Image"
            img-top
            tag="article"
            style="max-width: 16rem;"
            class="mb-2"
            id="card-in">
      <p class=title>이것 저것</p>
      <p class="card-text">
        Some quick example text to build on the card title and make up the bulk of the card's content.
      </p>
    <b-button id="btn" href="#">Go somewhere</b-button>
    </b-card>
    
    <b-card img-src="../assets/back.jpg"
            img-alt="Image"
            img-top
            tag="article"
            style="max-width: 16rem;"
            class="mb-2"
            id="card-in">
      <p class="title">김유정 문학기행</p>
      <p class="card-text">
        한국의 대표작가 김유정 작가에 대해 공부하고, 김유정 생가로 문학기행을 다녀왔습니다.
      </p>
      <b-button id="btn" href="#">더 알아보기</b-button>
    </b-card>
  </div>
</template>
<script>
export default {
  
}
</script>
<style>
  .btn {
    background-color: #4286f5;
    border-color: #ffffff;
    opacity: 0.7;
  }
  #card-in {
    border: solid 16px #00bfa4;
    text-align: center;
  }
</style>
