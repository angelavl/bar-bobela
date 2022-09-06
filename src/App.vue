<template>  
  <WorkInProgress/>
</template>

<script>
import WorkInProgress from './components/WorkInProgress.vue'

export default {
  name: 'App',
  components: {
    WorkInProgress
  }
}
</script>

<style>
body {
  height: 100%;
  width: 100%;
  margin:0;
  position: relative;
  display:flex;
  background: url('@/assets/images/pattern_white.jpg');
   background-size: cover;
}

/* #app {
  display: flex;
  height: 100%;
  width: 100%;
  position: relative;   


 font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}  */
</style>
