<template>
  <div>
    <Contacts></Contacts>
    <Footer></Footer>
  </div>
</template>

<script>
import Contacts from "../pages_components/Contacts.vue";
import Footer from "../pages_components/Footer.vue";
export default {
  components: { Footer, Contacts }
};
</script>