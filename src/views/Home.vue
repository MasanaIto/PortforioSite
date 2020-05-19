<template>
  <section id="home">
    <img class="top__icon" alt="Masana Icon" src="../assets/myicon.png">
    <h1 class="myname">Masana Ito</h1>
    <div class="social">
      <a href="https://www.facebook.com/masana.ito.758" class="link facebook" target="_brank">
        <span class="fab fa-facebook"></span>
      </a>
      <a href="https://twitter.com/zhen2333" class="link twitter" target="_brank">
        <span class="fa fa-twitter"></span>
      </a>
      <a href="https://github.com/MasanaIto" class="link github" target="_brank">
        <span class="fab fa-github"></span>
      </a>
    </div>
  </section>
</template>

<style lang="scss" scoped>
.top__icon {
    margin-top: 8em;
    margin-left: auto;
    margin-right: auto;
    width: 10em;
    height: 10em;
    border-radius: 50%;
}

.myname {
  font-size: 4em;
  font-family: 'Archivo Black', sans-serif;
}

h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}

.social {
  padding-top: 5em;
  width: 100%;
  top: 50%;
  text-align: center;
}

.social .link {
  display: inline-block;
  vertical-align: middle;
  position: relative;
  width: 100px;
  height: 100px;
  border-radius: 50%;
  border: 2px dashed white;
  background-clip: content-box;
  padding: 10px;
  transition: .5s;
  color: #D7D0BE;
  margin: 30px;
  font-size: 70px;
}

.social .link span {
  display: block;
  position: absolute;
  text-align: center;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
}

.social .link:hover {
  padding: 20px;
  color: white;
  margin-left: -5px;
  transform: translateX(10px) rotate(360deg);
}

.social .link.github {
  color: white;
}

.social .link.twitter {
  color: white;
}

.social .link.facebook {
  color: white;
}

</style>

<script>
</script>
