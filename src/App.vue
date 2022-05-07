<template>
  <div id="app">
    <h1>黑马头条</h1>
    <div>
      <i class="toutiao toutiao-pinglun"></i>
    </div>
    <van-button type="primary">主要按钮</van-button>
    <van-button type="info">信息按钮</van-button>
    <router-view />
  </div>
</template>
<script>
export default {
  // eslint-disable-next-line comma-dangle
  name: 'App',
}
</script>

<style lang="less"></style>
