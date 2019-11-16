<template>
  <div>
    <Header style="height: 100vh"></Header>
    <Error></Error>
    <Contacts></Contacts>
    <Footer></Footer>
  </div>
</template>

<script>
import Header from "../pages_components/Header.vue";
import Error from "../pages_components/Error.vue";
import Contacts from "../pages_components/Contacts.vue";
import Footer from "../pages_components/Footer.vue";
export default {
  components: { Header, Footer, Contacts, Error }
};
</script>