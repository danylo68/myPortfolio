<template>
  <v-app>

    <v-main>
    
      <NavBar />
      <Jumbotron />
      <About />
      <CenterView />
      <Carousel />
      <Parallax />
      <FooterBar />
      
    </v-main>
  </v-app>
</template>

<script>

import NavBar from './components/Core/NavBar';
import CenterView from './components/Core/CenterView';
import FooterBar from './components/Core/FooterBar.vue';
import Jumbotron from './components/Core/Jumbotron.vue';
import About from './components/Core/About.vue';
import Parallax from './components/Core/Parallax.vue';
import Carousel from './components/Core/Carousel.vue';




export default {
  name: 'App',

  components: {
    NavBar,
    CenterView,
    FooterBar,
    Jumbotron,
    About,
    Parallax,
    Carousel
},

  data: () => ({
    //
  }),
};
</script>

<style lang="scss" scoped>


@font-face { font-family: 'aileronblack'; src: url('./fonts/aileron-black-webfont.eot');
src: url('./fonts/aileron-black-webfont.eot?#iefix') format('embedded-opentype'),
url('./fonts/aileron-black-webfont.woff') format('woff'),
url('./fonts/aileron-black-webfont.ttf') format('truetype'),
url('./fonts/aileron-black-webfont.svg#aileronblack') format('svg'); font-weight:
normal; font-style: normal; }


</style>




