<template> 
  <div id="app">
    <Header />
    <Nav />
    <Home />
    <Footer />
    <p> {{ info }} </p>
  </div>
</template>

<script>
import Header from './components/Header.vue'
import Nav from './components/Nav.vue'
import Home from './components/Home.vue'
import Footer from './components/Footer.vue'

import axios from 'axios'
import VueAxios from 'vue-axios'

export default {
  name: 'app',
  components: {
    Header,
    Nav,
    Home,
    Footer
  },
  data () {
    return {
      info: null
    }
  },
  mounted () {
    axios
    .get('https://statsapi.web.nhl.com/api/v1/people/8476459/stats?stats=statsSingleSeason&season=20182019')
    .then(response => (this.info = response))
  }
}
</script>

<style lang="scss">
  @import "./scss/variables.scss";
</style>
