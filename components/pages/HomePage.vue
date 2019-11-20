<template>
  <div>
    <Header style="height: 100vh"></Header>
    <About></About>
    <Contacts></Contacts>
    <Footer></Footer>
  </div>
</template>

<script>
import Header from "../pages_components/Header.vue";
import Footer from "../pages_components/Footer.vue";
import Contacts from "../pages_components/Contacts.vue";
import About from "../pages_components/About.vue";
export default {
  components: { Header, Footer, Contacts, About }
};
</script>