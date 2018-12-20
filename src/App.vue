<template>
  <div id="app">
    <!--<img src="./assets/logo.png">-->
    <!--router-view显示当前路由地址所对应的页面-->
    <!--单页应用：JS渲染，优点：页面切换快，缺点：首屏时间慢，SEO慢，服务器端渲染可解决部分问题-->
    <!--多页应用：页面跳转后端返回新的html页面，优点：首页时间快，SEO效果好，缺点：页面切换慢-->
    <!--reset-css文件：做不同移动端适配时初始化的样式表-->
    <!--border-css文件：一像素边框解决方案-->
    <router-view/>
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
