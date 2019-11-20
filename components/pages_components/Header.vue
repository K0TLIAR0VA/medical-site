<template>
  <header class="fullscreen-bg">
    <div class="overlay">
      <img src="/img/logo/logo-white-with-title_v1.png" alt class="logo" />
      <Navigation></Navigation>
      <div class="title-border-top"></div>
      <h1>
        Погорєлов
        <br />Дмитро Олександрович
        <br />
        <span>Лікар-гінеколог</span>
      </h1>
      <div class="title-border-bottom"></div>
      <a href="/blog">la-la</a>
    </div>
    <!-- Video -->
    <video loop muted autoplay class="fullscreen-bg__video">
      <source src="/video/plane.mp4" type="video/mp4" />
    </video>
  </header>
</template>

<style lang="sass" scoped>
.fullscreen-bg
  overflow: hidden
  position: relative
  height: 100vh
  width: 100%
  padding-top: 45%
  .fullscreen-bg__video 
    position: absolute
    top: 0
    left: 0
    width: 100%
  .overlay
    background: rgba(0, 0, 0, 0.6)
    position: absolute
    top: 0
    left: 0
    width: 100%
    height: 100%
    z-index: 4
    padding: 40px 0
    .logo
      display: block
      margin: 0 auto
      padding-bottom: 70px
    .title-border-top, .title-border-bottom
      width: 550px
      height: 50px
      border: 3px solid #fff
      margin: 0 auto
    .title-border-top
      margin-top: 80px
      border-bottom: none
    .title-border-bottom
      border-top: none
    h1
      color: #fff
      font-size: 68px
      text-align: center
      margin: 30px 0
      line-height: 1.2em
      span
        font-size: 36px


@media (max-width: 767px)
  .fullscreen-bg
    /*background: url('../images/plane.jpg') center center / cover no-repeat;*/

  .fullscreen-bg__video
    display: none

</style>

<script>
import Navigation from './Navigation.vue';
export default {
  components: {Navigation}
}
</script>