<template>
  <div>
    <Blog></Blog>
    <Contacts></Contacts>
    <Footer></Footer>
  </div>
</template>

<script>
import Blog from "../pages_components/Blog.vue";
import Contacts from "../pages_components/Contacts.vue";
import Footer from "../pages_components/Footer.vue";
export default {
  components: { Footer, Blog, Contacts}
};
</script>