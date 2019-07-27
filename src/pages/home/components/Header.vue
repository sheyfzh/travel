<template>
  <div class="header">
    <div class="header-left"><span class="iconfont back-icon">&#xe605;</span></div>
    <div class="header-input"><span class="iconfont">&#xe6a2;</span>输入城市景点/游玩主题</div>
    <div class="header-right">城市<span class="iconfont arrow-icon">&#xe6aa;</span></div>
  </div>
</template>

<script>
export default {
  name: 'HomeHeader'
}
</script>

<style scoped>
  .header {
    display:flex;
    height: .86rem;
    line-height: .86rem;
    font-size: .3rem;
    background: #00bcd4;
    color: #fff;
  }
  .header-left {
    width: .64rem;
    border-radius: .1rem;
  }
  .back-icon{
    font-size: .5rem;
  }
  .header-input {
    flex:1;
    height: .64rem;
    line-height: .64rem;
    background: #fff;
    margin-top: .12rem;
    margin-bottom: .12rem;
    margin-left: .12rem;
    margin-right: .12rem;
    border-radius: .1rem;
    color: #ccc;
    text-align: left;
    padding-left: .12rem;
  }
  .header-right {
    width: 1.24rem;
    font-size: .32rem;
  }
  .arrow-icon{
    font-size: .42rem;
  }

</style>
