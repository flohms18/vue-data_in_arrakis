<script setup>

import Header from './Header.vue';
import Footer from './Footer.vue';
</script>

<template>
  <Header></Header>
  <div class="parallaxFirst">
    <div class="Main_Title text-center">
      <h1 class="james">DATAKIS</h1>
      <p class="subtitle-dune">Those who understand data, shape the data-driven future</p>
      <div class="intro-datakis w-50">
 Spice is the most valuable resource in the universe. It enables interstellar travel, extends life, and grants the ability to foresee events through heightened prescience. Found only in significant quantities on the desert planet Arrakis, it is the foundation of power: whoever controls the Spice controls the galaxy.</div>
    </div>
  </div>
  <div class="parallaxSecond">
    <div class="Second_Title text-center">
       <div class="second-intro-datakis text-white w-75">
In Dune, power is divided among the Great Houses and governed by the Imperium, all of which ultimately depends on control of the Spice. A resource as central to their universe as data is to ours. Also a source of conflict, the control of Arrakis for Spice's exploration</div>
    </div>
   
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
  min-height: 500px;
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
  display: flex;
  justify-content: center;
  align-items: center;
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

.Main_Title {
  padding-top: 100px;


}

.intro-datakis {
  height: 100px;
  display: block;
  margin-left: auto;
  font-size: 18px;
  margin-right: auto;
  font-family: "subtitle_dune_font", sans-serif

}

.second-intro-datakis {
  height: 100px;
  display: flex;
  justify-content: center;
  align-items: center;
  font-size: 18px;
  font-family: "subtitle_dune_font", sans-serif
}

.subtitle-dune {
    padding-top: 10px;
    font-size: 18px;
    font-family: "subtitle_dune_font", sans-serif
  
}

.Second_Title {
  display: flex;
  justify-content: center;
  align-items: center;
}





</style>
