<template>
  <div class="blog container">
    <article class="post" v-for="post in posts" :key="post.id">
      <img :src="post.picture" />
      <div class="post-text">
        <h2>{{post.title}}</h2>
        <p>{{post.text}}</p>
        <a :href="post.href" class="white">Читати більше <i class="fas fa-arrow-right"></i></a>
      </div>
    </article>
  </div>
</template>

<script>
export default {
  data: () => ({
    posts: [
      {
        title: "Як часто треба відвідувати гінеколога?",
        picture: require("/img/blog/blog_1.jpg"),
        text:
          "Всі знають, що гінеколога треба відвідувати щороку. Деякі лікарі хотіли б бачитися з вами частіще: їм за це платять :) Але навіщо це вам?",
        href: "/post1"
      },
      {
        title: "Lorem Ipsum is not simply",
        picture: require("/img/blog/blog_2.jpg"),
        text:
          "Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy. Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has ",
        href: "#"
      },
      {
        title: "Lorem Ipsum is not simply. Lorem Ipsum is not simply",
        picture: require("/img/blog/blog_3.jpg"),
        text:
          "Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy",
        href: "#"
      },
      {
        title: "Lorem Ipsum is not simply",
        picture: require("/img/blog/blog_4.jpg"),
        text:
          "Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy",
        href: "#"
      },
      {
        title: "Lorem Ipsum is not simply not simply",
        picture: require("/img/blog/blog_5.jpg"),
        text:
          "Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy",
        href: "#"
      },
      {
        title: "Lorem Ipsum is not simply simply",
        picture: require("/img/blog/blog_6.jpg"),
        text:
          "Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy",
        href: "#"
      },
      {
        title: "Lorem Ipsum is not simply",
        picture: require("/img/blog/blog_1.jpg"),
        text:
          "Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy",
        href: "#"
      },
      {
        title: "Lorem Ipsum is not simply",
        picture: require("/img/blog/blog_1.jpg"),
        text:
          "Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy",
        href: "#"
      },
      {
        title: "Lorem Ipsum is not simply",
        picture: require("/img/blog/blog_1.jpg"),
        text:
          "Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy. Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industr",
        href: "#"
      },
      {
        title: "Lorem Ipsum is not simply",
        picture: require("/img/blog/blog_1.jpg"),
        text:
          "Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy",
        href: "#"
      },
      {
        title: "Lorem Ipsum is not simply",
        picture: require("/img/blog/blog_1.jpg"),
        text:
          "Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy",
        href: "#"
      }
    ]
  })
};
</script>

<style lang="sass" scoped>
.blog
  margin-bottom: 50px
  height: 2300px
  display: flex
  flex-flow: column wrap
  .post
    width: 30%
    border: 1px solid #BEBEBE
    margin: 0 1.66666666666666% 40px
    img
      width: 100%
    .post-text
      padding: 20px
      h2
        text-align: center
        font-size: 2em
        color: #7d3f98
      a
        display: inline-block
        background: #7D3F98
        box-shadow: 0 0 1px rgba(0, 0, 0, 0)
        padding: 1em
      h2, p
        margin-bottom: 20px
    
</style>