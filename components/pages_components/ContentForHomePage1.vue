<template>
  <div class="container">
    <div class="col">
      <p class="icon">
        <i class="fas fa-user-md"></i>
      </p>
      <h3>Contrary to popular</h3>
      <p>Lorem Ipsum is not simply random text. It has roots in a piece of classical Latin literature from 45</p>
    </div>
    <div class="col">
      <p class="icon">
        <i class="fas fa-user-md"></i>
      </p>
      <h3>Contrary to popular</h3>
      <p>Lorem Ipsum is not simply random text. It has roots in a piece of classical Latin literature from 45</p>
    </div>
    <div class="col">
      <p class="icon">
        <i class="fas fa-user-md"></i>
      </p>
      <h3>Contrary to popular</h3>
      <p>Lorem Ipsum is not simply random text. It has roots in a piece of classical Latin literature from 45</p>
    </div>
  </div>
</template>

<style scoped>
.container {
  display: flex;
  justify-content: space-between;
  position: relative;
  top: -200px;
}
.col {
  width: 33%;
  margin-right: 1%;
  min-height: 350px;
  padding: 20px 50px 0;
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
}
.col:last-child {
  margin-right: 0;
}
.col:first-child,
.col:last-child {
  background: url(/img/top2.png);
}
.col:nth-child(2) {
  background: url(/img/top1.png);
}
.col .icon {
  font-size: 60px;
  color: #fff;
  border: dotted 3px #fff;
  width: 100px;
  height: 100px;
  border-radius: 50%;
  display: flex;
  justify-content: center;
  align-items: center;
  margin-bottom: 20px;
}
</style>