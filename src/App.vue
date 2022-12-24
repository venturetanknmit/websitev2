<template>
    <NavBarVue/>
    <LandingVue/>
    <AboutusVue/>
    <FlipMain/>
    <TimelineSec/>
    <SponserSec/>
    <FaqsWrapper/>
    <FooterSection/>
    <!-- <ResultsPage2/> -->
</template>

<script>
import LandingVue from './components/Landing.vue';
import NavBarVue from './components/NavBar.vue';
import AboutusVue from "./components/sudeep/Aboutus.vue"
import FlipMain from './components/suhas/flip.vue';
import SponserSec from "./components/suhas/sponser1.vue"
import TimelineSec from "./components/vishak/timeline.vue"
import FaqsWrapper from "./components/vsagar/FaqsWrapper.vue"
import FooterSection from './components/vsagar/FooterSection.vue';

// import ResultsPage2 from './components/ResultsPage2.vue';

export default {
  name: 'App',
  components: {
    NavBarVue,
    LandingVue,
    AboutusVue,
    // PrizeVue,
    SponserSec,
    TimelineSec,
    FlipMain,
    FooterSection,
    FaqsWrapper,
    // ResultsPage2
}
}
</script>

<style>

@import url('https://fonts.googleapis.com/css2?family=Bangers&family=Comfortaa&family=Hammersmith+One&family=Josefin+Sans&family=Koulen&family=Neucha&family=Nova+Cut&family=Righteous&family=Roboto+Condensed:wght@300&family=Roboto+Mono&family=Roboto+Serif:opsz,wght@8..144,300&family=Roboto:wght@300&family=Sen&family=Shadows+Into+Light&family=Teko:wght@300&display=swap');

:root{
  --logoPri: #2493d4;
  --neutral: #7a87a8;
  /* --bgBlue: #3100806e; */
  /* --bgBlue: #091164; */
  --blueNeutral: #b5d7f8;
  --blueDark: #020859;
  --footerBg: #0f172a;
}

html, body{
  margin: 0;
  height: 100vh;
  transition: all; 
  overflow-x: hidden !important;
  scroll-behavior: smooth !important;
  font-family: 'Roboto Mono', monospace !important;
}
</style>
