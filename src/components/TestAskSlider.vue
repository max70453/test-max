<template>
  <div class="test_ask">
    <div class="item_img">
      <img src="../assets/img/Барселона_Испания.jpg" alt="Барселона">
    </div>
    <div class="item_description">
      <h2>Барселона — обзор города</h2>
      <p>Барселона с её золотистыми пляжами, архитектурными шедеврами Гауди,
         многочисленными фестивалями и гастрономическим разнообразием понравилась
        мне в первый же день пребывания и стала местом, в котором...</p>
        <a href="#">Читать дальше</a>
    </div>
  </div>
</template>

<script>
export default {
  name: 'TestAskSlider',
  props: {
    
  }
}
</script>

<style scoped>
  .test_ask{
    display: flex;
    justify-content: center;
    height: 440px;
    margin: auto;
    width: 879px;
    top: 110px;
    background-color: #fff;
  }
  .item_img{
    height: 440px;
    width: 440px;
    left: 243px;
  }
  .item_description{
    align-items: center;
  }
  .item_description{
    align-self: center;
  }
  h2{
    font-family: KievitPro;
    font-size: 29px;
    line-height: 35px;
    letter-spacing: 0.03em;
    margin-bottom: 19px;
  }
  p{
    font-family: KievitPro;
    font-size: 17px;
    line-height: 25px;
    text-align: left;
    margin-left: 29px;
    margin-bottom: 6px;
  }
  a{
    font-family: KievitPro;
    font-size: 17px;
    line-height: 25px;
    display: block;
    margin-left: 29px;
    text-align: left;
    text-decoration: none;
    color: black;
    width: 111px;
    border-bottom: 2px solid red;
  }

</style>
