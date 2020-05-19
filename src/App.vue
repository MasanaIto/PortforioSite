<template>
  <div id="app">
    <Navbar />
    <transition mode="out-in">
      <router-view/>
    </transition>
    <footer>
      <Footer />
    </footer>
  </div>
</template>
<style lang="scss">
body {
  background: linear-gradient(#eadeb9, #e2a872);
}
#app {
  font-family: 'Noto Sans SC', sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #051637;
}
.v-enter {
  transform: translate(-100px, 0);
  opacity: 0;
}
.v-enter-to {
  opacity: 1;
}
.v-enter-active {
  transition: all 1s 0s ease;
}
.v-leave {
  transform: translate(0, 0);
  opacity: 1;
}
.v-leave-to {
  transform: translate(100px, 0);
  opacity: 0;
}
.v-leave-active {
  transition: all .5s 0s ease;
}
</style>

<script>
import Navbar from './components/Navbar'
import Footer from './components/Footer'

export default {
  components: {
    Navbar,
    Footer
  }
}
</script>
