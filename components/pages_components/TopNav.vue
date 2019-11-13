<template>
  <div class="container">
    <div class="col">
      <p class="icon">
        <i class="fas fa-user-md"></i>
      </p>
      <h3>Link</h3>
    </div>
    <div class="col">
      <p class="icon">
        <i class="fas fa-user-md"></i>
      </p>
      <h3>Link</h3>
    </div>
    <div class="col">
      <p class="icon">
        <i class="fas fa-user-md"></i>
      </p>
      <h3>Link</h3>
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
  min-height: 300px;
  padding: 65px 50px 0;
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
  font-size: 60px;
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