<template>
    <NavBarVue/>
    <LandingVue/>
    <AboutusVue/>
    <PrizeVue/>
    <SponserSec/>
    <!-- <FooterSection/> -->

</template>

<script>
import LandingVue from './components/Landing.vue';
import NavBarVue from './components/NavBar.vue';
import AboutusVue from "./components/sudeep/Aboutus.vue"
import PrizeVue from './components/suhas/prize.vue';
import SponserSec from "./components/suhas/sponser1.vue"
// import FooterSection from './components/vsagar/FooterSection.vue';

export default {
  name: 'App',
  components: {
    NavBarVue,
    LandingVue,
    AboutusVue,
    SponserSec,
    PrizeVue,
    // FooterSection
}
}
</script>

<style>

:root{
  --logoPri: #2493d4;
  --neutral: #7a87a8;
  /* --bgBlue: #3100806e; */
}

html, body{
  margin: 0;
  scroll-behavior: smooth !important;
  transition: all; 
  overflow-x: hidden !important;
  height: 100vh;
  font-family: 'Josefin Sans', sans-serif !important;
}
</style>
