<template>
  <header>
    <div class="container">
      <div class="logo">
        <a href="/">
          <img src="/img/logo/logo-white-with-title_v1.png" alt />
        </a>
      </div>
      <div class="top-nav">
        <span class="menu">
          <img src="/img/icon/menu.png" alt />
        </span>
        <ul>
          <li>
            <a href="/" class="link">Головна</a>
          </li>
          <!--присвоить class="active" -->
          <li>
            <a href="/about" class="link">Про себе</a>
          </li>
          <li>
            <a href="/blog" class="link">Блог</a>
          </li>
          <li>
            <a href="/contact" class="link">Контакти</a>
          </li>
        </ul>
      </div>
      <div class="title"><h1 class="violet">Лікар-гінеколог Погорєлов <br> Дмитро Олександрович</h1></div>
    </div>
  </header>
</template>

<style scoped>
/*



*/
</style>

<style lang="sass" scoped>
header
  background: url(/img/1.jpg) no-repeat
  background-size: cover
  position: relative
  .container
    display: flex
    justify-content: space-between
    .logo a
      background: url(/img/log.png) bottom no-repeat
      width: 240px
      height: 204px
      display: block
      text-align: center
      padding: 1.7em 0 0
    .top-nav .menu
      display: none
    .top-nav ul
      display: flex
      li a
        font-size: 1.2em
        display: block
        padding: 1.6em 1em
        text-align: center
        color: #ffffff
        display: inline-block
        vertical-align: middle
        transform: translateZ(0)
        box-shadow: 0 0 1px rgba(0, 0, 0, 0)
        backface-visibility: hidden
        position: relative
        transition-property: color
        transition-duration: 0.3s
      li a:before
        content: ""
        position: absolute
        z-index: -1
        top: 0
        left: 0
        right: 0
        bottom: 0
        background: #00bce4
        transform: scaleY(0)
        transform-origin: 50% 0
        transition-property: transform
        transition-duration: 0.3s
        transition-timing-function: ease-out
      li a:hover, li a:focus, li a:active
        color: #fff
      li a:hover:before, li a:focus:before, li a:active:before
        transform: scaleY(1)
      li.active a
        background: #00bce4
    .title
      position: absolute
      font-size: 80px
      width: 40%
      top: 30%
      right: 10%
      font-weight: 900
</style>