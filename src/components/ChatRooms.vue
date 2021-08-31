<template>
  <div>
    <div class="Chat">
      <h2>Чат с пользователем</h2>
      <h2>Чат с администратором</h2>
    </div>
    <div class="chat_rooms">
      <div class="userChat">
        <img src="../assets/img/Oval 2.png" alt="Аватар">
        <h2>Наталия Полянская</h2>
        <span>Гид по Баварии, фотограф</span>
      </div>
      <div class="adminChat">
        <img src="../assets/img/Oval 2.png" alt="Аватар">
        <h2>Администратор</h2>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'ChatRooms',
  props: {
    
  }
}
</script>

<style scoped>
  .Chat{
    display: flex;
    justify-content: space-evenly;
  }
  .chat_rooms{
    display: flex;
    justify-content: center;
  }
  h2{
    height: 35px;
    width: 289px;
  }
  .userChat{
    display: flex;
    height: 698px;
    width: 415px;
    margin-right: 49px;
    background-color: #fff;
    padding: 27px 26px;
  }
  .adminChat{
    display: flex;
    height: 698px;
    width: 415px;
    margin-right: 49px;
    background-color: #fff;
    padding: 27px 26px;
  }
  .userChat img{
    align-self: start;
    margin-right: -40px;
  }
  .adminChat img{
    align-self: start;
    margin-right: -50px;
  }
  .userChat h2{
    font-family: KievitPro;
    font-size: 18px;
    line-height: 17px;
    position: relative;
    bottom: 18px;
  }
  .adminChat h2{
    font-family: KievitPro;
    font-size: 18px;
    line-height: 17px;
    position: relative;
    bottom: 18px;
  }
  .userChat span{
    font-family: KievitPro;
    font-size: 13px;
    line-height: 17px;
    width: 180px;
    height: 17px;
    position: relative;
    top: 15px;
    right: 211px;
    color: #FF4641;
  }
  .userChat span::before{
    content: url("../assets/img/Icon — flag.png");
    margin-right: 5px;
  }
</style>