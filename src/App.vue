<template> 
  <div id="app">
    <Header />
    <Nav />
    <Home />
    <Footer />
  </div>
</template>

<script>
import Header from './components/Header.vue'
import Nav from './components/Nav.vue'
import Home from './components/Home.vue'
import Footer from './components/Footer.vue'

export default {
  name: 'app',
  components: {
    Header,
    Nav,
    Home,
    Footer
  }
}
</script>

<style lang="scss">
  @import "./scss/variables.scss";
</style>
