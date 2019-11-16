<template>
  <div class="form-wrap">
    <div class="input-wrap">
      <input placeholder="Ваше ім'я" class="white" />
      <input placeholder="Ваш телефон" class="white" />
    </div>
    <textarea placeholder="Ваше повідомлення" class="white"></textarea>
    <input type="submit" value="Відправити" class="violet" />
  </div>
</template>


<style lang="sass" scoped>
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