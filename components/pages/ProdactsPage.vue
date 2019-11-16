<template>
  <div>
    <Header style="height: 50vh"></Header>
    <TopNav></TopNav>
    <Contacts></Contacts>
    <Footer></Footer>
  </div>
</template>

<script>
import Header from "../pages_components/Header.vue";
import TopNav from "../pages_components/TopNav.vue";
import Contacts from "../pages_components/Contacts.vue";
import Footer from "../pages_components/Footer.vue";
export default {
  components: { Header, Footer, TopNav, Contacts }
};
</script>