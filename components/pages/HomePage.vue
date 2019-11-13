<template>
  <div>
    <Header></Header>
    <div class="container">
      <TopNav></TopNav>
    </div>
    <Footer></Footer>
  </div>
</template>

<script>
import Header from "../pages_components/Header.vue";
import Footer from "../pages_components/Footer.vue";
import TopNav from "../pages_components/TopNav.vue";
export default {
  components: { Header, Footer, TopNav }
};
</script>

<style scoped>
</style>