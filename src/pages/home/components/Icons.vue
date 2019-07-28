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
  .icons {
    width: 100%;
    height: 0;
    padding-bottom: 50%;
    position: relative;
  }
  .icons >>> .swiper-container {
    height: 100%;
    width: 100%;
    position: absolute;
  }
  .icons >>> .swiper-wrapper{
    height: 100%;
    width: 100%;
    position: absolute;
  }
  .icons >>>.swiper-slide {
    display: flex;
    flex-wrap: wrap;
    flex-direction: row;
    width: 100%;
    height: 100%;
  }

  .icon-img {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    width: 25%;
    height: 50%;
  }
  .icon-img-content {
    width: 80%;
    height: 80%;
  }
  .icon-desc {
    font-size: .3rem;
  }
</style>
