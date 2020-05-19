<template>
  <section id="about">
    <img class="top__icon" alt="Masana Icon" src="../assets/myface.jpg">
    <h1>いとう まさな</h1>
    <h3><i class="fas fa-school"></i> 経歴 <i class="fas fa-school"></i></h3>
    <ul>
      <li>2018/4 ~ 現在3年生</li>
      <li>北海学園大学 経営学部 経営学科 (夜間過程)</li>
    </ul>
    <h3><i class="far fa-building"></i> インターン歴 <i class="far fa-building"></i></h3>
    <ul>
      <li>2019/2 ~ 3</li>
      <li>ダイアモンドヘッド株式会社</li>
      <li>ECサイト開発 - Laravel/HTML5/CSS3/Scss</li>
      <p class="far fa-hand-point-down"></p>
      <li>2019/10 ~ 現在</li>
      <li>株式会社インフィニットループ</li>
      <li>ソーシャルゲーム開発 - PHP/MySQL/jQuery</li>
    </ul>
    <h3>バイト歴</h3>
    <ul>
      <li><i class="fas fa-cut"></i> 刺繍屋</li>
      <li><i class="fas fa-hamburger"></i> ファストフード店</li>
      <li><i class="fas fa-gamepad"></i> ゲームのバグチェッカー</li>
      <li><i class="fas fa-robot"></i> ロボット・プログラミング教室講師</li>
    </ul>
  </section>
</template>

<style lang="scss" scoped>
#about {
  .top__icon {
      margin-top: 8em;
      margin-left: auto;
      margin-right: auto;
      width: 10em;
      height: 10em;
      border-radius: 50%;
  }
  h3 {
    margin: 40px 0 0;
  }
  ul {
    list-style-type: none;
    padding: 0;
  }
  li {
    display: block;
    margin: 0 10px;
  }
  a {
    color: #42b983;
  }
}

</style>

<script>
</script>
