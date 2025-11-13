<script setup>

import Header from './Header.vue';
import Footer from './Footer.vue';
</script>

<template>
  <Header></Header>
  <div class="parallaxFirst">
      <h1 class="james">DUNE</h1>
      <div class="toto">
        James 
      </div>
  </div>
  <Footer></Footer>
</template>

<style scoped>


.parallaxFirst {
  background-image: url("./src/assets/images/dune-wallpaper.jpeg");
  min-height: 500px;
  background-attachment: fixed;
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
}

.toto {
  height: 300px;
  display: block;
  text-align: center;
  margin-left: auto;
  margin-right: auto;
  padding-top: 50px;
  font-family: "custom_dune", sans-serif;
}
</style>
