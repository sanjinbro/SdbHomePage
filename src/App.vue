<template>
  <div id="app">
    <NavBar></NavBar>
    <el-row :gutter="20">
      <el-col :span="12">
        <div class="grid-content bg-purple">
          <Notice></Notice>
        </div>
      </el-col>
      <el-col :span="12">
        <div class="grid-content bg-purple">
          <CommonLinks></CommonLinks>
        </div>
      </el-col>
    </el-row>

    <el-row :gutter="20">
      <el-col :span="12">
        <div class="grid-content bg-purple">
          <UsefulTools></UsefulTools>
        </div>
      </el-col>
      <el-col :span="12">
        <div class="grid-content bg-purple">
          <FunnyArea></FunnyArea>
        </div>
      </el-col>
    </el-row>
    <router-view></router-view>
  </div>
</template>

<script>
import NavBar from "@/components/NavBar";
import CommonLinks from "@/components/CommonLinks";
import FunnyArea from "@/components/FunnyArea";
import Notice from "@/components/Notice";
import UsefulTools from "@/components/UsefulTools";
export default {
  name: 'app',
  components: {
    FunnyArea,
    UsefulTools,
    CommonLinks,
    Notice,
    NavBar,

  }
}
</script>

<style>

</style>
