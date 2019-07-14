<template>
  <div id="app">
    
  <Navigation/>

  <!-- Header -->
  <header class="masthead">
    <div class="container">
      <div class="intro-text">
        <div class="intro-lead-in">Welcome To Our Studio!</div>
        <div class="intro-heading text-uppercase">It's Nice To Meet You</div>
        <a class="btn btn-primary btn-xl text-uppercase js-scroll-trigger" href="#services">Tell Me More</a>
      </div>
    </div>
  </header>

  <!-- Services -->
  <Services/>

  <!-- Portfolio -->
  <Portfolio/>

  <!-- About -->
  <About/>

  <!-- Team -->
  <Team/>

  <!-- Clients -->
  <Clients/>

  <!-- Contact -->
  <ContactUs/>

  <!-- Footer -->
  <Footer/>

  <!-- Portfolio Modals -->

  <Modals/>
  </div>
  
</template>

<script>
import Portfolio from './components/Portfolio.vue';
import Navigation from './components/Navigation.vue';
import Services from './components/Services.vue';
import About from './components/About.vue';
import Footer from './components/Footer.vue';
import Modals from './components/Modals.vue';
import Team from './components/Team.vue';
import Clients from './components/Clients.vue';
import ContactUs from './components/ContactUs.vue';

export default {
  name: 'app',
  components: {
    Portfolio,
    Navigation,
    Services,
    About,
    Footer,
    Modals,
    Team,
    Clients,
    ContactUs
  }
}
</script>

<style scoped>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
