<template>
<div class="error-wrap">
  <section class="container error-wrap">
    <div class="main">
      <div class="img center"><img src="/img/logo/logo-white-with-title_v1.png"></div>
      <div class="text">
        <h1 class="white">Особистий сайт лікаря-гінеколога Погорєлова Дмитра Олександровича</h1>
      </div>
    </div>
    <div class="home"><p>на головну сторінку</p></div>
    <button class="btn"><a href="/">ПЕРЕЙТИ</a></button>
    <div class="er-404 center"><p>404</p></div>
    <div class="not-found"><p>Запитану вами сторінку не знайдено</p></div>
    <div class="error"><p>Помилка</p></div>
  </section>
</div>
</template>

<style lang="sass" scoped>
.error-wrap
  background: #cccccc
  padding: 50px
  .container
    position: relative
    height: 550px
    .main, .home, .er-404, .btn, .not-found, .error
      position: absolute
      border-radius: 20px
      box-shadow: 5px 5px 10px rgba(0,0,0,0.5)
    .main
      background: #7d3f98
      display: flex
      font-size: 24px
      line-height: 1.2em
      width: 500px
      height: 270px
      z-index: 1
      left: 130px
      top: -10px
      padding: 50px 100px 50px 50px
      .img
        margin-right: 20px
    .home
      z-index: 1
      left: 340px
      top: 290px
      background: #fff
      width: 250px
      padding: 60px 40px 50px
    .er-404
      font-size: 10em
      width: 480px
      height: 400px
      right: 110px
      top: 100px
      padding: 25px
      z-index: 2
      background: radial-gradient(white, #aaa)
    .btn
      width: 120px
      height: 120px
      top: 230px
      left: 260px
      z-index: 2
      background: #00BCE4
      border-radius: 50%
      border: none
      background: radial-gradient(farthest-side ellipse at top left, white, #00BCE4)
      font-size: 18px
      box-shadow: 5px 10px 20px rgba(0,0,0,0.3), -5px -10px 20px rgba(255,255,255,0.5)
    .not-found
      z-index: 5
      border: solid yellow 2px
      padding: 50px 40px
      top: 406px
      right: 260px
      box-shadow: 5px 10px 20px rgba(0,0,0,0.3), -5px -10px 20px rgba(255,255,255,0.5)
    .error
      z-index: 5
      border: solid green 2px
      padding: 40px 80px
      right: 200px
      top: 50px
      box-shadow: 5px 10px 20px rgba(0,0,0,0.3), -5px -10px 20px rgba(255,255,255,0.5)
</style>