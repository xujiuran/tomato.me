<script setup lang='ts'>

</script>

<template>
  <div class="common-layout">
    <el-container class="my-container">
      <el-aside class="my-aside">
        <Menu />
      </el-aside>
      <el-container>
        <el-header>Header</el-header>
        <el-main class="my-main">
          <router-view />
        </el-main>
      </el-container>
    </el-container>
  </div>
</template>

<style lang='scss' scoped>
.my-container {
  height: 100vh;
}
.my-main {
  flex: 1;
}
</style>
