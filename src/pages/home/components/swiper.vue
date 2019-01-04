<template>
  <div>
    <swiper :options="swiperOption">
      <!-- slides -->
      <swiper-slide>
        <img src="http://img1.qunarzz.com/piao/fusion/1811/7c/8e5c4ab8ee8b7402.jpg_750x200_dd7a38dd.jpg" class="swiper-img">
      </swiper-slide>
      <swiper-slide>
        <img src="http://img1.qunarzz.com/piao/fusion/1811/39/6b1f0402bb1d5902.jpg_750x200_3c7661d6.jpg" alt="">
      </swiper-slide>
      <swiper-slide>
        <img src="http://img1.qunarzz.com/piao/fusion/1812/a8/33a03fe1c213da02.jpg_750x200_dd491fc5.jpg" alt="">
      </swiper-slide>
      <swiper-slide>
        <img src="http://img1.qunarzz.com/piao/fusion/1810/af/30ffcf34e9819f02.jpg_750x200_736b7236.jpg" alt="">
      </swiper-slide>
      <!-- Optional controls -->
      <div class="swiper-pagination"  slot="pagination"></div>
    </swiper>
  </div>
</template>

<script>
export default {
  name: 'homeSwiper',
  data () {
    return {
      swiperOption: {}
    }
  }
}
</script>

<style scoped lang="stylus">
  .swiper-img
    width 25rem
</style>
