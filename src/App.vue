<template>
<div>
  <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
  <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->
   <HomeW  />

</div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
import HomeW from './components/HomeW.vue'

export default {
  name: 'App',
  components: {
    // HelloWorld,
    HomeW
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
}
</style>
