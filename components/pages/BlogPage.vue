<template>
  <div>
    <Header style="height: 50vh"></Header>
    <TopNav></TopNav>
    <Blog></Blog>
    <Footer></Footer>
  </div>
</template>

<script>
import Header from "../pages_components/Header.vue";
import TopNav from "../pages_components/TopNav.vue";
import Blog from "../pages_components/Blog.vue";
import Footer from "../pages_components/Footer.vue";
export default {
  components: { Header, Footer, Blog, TopNav}
};
</script>