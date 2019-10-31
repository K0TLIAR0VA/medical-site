<template>
  <div>
    <Header></Header>
    <div class="container">
      <ContentTop></ContentTop>
    </div>
    <Footer></Footer>
  </div>
</template>

<script>
import Header from "../pages_components/Header.vue";
import Footer from "../pages_components/Footer.vue";
import ContentTop from "../pages_components/ContentForHomePage1.vue";
export default {
  components: {
    Header: Header,
    Footer: Footer,
    ContentTop: ContentTop
  }
};
</script>

<style scoped>
</style>