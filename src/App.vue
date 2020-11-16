<template>
  <div id="app">
    <Nav />
    <Startup />
    <Features />
    <Experience />
    <Reviews />
    <Footer />
  </div>
</template>

<script>
import Nav from './components/Nav';
import Startup from './components/Startup';
import Features from './components/Features';
import Experience from './components/Experience';
import Reviews from './components/Reviews';
import Footer from './components/Footer';

export default {
  name: 'App',
  components: {
    Nav, 
    Startup,
    Features,
    Experience,
    Reviews,
    Footer
  }
}
</script>

<style lang="scss">
@import './assets/scss/config';
@import './assets/scss/buttons';
@import './assets/scss/animations';
@import './assets/scss/utilities';
@import './assets/scss/styles';


* {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
}

body {
    font-family: Arial, Helvetica, sans-serif;
    line-height: 1.6;
}
</style>
