<template>
  <div class="navbar-main">
    <el-menu :default-active="activateIndex" class="navbar-el-menu" mode="horizontal" @select="handleSelect">
      <el-menu-item index="1">主页面</el-menu-item>
      <el-submenu index="2">
        <template slot="title">详情页面</template>
        <el-menu-item index="2-1">详情1</el-menu-item>
        <el-menu-item index="2-2">详情2</el-menu-item>
      </el-submenu>
      <el-menu-item index="3">活动中心</el-menu-item>
    </el-menu>
  </div>
</template>

<script>
export default {
  name: "index",
  data(){
    return{
      activateIndex:'1'
    }
  },
  methods:{
    handleSelect(key,keyPath){
      console.log(key,keyPath)
    }
  }
}
</script>

<style scoped>
.navbar-main{
  width: 100%;
  height: 100%;
}
.navbar-el-menu{
  width: 100%;
  height: 100%;
}
</style>
