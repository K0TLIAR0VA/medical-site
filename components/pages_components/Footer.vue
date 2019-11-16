<template>
  <footer>
    <div class="container">
      <img src="/img/logo/logo-white-with-title_v1.png" alt />
      <div class="footer-text">
        <p class="white">&copy; 2019 Особистий сайт лікаря-гінеколога Погорєлова Д.О.</p>
        <p class="white">Всі права захищено.</p>
        <small class="white">Developed by Kateryna</small>
      </div>
    </div>
  </footer>
</template>

<style lang="sass" scoped>
footer
  height: 25vh
  background: #7d3f98
  .container
    display: flex
    height: 100%
    justify-content: space-between
    align-items: center
    img
      display: block
      margin-left: 70px
    p, small
      line-height: 2em
    small
      font-size: 0.8em
</style>