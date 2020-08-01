<template>
  <div id="app">
    <!-- 路由的出口 -->
    123
    <div>
      <van-button type="primary">主要按钮</van-button>
      <i class="toutiao toutiao-yuedu"></i>
    </div>
    <van-cell-group>
      <van-cell title="单元格" value="内容" />
      <van-cell title="单元格" value="内容" label="描述信息" />
    </van-cell-group>
    <router-view />
  </div>
</template>
<script>
export default {
  name: 'App',
}
</script>
<style lang="less"></style>
