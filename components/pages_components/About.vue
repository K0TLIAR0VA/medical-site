<template>
  <section class="container">
    <div class="foto"></div>
    <div class="about">
      <h2 class="white">Вітаю!</h2>
      <p class="white">Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially</p>
    </div>
  </section>
</template>


<style lang="sass" scoped>
.container
  display: flex
  padding-bottom: 50px
  .foto, .about
    width: 50%
  .foto
    background: url(/img/2.jpg) no-repeat
  .about
    padding: 5%
    background: #7d3f98
    h2
      font-size: 56px
      margin-bottom: 5%
    p
      line-height: 1.5em
</style>