<template>
  <div id="app">
    <img src="./assets/logo.png">
    <wordActivity></wordActivity>
    <router-view/>
  </div>
</template>

<script>
import wordActivity from '. /components/wordActivity.vue';
// console.log(activity,222)
export default {
  name: 'App',
    components:{
      wordActivity
    }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
