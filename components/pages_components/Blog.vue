<template>
  <div class="blog container">
    <div class="col">
      <div class="post" v-for="post_first in posts_first" :key="post_first.id">
        <h2>{{post_first.title}}</h2>
        <div class="img"><img :src="post_first.picture" /></div>
        <p>{{post_first.text}}</p>
        <a :href="post_first.href">Читати більше...</a>
      </div>
    </div>
    <div class="col">
      <div class="post" v-for="post_second in posts_second" :key="post_second.id">
        <h2>{{post_second.title}}</h2>
        <div class="img"><img :src="post_second.picture" /></div>
        <p>{{post_second.text}}</p>
        <a :href="post_second.href">Читати більше...</a>
      </div>
    </div>
    <div class="col">
      <div class="post" v-for="post_third in posts_third" :key="post_third.id">
        <h2>{{post_third.title}}</h2>
        <div class="img"><img :src="post_third.picture" /></div>
        <p>{{post_third.text}}</p>
        <a :href="post_third.href">Читати більше...</a>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data: () => ({
    posts_first: [
      {
        title: "Як часто треба відвідувати гінеколога?",
        picture: require("/img/blog/blog_1.jpg"),
        text: "Всі знають, що гінеколога треба відвідувати щороку. Деякі лікарі хотіли б бачитися з вами частіще: їм за це платять :) Але навіщо це вам?.."
      }
    ],
    posts_second: [
      {
        title: "Як часто треба відвідувати гінеколога?",
        picture: require("/img/blog/blog_1.jpg"),
        text: "Всі знають, що гінеколога треба відвідувати щороку. Деякі лікарі хотіли б бачитися з вами частіще: їм за це платять :) Але навіщо це вам?.."
      }
    ],
    posts_third: [
      {
        title: "Як часто треба відвідувати гінеколога?",
        picture: require("/img/blog/blog_1.jpg"),
        text: "Всі знають, що гінеколога треба відвідувати щороку. Деякі лікарі хотіли б бачитися з вами частіще: їм за це платять :) Але навіщо це вам?.."
      }
    ]
  })
}
</script>

<style lang="sass" scoped>
.blog
  border: red 1px solid
  margin-bottom: 50px
  display: flex
  .col
    width: 33%
    h2, .img, p, a
      width: 85%
      margin: 0 auto 20px
      display: block
    h2
      text-align: center
      font-size: 2em
    .img img
      width: 100%
  .col:first-child, .col:nth-child(2)
    margin-right: .5%
    
</style>