<template>
    <section class="navbar">
      <router-link class="tab" to="/">Home</router-link>
      <router-link class="tab" to="/about">About</router-link>
      <router-link class="tab" to="/skill">Skill</router-link>
    </section>
</template>

<style lang="scss" scoped>
.navbar {
  display: flex;
  justify-content: space-between;
  width: 50%;
  margin: 0 auto;
  padding: 40px;
  a {
    font-family: 'Archivo Black', sans-serif;
    color: #EB4E89;
    font-size: 1.5em;
    font-weight: bold;
    color: #2c3e50;
    text-decoration: none;
    transition: all  0.5s ease;
    &.router-link-exact-active {
      color: #EB4E89;
    }
    &:hover {
      color: #EB4E89;
    }
  }
}

@media screen and (max-width: 700px) {
  .navbar {
    width: 80%;
    a {
      font-size: 1.2em;
    }
  }
}

</style>

<script>
export default {
  name: 'Navbar'
}
</script>
