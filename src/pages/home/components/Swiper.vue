<template>
  <div class="wrapper">
    <swiper :options="swiperOption">
      <!-- slides -->
      <swiper-slide v-for='item of swiperList' :key="item.id">
        <img class="swiper-img"
             :src="item.imgUrl">
      </swiper-slide>
      <!-- Optional controls -->
      <div class="swiper-pagination" slot="pagination"></div>

      <!--左右的箭头-->
      <!--<div class="swiper-button-prev" slot="button-prev"></div>-->
      <!--<div class="swiper-button-next" slot="button-next"></div>-->
      <!--滚动条-->
      <!--<div class="swiper-scrollbar"   slot="scrollbar"></div>-->
    </swiper>
  </div>
</template>

<script>
export default {
  name: 'HomeSwiper',
  data () {
    return {
      swiperOption: {
        pagination: '.swiper-pagination',
        // 循环显示
        loop: true
      },
      swiperList: [{
        id: '0001',
        imgUrl: 'http://mp-piao-admincp.qunarzz.com/mp_piao_admin_mp_piao_admin/admin/20196/01549e224da474a72681614810d07860.jpg_750x200_47325a53.jpg'
      },
      {
        id: '0002',
        imgUrl: 'http://mp-piao-admincp.qunarzz.com/mp_piao_admin_mp_piao_admin/admin/20197/ae8987bff39ff10e82675a3643154e66.jpg_750x200_0f187b2e.jpg'
      },
      {
        id: '0003',
        imgUrl: 'http://mp-piao-admincp.qunarzz.com/mp_piao_admin_mp_piao_admin/admin/20194/0ba6d3d25a22d6a0209e17292af2c16f.jpg_750x200_3b96e112.jpg'
      }]
    }
  }
}
</script>

<style scoped>

  .wrapper >>> .swiper-pagination-bullet-active{
    background:#fff
  }
  .wrapper {
    width:100%;
    height: 0;
    overflow: hidden;
    padding-bottom: 26.5%;
  }
  .swiper-img {
    width: 100%;
    height: auto;
  }
</style>
