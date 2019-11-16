<template>
  <Router :routes="routes"></Router>
</template>

<script>
import Router from './Router.vue';

import HomePage from './pages/HomePage.vue';
import ProdactsPage from './pages/ProdactsPage.vue';
import BlogPage from './pages/BlogPage.vue';
import NotFoundPage from './pages/NotFoundPage.vue';
import Post1 from './pages/blog/Post1.vue';

export default {
  data: () => ({
    routes: {
      default: NotFoundPage,
      '/': HomePage,
      '/prodacts': ProdactsPage,
      '/blog': BlogPage,
      '/post1': Post1
    }
  }),

  components: { Router }
}
</script>