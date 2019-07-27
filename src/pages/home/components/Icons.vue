<template>
  <div class="icons">
    <swiper :options="swiperOption">
      <swiper-slide>
        <div class="icon-img">
          <img src="http://img1.qunarzz.com/piao/fusion/1803/95/f3dd6c383aeb3b02.png" class="icon-img-content">
          <div class="icon-desc">热门景点</div>
        </div>
        <div class="icon-img">
          <img src="http://img1.qunarzz.com/piao/fusion/1803/95/f3dd6c383aeb3b02.png" class="icon-img-content">
          <div class="icon-desc">热门景点</div>
        </div>
        <div class="icon-img">
          <img src="http://img1.qunarzz.com/piao/fusion/1803/95/f3dd6c383aeb3b02.png" class="icon-img-content">
          <div class="icon-desc">热门景点</div>
        </div>
        <div class="icon-img">
          <img src="http://img1.qunarzz.com/piao/fusion/1803/95/f3dd6c383aeb3b02.png" class="icon-img-content">
          <div class="icon-desc">热门景点</div>
        </div>
        <div class="icon-img">
          <img src="http://img1.qunarzz.com/piao/fusion/1803/95/f3dd6c383aeb3b02.png" class="icon-img-content">
          <div class="icon-desc">热门景点</div>
        </div>
        <div class="icon-img">
          <img src="http://img1.qunarzz.com/piao/fusion/1803/95/f3dd6c383aeb3b02.png" class="icon-img-content">
          <div class="icon-desc">热门景点</div>
        </div>
        <div class="icon-img">
          <img src="http://img1.qunarzz.com/piao/fusion/1803/95/f3dd6c383aeb3b02.png" class="icon-img-content">
          <div class="icon-desc">热门景点</div>
        </div>
        <div class="icon-img">
          <img src="http://img1.qunarzz.com/piao/fusion/1803/95/f3dd6c383aeb3b02.png" class="icon-img-content">
          <div class="icon-desc">热门景点</div>
        </div>
      </swiper-slide>
      <swiper-slide>
        <div class="icon-img">
          <img src="http://img1.qunarzz.com/piao/fusion/1803/95/f3dd6c383aeb3b02.png" class="icon-img-content">
          <div class="icon-desc">热门景点</div>
        </div>
        <div class="icon-img">
          <img src="http://img1.qunarzz.com/piao/fusion/1803/95/f3dd6c383aeb3b02.png" class="icon-img-content">
          <div class="icon-desc">热门景点</div>
        </div>
      </swiper-slide>
      <div class="swiper-pagination" slot="pagination"></div>
    </swiper>
  </div>
</template>

<script>
export default {
  name: 'HomeIcons',
  data () {
    return {
      swiperOption: {
        pagination: '.swiper-pagination',
        // 循环显示
        loop: true
      }
    }
  }
}
</script>
<style scoped>
  .icons >>> .swiper-container .swiper-wrapper .swiper-slide {
    display: flex;
    flex-wrap: wrap;
    width: 100%;
    height: 0;
    padding-bottom: 50%;
  }

  .icons >>> .swiper-pagination-bullet-active{
    background: coral;
  }
  .icon-img {
    display: flex;
    flex-direction: column;
    align-items: center;
    width: 25%;
    height: 0;
    padding-bottom: 25%;
  }

  .icon-img-content {
    margin-top: .1rem;
    width: 70%;
    height: auto;
  }

  .icon-desc {
    padding: .1rem;
    font-size: .3rem;
    color: #333333;
  }
</style>
