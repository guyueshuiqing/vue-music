<template>
  <div id="app">
    <m-header></m-header>
  </div>
</template>

<script>
import MHeader from 'components/m-header/MHeader'
export default {
  name: 'App',
  components: {
    MHeader
  }
}
</script>

<style scoped lang="less" >
  @import "common/less/variable";
  #app{
    color: @color-theme;
  }
</style>
