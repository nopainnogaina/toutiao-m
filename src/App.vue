<template>
  <div id="app">
    <!-- 路由出口，不写会看不到路由界面 -->
    <router-view />
    <h1>黑马头条</h1>
  </div>
</template>
<script>
export default {
  // 不管用不用组件，都要把组件名字起好，以防后续使用
  name: 'App'
}
</script>

<style lang="less" scoped></style>
