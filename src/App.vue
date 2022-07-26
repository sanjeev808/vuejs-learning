<template> 
  <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
<!-- <Home data = "Sanjeev I here" /> -->
  <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->
<!-- <ConditionRendering /> -->
<!-- <Loops /> -->
<Home />
</template>

<script>
import Home from "./components/Home/Home.vue";

// import HelloWorld from './components/HelloWorld.vue'
// import Hello from './components/Home.vue'
// import Home from './components/Home.vue'
// import ConditionRendering from './components/ConditionRendering'
// import Loops from './components/Loops.vue'
export default {
  name: 'App',
  components: {
    Home
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
}
</style>
