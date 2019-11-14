<template>
  <div>
    <Header style="height: 50vh"></Header>
    <TopNav></TopNav>
    <article class="container wrap">
      <h1>Як часто треба відвідувати гінеколога?</h1>
      <p>https://www.passion.ru/health/kak-chasto-nuzhno-hodit-k-ginekologu-157037.html</p>
    </article>
    <Footer></Footer>
  </div>
</template>

<script>
import Header from "/components/pages_components/Header.vue";
import Footer from "/components/pages_components/Footer.vue";
import TopNav from "/components/pages_components/TopNav.vue";
export default {
  components: { Header, Footer, TopNav }
};
</script>

<style lang='sass' scoped>
.wrap
  h1
    font-size: 46px
    text-align: center
    margin-bottom: 40px
</style>