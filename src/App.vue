<template>
  <div id="app" v-md-theme="'default'">
    <img src="./assets/logo.png">
    <!-- <hello></hello> -->
    <sample></sample>
  </div>
</template>

<script>
// import Hello from './components/Hello'
import Sample from './components/Sample'
export default {
  name: 'app',
  components: {
    // Hello,
    Sample
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
