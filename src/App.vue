<template>
  <div id="app">

    <!-- <Swiper></Swiper> -->
    <Photos></Photos>
  </div>
</template>

<script>
// import Swiper from "./views/swiper"
import Photos from "./views/Photos.vue"
export default {
  name: "App",
  components: {
    // Swiper.
    Photos
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;

  color: #2c3e50;
}
</style>
