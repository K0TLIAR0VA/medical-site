<template>
  <div class="wrap white">
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
        <div class="form-wrap">
          <div class="input-wrap">
            <input placeholder="Ваше ім'я" class="white"/>
            <input placeholder="Ваш телефон" class="white"/>
          </div>
          <textarea placeholder="Ваше повідомлення" class="white"></textarea>
          <input type="submit" value="Відправити" class="violet"/>
        </div>
      </div>
    </section>
  </div>
</template>


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
    .form-wrap
      width: 50%
      padding: 0 5%
      .input-wrap
        display: flex
        margin-bottom: 30px
        input
          width: 47.5%
          height: 30px
          padding: 0 20px
        input:first-child
          margin-right: 5%
      textarea
        width: 100%
        height: 50%
        resize: none
        padding: 10px 20px
        margin-bottom: 20px
      .input-wrap input, textarea, input[type="submit"]
        background: #00BCE4
        border: none
        border-radius: 7px
        font-size: 16px
      .input-wrap input::placeholder, textarea::placeholder
        color: #fff
        font-size: 14px
        font-style: italic
        opacity: 0.6
      input[type="submit"]
        height: 30px
        padding: 0 20px
        width: 160px
        background: #00BCE4
        border: 2px solid #7d3f98
      input[type="submit"]:hover
        color: #fff
</style>