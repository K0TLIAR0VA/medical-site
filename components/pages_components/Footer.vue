<template>
  <footer>
    <div class="container">
      <img src="/img/logo/logo-white-with-title_v1.png" alt />
      <div class="footer-text">
        <p>&copy; 2019 Особистий сайт лікаря Погорєлова Д.О.</p>
        <p>Всі права захищено.</p>
        <small>Developed by Kateryna Kotliarova</small>
      </div>
    </div>
  </footer>
</template>

<style scoped>
footer {
  height: 25vh;
  background: #7d3f98;
}
.container {
  display: flex;
  height: 100%;
  justify-content: space-between;
  align-items: center;
}
img {
  display: block;
  margin-left: 70px;
}
p, small {
  color: #fff;
  line-height: 2em;
}
small {font-size: 0.8em;}
</style>