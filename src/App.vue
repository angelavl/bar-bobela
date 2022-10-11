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

@font-face {
  font-family: "Montserrat";
  src: local("Montserrat"),
   url(./assets/fonts/Montserrat/Montserrat-Regular.ttf) format("truetype");
}

html {
  height: 100%;
  width: 100%;
}

body {
  height: 100%;
  width: 100%;
  margin:0;
  background: url('@/assets/images/pattern_white.jpg');
  object-fit: cover;
}

#app {
  display: flex;
  align-items: center;
  justify-content: center;
  height: 100%;
  width: 100%;
  font-family: "Montserrat";
} 
</style>
