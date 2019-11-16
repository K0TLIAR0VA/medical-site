<template>
  <div>
    <Header style="height: 100vh"></Header>
    <div class="container">
      <TopNav></TopNav>
    </div>
    <About></About>
    <Contacts></Contacts>
    <Footer></Footer>
  </div>
</template>

<script>
import Header from "../pages_components/Header.vue";
import Footer from "../pages_components/Footer.vue";
import TopNav from "../pages_components/TopNav.vue";
import Contacts from "../pages_components/Contacts.vue";
import About from "../pages_components/About.vue";
export default {
  components: { Header, Footer, TopNav, Contacts, About }
};
</script>