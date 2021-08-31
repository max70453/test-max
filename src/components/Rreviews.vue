<template>
  <div class="reviews">
    <div class="reviews_title">
      <h2>Отзывы о Барселоне</h2>
    </div>
    
    <div class="items">
        <div class="item_reviews-1">
          <div class="avatar">
            <img src="../assets/img/Oval 2.png" alt="avatar">
            <span class="avatar_title">Наталия Полянская</span>
            <span class="about_city">Барселона</span>
            <p>Барселона – моя третья большая любовь, после Вены и Крита. 
              Это город, в который я каждый раз возвращаюсь с огромным удовольствием, всем 
              рекомендую хоть раз там побывать и осмотреть ...</p>
            <div class="gallery_img">
              <div class="item_img"></div>
              <div class="item_img-2"></div>
              <div class="item_img-3"></div>
              <div class="item_img-4"></div>
            </div>
            <sall class="review_date">около 1 года назад 
              <span class="bull">&bull;</span>
              9 комментариев <span class="like"><div class="like_number">9</div></span>
            </sall>
          </div>
        </div>
        <div class="item_reviews-2">
          <div class="avatar">
            <img src="../assets/img/Oval 2.png" alt="avatar">
            <span class="avatar_title">Elena Bulgakova</span>
            <span class="about_city">Барселона</span>
            <p>Плюсы города: весь город одни плюсы! Минусы города: не 
                видела. В наш марафон по 
                Европе не вписалось 2 испанских города от усталости - решили 
                остаток путешествия провести в 
                Барселоне ...</p>
            <div class="gallery_img">
              <div class="item_img"></div>
              <div class="item_img-2"></div>
              <div class="item_img-3"></div>
              <div class="item_img-4"></div>
            </div>
            <sall class="review_date">5 месяцев назад 
              <span class="bull">&bull;</span>
              3 комментария <span class="like"><div class="like_number">7</div></span>
            </sall>
          </div>
        </div>
        <div class="item_reviews-3">
          <div class="avatar">
            <img src="../assets/img/Oval 2.png" alt="avatar">
            <span class="avatar_title">Наталия Полянская</span>
            <span class="about_city">Барселона</span>
            <p>Барселона – моя третья большая любовь, после Вены и Крита. 
              Это город, в который я каждый раз возвращаюсь с огромным удовольствием, всем 
              рекомендую хоть раз там побывать и осмотреть ...</p>
            <div class="gallery_img">
              <div class="item_img"></div>
              <div class="item_img-2"></div>
              <div class="item_img-3"></div>
              <div class="item_img-4"></div>
            </div>
            <sall class="review_date">около 1 года назад 
              <span class="bull">&bull;</span>
              9 комментариев <span class="like"><div class="like_number">9</div></span>
            </sall>
          </div>
        </div>
    </div>
    
    <div class="rev_footer">
      <a  type="button" href="#" class="rev_btn">Все отзывы</a>
      <div class="reviews_slider">
        <span class="slide-1"></span>
        <span class="slide-2"></span>
        <span class="slide-3"></span>
        <span class="slide-4"></span>
        <span class="slide-5"></span>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Reviews',
}
</script>

