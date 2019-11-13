<template>
  <div class="blog container">
    <div class="post" v-for="post in posts" :key="post.id">
      <div class="img"><img :src="post.picture"></div>
      <div class="text">
        <h2>{{post.title}}</h2>
        <p>{{post.text}}</p>
        <a :href="post.href">Read More..</a>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data: () => ({
    posts: [
      {
        title: 'Як часто треба відвідувати гінеколога?',
        picture: require('/img/blog/blog_1.jpg'),
        text: 'Жінка в будь-якому віці повинна проходити консультацію гінеколога один раз в 6-12 місяців, робити це необхідно навіть при відсутності скарг...'
      }
    ]
  })
}
</script>

<style lang='sass' scoped>
.blog
  padding: 50px 0
  .post
    display: flex
    justify-content: space-between
</style>