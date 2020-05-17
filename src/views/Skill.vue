<template>
<div class="skill">
    <section id="skill">
        <div class="card-list">
          <section class="card">
            <i class="fab fa-php card__icon"></i>
            <h3 class="card__title">PHP</h3>
            <p class="card__text">
              <i class="fab fa-laravel"></i> Laravel</p>
          </section>
          <section class="card">
            <i class="fab fa-js-square card__icon"></i>
            <h3 class="card__title">JavaScript</h3>
            <p class="card__text">
              <i class="fab fa-vuejs"></i> Vue.js / jQuery</p>
          </section>
          <section class="card">
            <i class="far fa-file-code card__icon"></i>
            <h3 class="card__title">HTML5/CSS3</h3>
            <p class="card__text"><i class="fab fa-sass"></i> Scss / <i class="fab fa-bootstrap"></i> Bootstrap</p>
          </section>
        </div>
    </section>
    </div>
</template>

<style lang="scss" scoped>

#skill {
  margin-top: 5em;
}

.card-list {
  display: flex;
  flex-wrap: wrap;
  align-items: flex-start;
  justify-content: space-between;
  padding: 0 10%;
  box-sizing: border-box;
}

.card {
  position: relative;
  width: 10em;
  height: auto;
  padding: 5%;
  text-align: center;
  line-height: 1.8;
  margin-bottom: 5em;

  &__icon {
    font-size: 10em;
  }

  &__title {
    text-align: left;
    font-weight: bold;
    font-size: 1.5em;
    margin-top: 10px;
  }

  &__text {
    margin-top: -1em;
    font-size: 1em;
    text-align: left;
  }

  .fa-php {
    margin-left: -20px;
  }
}

@media screen and (max-width: 700px) {
  .card-list {
    display: block;
  }
  .card {
    width: 10em;
    margin: 0 auto 3em auto;

    .fa-php {
      font-size: 9em;
      margin-right: -20px;
    }
  }
}
</style>

<script>
</script>