<style scoped>
  .reviews{
    height: 606px;
    width: 879px;
    margin-top: 20px;
    background: white;
    display: flex;
    flex-direction: column;
    justify-content: flex-start;
    margin: 20px auto;
    padding: 35px 31px;
  }
  .reviews_title{
    align-self: start;
  }
  h2{
    font-family: KievitPro;
    font-size: 29px;
    line-height: 35px;
    letter-spacing: 0.03em;
  }
  .items{
    display: flex;
  }
  .item_reviews-1{
    padding-top: 25px;
    padding-left: 19px;
    height: 410px;
    width: 300px;
    background-color: #F9F7F2;
    margin-right: 20px;
  }
  .item_reviews-2{
    padding-top: 25px;
    padding-left: 19px;
    height: 410px;
    width: 300px;
    background-color: #F9F7F2;
    margin-right: 20px;
  }
  .item_reviews-3{
    padding-top: 25px;
    padding-left: 19px;
    height: 410px;
    width: 300px;
    background-color: #F9F7F2;
  }
  .avatar{
    background: no-repeat;
    text-align: start;
  }
  .avatar span{
    margin-left: 10px;
    font-family: KievitPro;
    font-size: 15px;
    position: relative;
    bottom: 10px;
  }
  .about_city{
    display: block;
    margin-top: 33px;
    text-transform: uppercase;
    color: #FC4F1E;
    font-family: KievitPro;
    font-size: 13px;
    line-height: 17px;
    letter-spacing: 0.4642857015132904px;
  }
  .about_city::after{
    content: " - о городе:";
    color: #212121;
  }
  .avatar p{
    font-family: Roboto;
    font-size: 14px;
    font-weight: 400;
    line-height: 25px;
  }
  .gallery_img{
    display: flex;
  }
  .item_img{
    background-image: url("../assets/img/gallery/IMG_2299.jpg");
    background-repeat: no-repeat;
    width: 74px;
    height: 50px;
    margin-right: -20px;
  }
  .item_img-2{
    background-image: url("../assets/img/gallery/IMG_2675.jpg");
    background-repeat: no-repeat;
    width: 74px;
    height: 50px;
    margin-right: -20px;
  }
  .item_img-3{
    background-image: url("../assets/img/gallery/IMG_2388.jpg");
    background-repeat: no-repeat;
    width: 74px;
    height: 50px;
    margin-right: -20px;
  }
  .item_img-4{
    background-image: url("../assets/img/gallery/IMG_2388.jpg");
    background-repeat: no-repeat;
    width: 74px;
    height: 50px;
    margin-right: -20px;
  }
  .item_img-4::after{
    content: "+7";
    font-family: Roboto;
    font-size: 17px;
    line-height: 50px;
    color: white;
    margin-left: 12px;
  }
  .review_date{
    margin-top: 28px;
    display: block;
    font-family: Roboto;
    font-size: 11px;
    line-height: 25px;
    color: #9D9D9D;
  }
  .like::before{
    content: url("../assets/img/Page 1.png");
    margin-left: 3px;
    position: relative;
    top: 11px;
  }
  .like_number{
    font-family: Roboto;
    font-size: 11px;
    display: inline;
    position: relative;
    top: 8px;
    left: 5px;
  }
  .bull{
    margin-right: 5px;
    top: 1px;
  }
  .rev_footer{
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin: 32px;
  }
  .rev_btn{
    width: 124px;
    height: 40px;
    border: 2px solid #FF4641;
    box-sizing: border-box;
    border-radius: 2px;
    font-family: KievitPro;
    font-size: 15px;
    text-align: center;
    padding-top: 8px;
    text-decoration: none;
    color: #212121;
  }
  .slide-1{
    width: 8px;
    height: 8px;
    display: inline-block;
    border-radius: 50%;
    margin-right: 12px;
    background: #FF4641;
    cursor: pointer;
  }
  .slide-2{
    width: 6px;
    height: 6px;
    display: inline-block;
    margin-right: 12px;
    border-radius: 50%;
    background: #000;
    cursor: pointer;
  }
  .slide-3{
    width: 6px;
    height: 6px;
    display: inline-block;
    margin-right: 12px;
    border-radius: 50%;
    background: #000;
    cursor: pointer;
  }
  .slide-4{
    width: 6px;
    height: 6px;
    display: inline-block;
    margin-right: 12px;
    border-radius: 50%;
    background: #000;
    cursor: pointer;
  }
  .slide-5{
    width: 6px;
    height: 6px;
    display: inline-block;
    margin-right: 12px;
    border-radius: 50%;
    background: #000;
    cursor: pointer;
  }
</style>
