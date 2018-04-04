<template>
  <div>
    <b-jumbotron id="jumbo1" header-level=4>
    <template id="header" slot="header">
      배움에서 나눔까지
    </template>
    <template slot="lead">
      6개월 동안의 인문학수업과 영어수업으로 배움을 받고
      인천지역봉사활동으로 배움을 실천하여 나누는 선순환
    </template>
    <hr class="my-4">
    <p id="words">
      인천 글로벌리더쉽스쿨은 오랜 시간동안 SK의 임원으로 계셨던 이헌섭 교수님과
      뉴욕주립대학교 최고의 원어민 교수진이 함께합니다.
    </p>
    </b-jumbotron>
  </div>  
</template>

<script>
export default {
  
}
</script>
<style>
  #jumbo1 {
    color: #ffffff;
    background-color: #01bea4;
    width: 100%;
    height: 320px;
    transition: 0.5s;
    margin-bottom: 0;
    border-radius: 0;
  }

  #header {
    font-weight: bold;
  }
</style>
