<template>
  <div class="header">
    <div class="header-left">
      <span class="iconfont">&#xe624;</span>
    </div>
    <div class="header-input">
        <span class="iconfont">&#xe632;</span>
        <span>输入城市/景点/游玩主题</span>
      <!--<input type="text" placeholder="输入城市/景点/游玩主题" class="main-input">-->
    </div>
    <div class="header-right">
      城市
      <span class="iconfont icon-arrowdwon arrow-down"></span>
    </div>
  </div>
</template>

<script>
export default {
  name: 'homeHeader'
}
</script>
<style scoped lang="stylus">
  //样式中引用其他样式如果使用@时需要加上~
  @import "~@/assets/styles/varibles.styl"
.header
  display: flex
  line-height: .86rem
  background-color $bgColor
  color #ffffff
  .header-left
    width: .64rem
    float: left
    text-align: center
  .header-input
    flex: 1
    height .64rem
    line-height .64rem
    background-color #ffffff
    padding-left .2rem
    border-radius .1rem
    margin-top .12rem
    margin-left .2rem
    color #ccc
    .main-input
      width 80%
  .header-right
    width: 1.24rem
    float: right
    text-align: center
    .arrow-down
      font-size .24rem
      margin-top -0.1rem
      margin-left -.04rem
</style>
