<template>
  <div>
    <home-header></home-header>
    <home-swiper></home-swiper>
  </div>
</template>

<script>
import homeHeader from './components/header'
import HomeSwiper from './components/swiper'
export default {
  name: 'home',
  components: { homeHeader, HomeSwiper }

}
</script>

<style scoped lang="sass">

</style>
