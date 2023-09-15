<template>
  <el-menu class="top-bar" mode="horizontal" router>
    <el-menu-item index="/">首页</el-menu-item>
    <el-menu-item index="/blogs">博客专栏</el-menu-item>
    <el-menu-item index="/warehouse">文件仓库</el-menu-item>
  </el-menu>
</template>

<script>

export default {
  name: 'NavBar',
  data() {
    return {
      activeIndex: '1',
      activeIndex2: '1'
    };
  },
  methods: {
  }
}
</script>

<style scoped>
.top-bar{
  margin-bottom: 30px;
}
</style>
