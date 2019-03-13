<template>
  <div class="headerContainer">
    <div class="toBack">
      <span class="iconfont">&#xe60c;</span>
    </div>
    <div class="searchInput">
      <input type="text">
    </div>
    <div class="selectCity">
      上海
      <span class="iconfont">&#xe64a;</span>
    </div>
  </div>
</template>
<script>
export default {
  data() {
    return {};
  }
};
</script>
<style lang="stylus" scoped>
@import '~@/assets/styles/variables.styl';
.headerContainer 
  line-height: $headerHeight;
  background-color: $bgColor;
  height: $headerHeight;
  width: 100%;
  position: fixed;
  z-index: 3;
  padding: 0 40px;
  box-sizing: border-box;
  float left;
  .searchInput 
    width 120%;
    input 
     width 120%;
  .iconfont 
      color #fff;
</style>