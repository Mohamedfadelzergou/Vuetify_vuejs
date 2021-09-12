<template>
  <v-app>
    <Header />
    <v-main>

    </v-main>
  </v-app>
</template>

<script>
import Header from './components/Header.vue'

export default {
  components: { Header },
  name: 'App',

  data(){
    return{
      menus:[
        {title:'Home',      route:'home'},
        {title:'About us',  route:'about-us'},
        {title:'Portfolio', route:'portfolio'},
        {title:'Project',   route:'project'},
        {title:'Gallory',   route:'gallory'},
        {title:'Contact',   route:'contact'},
      ]
    }
  }
}
</script>
