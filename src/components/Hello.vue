<script setup>

import Header from './Header.vue';
import Footer from './Footer.vue';
</script>

<template>
  <Header></Header>
  <div class="parallaxFirst">
    <div class="Main_Title text-center">
      <h1 class="james">DATA'RRAKIS</h1>
      <p class="subtitle-dune">Those who understand data, shape the data-driven future</p>
      <div class="intro-datakis w-50">
 In Dune's novel, Spice is the most valuable resource in the universe. It enables interstellar travel, extends life, and grants the ability to foresee events through heightened prescience. Found only in significant quantities on the desert planet Arrakis, it is the foundation of power: whoever controls the Spice controls the galaxy.</div>
    </div>
  </div>
  <div class="parallaxSecond">
    <div class="Second_Title text-center">
       <div class="second-intro-datakis text-white w-50">
In much the same way, as part of digital transformation, organisations are now treating data as a critical resource that sets direction, unlocks value and powers every meaningful innovation.</div>
    </div>
   
  </div>

  <div class="parallaxThird">
      <div class="third-intro-datakis text-white w-50 pt-5">And just as the Spice influenced every alliance and conflict in Dune, data now influences every decision we make—from the strategies we choose to the use-cases we build. It has become the thread connecting the present to the possibilities ahead.</div>
  </div>


  <div class="parallaxFourth">
      <div class="fourth-intro-datakis text-black w-50 pt-5">The control of the Spice is meaningless without the structures, discipline, and oversight that keep it flowing across the Imperium. Power depends not just on possessing the resource, but on managing it wisely, protecting it, and ensuring it is used with purpose.<br><br>Data is no different. Without strong governance—clear rules, trusted processes, and responsible stewardship—its value quickly erodes. But with the right governance in place, data becomes a stable, reliable source of insight and advantage, just as the Spice sustained entire worlds. Strong governance turns raw data into strategic power.</br></div>
  </div>
  <Footer></Footer>
</template>

<style scoped>


.parallaxFirst {
  background-image: url("./src/assets/images/dune-wallpaper.jpeg");
  min-height: 750px;
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
  background-image: url("./src/assets/images/fight.jpg");
  min-height: 500px;
  background-attachment: fixed;
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
  display: flex;
  justify-content: center;
  align-items: center;
  
}



.parallaxFourth {
  background-image: url("./src/assets/images/fremen.jpg");
  min-height: 750px;
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
  font-size: 20px;
  margin-right: auto;
  font-family: "subtitle_dune_font", sans-serif

}

.second-intro-datakis {
  height: 100px;
  display: block;
  margin-left: auto;
  margin-right: auto;
  padding-top: 20px;
  font-size: 20px;
  font-family: "subtitle_dune_font", sans-serif
}

.third-intro-datakis {
  height: 100px;
  font-size: 20px;
  font-family: "subtitle_dune_font", sans-serif;
  display: block;
  text-align: center;
  margin-left: auto;
  margin-right: auto;
}

.fourth-intro-datakis {
  height: 100px;
  font-size: 20px;
  font-family: "subtitle_dune_font", sans-serif;
  display: block;
  text-align: center;
  margin-left: auto;
  margin-right: auto;
}

.fifth-intro-datakis {
  height: 100px;
  font-size: 20px;
  font-family: "subtitle_dune_font", sans-serif;
  display: block;
  text-align: center;
  margin-left: auto;
  margin-right: auto;
}

.subtitle-dune {
    padding-top: 10px;
    font-size: 24px;
    font-family: "subtitle_dune_font", sans-serif
  
}

.Second_Title {
  display: flex;
  justify-content: center;
  align-items: center;
}





</style>
