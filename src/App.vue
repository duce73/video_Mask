<script setup lang="ts">
import Sider from './components/Sider.vue';
import VideoPlay from './components/VideoPlay.vue';

</script>

<template>
  <div id="page">
    <h1>蒙版弹幕实现效果展示</h1>
    <div id="main">
      <VideoPlay id='videoPlay'/>
      <sider></sider>
    </div>
  </div>
  
</template>

<style lang='scss'>
body {
  margin: 0;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  #page {
    margin: 0 auto;
    width: 90%;
    height: 100%;
    background-color: white;
    padding: 20px 30px;
    #main{
      display: flex;
    }
  }
}
</style>
