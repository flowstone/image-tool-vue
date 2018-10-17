<template>
  <div class="index">
    <el-container>
      <el-header>
        <el-menu :default-active="activeIndex" class="el-menu-demo" mode="horizontal" @select="handleSelect">
          <el-menu-item index="1">收藏</el-menu-item>
          <el-menu-item index="2">关于</el-menu-item>
        </el-menu>
      </el-header>
      <el-container>
        <el-aside>左</el-aside>
        <el-main>中</el-main>
      </el-container>
      <el-footer>尾</el-footer>
    </el-container>
  </div>
</template>
<script>
export default {
  name: 'index'
}
</script>
<style scoped>
  el-header {
    border: 1px solid red;
  }
  el-aside {
    border: 1px solid yellow;
  }
  el-main {
    border: 1px solid blue;
  }
  el-footer {
    border: 1px solid gray;
  }
</style>
