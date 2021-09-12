<template>
  <v-app>
    <!-- Header component -->
    <Header />
    <v-main>
    <!-- HelloComponent component -->
    <HelloComponent/>
    <!-- About Us component -->
    <Aboutus/>
    <!-- Portfolio component -->
    <Portfolio/>
    <!-- Project component -->
    <Project/>
    <!-- Gallery component -->
    <Gallery/>
    <!-- Contact us component -->
    <Contactus/>
    <!-- Footer component -->
    <Footer/>
    </v-main>
  </v-app>
</template>

<script>
import Aboutus from './components/Aboutus.vue'
import Contactus from './components/Contactus.vue'
import Footer from './components/Footer.vue'
import Gallery from './components/Gallery.vue'
import Header from './components/Header.vue'
import HelloComponent from './components/HelloComponent.vue'
import Portfolio from './components/Portfolio.vue'
import Project from './components/Project.vue'

export default {
  components: { Header, HelloComponent, Aboutus, Portfolio, Project, Gallery, Contactus, Footer },
  name: 'App',

  data(){
    return{
    }
  }
}
</script>
