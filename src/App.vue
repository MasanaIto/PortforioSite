<template>
  <div id="app">
    <Navbar />
    <Footer />
  </div>
</template>
<style lang="scss">
body {
  background: linear-gradient(#eadeb9, #e2a872);
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #051637;
}

</style>

<script>
import Navbar from './components/Navbar'
import Footer from './components/Footer'

export default {
  components: { Navbar, Footer }
}
</script>
