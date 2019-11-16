<template>
  <div class="wrap white" id="contacts">
    <section class="container">
      <h2 class="blue">Контакти</h2>
      <div class="contacts-wrap">
        <div class="contacts">
          <div class="flex-elem">
            <div class="icon">
              <p>
                <i class="fas fa-phone blue"></i>
              </p>
            </div>
            <div>
              <p>
                <a href="tel:+380935082683" class="white">093 508 26 83</a>
              </p>
              <p></p>
            </div>
          </div>
          <div class="flex-elem">
            <div class="icon">
              <p>
                <i class="fas fa-map-marker-alt blue"></i>
              </p>
            </div>
            <div>
              <p>Клініка "19+"</p>
              <p>м. Харків, вул. Клочківська, 366</p>
            </div>
          </div>
          <div class="flex-elem">
            <div class="icon">
              <p>
                <i class="fas fa-map-marker-alt blue"></i>
              </p>
            </div>
            <div>
              <p>Військовий госпіталь</p>
              <p>м. Харків, вул. Культури, 5</p>
            </div>
          </div>
          <div class="flex-elem">
            <div class="icon">
              <p>
                <i class="fas fa-map-marker-alt blue"></i>
              </p>
            </div>
            <div>
              <p>Сахновщинська ЦВЛ</p>
              <p>смт. Сахновщина, вул. Полтавська, 76</p>
            </div>
          </div>
          <div class="flex-elem">
            <div class="icon">
              <p>
                <i class="fab fa-instagram blue"></i>
              </p>
            </div>
            <div>
              <p>
                <a href="https://www.instagram.com/pogorelov.doctor" class="white">@pogorelov.doctor</a>
              </p>
              <p></p>
            </div>
          </div>
        </div>
        <ContactForm></ContactForm> 
      </div>
    </section>
  </div>
</template>

<script>
import ContactForm from './ContactForm.vue';
export default {
  components: { ContactForm }
}
</script>
<style lang="sass" scoped>
.wrap
  background: #404040
  padding: 40px 0
  h2
    font-size: 46px
    text-align: center
    margin-bottom: 40px
  .contacts-wrap
    display: flex
    .contacts
      width: 50%
      line-height: 1.5em
      padding-left: 50px
      .flex-elem
        display: flex
        margin-bottom: 10px
        .icon
          margin-right: 20px
    
</style>