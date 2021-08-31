<template>
  <div id="app">
    <TestAskSlider/>
    <Reviews/>
    <ChatRooms/>
  </div>
</template>

<script>
import TestAskSlider from './components/TestAskSlider.vue'
import Reviews from './components/Rreviews.vue'
import ChatRooms from './components/ChatRooms'

export default {
  name: 'App',
  components: {
    TestAskSlider,
    Reviews,
    ChatRooms,
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
  @import url('https://fonts.googleapis.com/css2?family=Roboto:wght@500&display=swap');
}
body{
  background: #F9F7F2;
  margin: 0;
  padding: 0;
}
</style>
