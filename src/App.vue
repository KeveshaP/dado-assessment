<template>
  <div id="app">
    <router-view />
  </div>
</template>

<style lang="scss">
@import url("https://fonts.googleapis.com/css?family=Roboto:300,400,500,700&display=swap");

body{
  background-color: #f6e0a2;
}

#app {
  font-family: "Roboto", Helvetica, Arial, sans-serif;
  text-align: center;
  color: #2c3e50;
}
.first-bn-block-bg-main {
    // position: absolute;
    background-color: #E4C953;
    background-image: url(//cdn.shopify.com/s/files/1/0015/4874/6807/t/109/assets/about-first-bg.png?v=3707026005542772939);
    top: 0;
    left: 30;
    width: 100%;
    height: 100%;
    // background-position: 50% 0;
    background-size: auto;
    background-repeat: no-repeat;
}
.header{
  height:100px;display: flex; align-items: center; justify-content:center;
}
.card-image-hover{
height: 300px;
width: 50px;
}
</style>
