<template>
  <Router :routes="routes"></Router>
</template>

<script>
import Router from './Router.vue';

import HomePage from './pages/HomePage.vue';
import AboutPage from './pages/AboutPage.vue';
import BlogPage from './pages/BlogPage.vue';
import ContactPage from './pages/ContactPage.vue';
import NotFoundPage from './pages/NotFoundPage.vue';
import Post1 from './pages/blog/Post1.vue';

export default {
  data: () => ({
    routes: {
      default: NotFoundPage,
      '/': HomePage,
      '/about': AboutPage,
      '/blog': BlogPage,
      '/contacts': ContactPage,
      '/post1': Post1
    }
  }),

  components: { Router }
}
</script>