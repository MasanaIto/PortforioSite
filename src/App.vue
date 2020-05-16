<template>
  <div id="app">
    <Navbar />
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
  color: #2c3e50;
}

</style>

<script>
import Navbar from './components/Navbar'

export default {
  components: { Navbar }
}
</script>
