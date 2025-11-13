<script setup>

import Header from './Header.vue';
import Footer from './Footer.vue';
</script>

<template>
  <Header></Header>
  <div class="parallaxFirst">
      <h1 class="james">DUNE</h1>
  </div>
  <div class="parallaxSecond">
      <h1 class="james">DUNE</h1>
  </div>

  <div class="parallaxThird">
      <h1 class="james">DUNE</h1>
  </div>
  <div class="parallaxFourth">
      <h1 class="james">DUNE</h1>
  </div>
  <Footer></Footer>
</template>

<style scoped>


.parallaxFirst {
  background-image: url("./src/assets/images/dune-wallpaper.jpeg");
  min-height: 1000px;
  background-attachment: fixed;
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
}

.parallaxSecond {
  background-image: url("./src/assets/images/sardokhar.jpg");
  min-height: 500px;
  background-attachment: fixed;
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
}

.parallaxThird {
  background-image: url("./src/assets/images/caladan.jpg");
  min-height: 500px;
  background-attachment: fixed;
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
}

.parallaxFourth {
  background-image: url("./src/assets/images/imperium.jpg");
  min-height: 500px;
  background-attachment: fixed;
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
}


</style>
