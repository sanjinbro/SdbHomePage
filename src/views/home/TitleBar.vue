<template>
  <div class="title">
    <div class="title-logo">
      <el-avatar :src="avatar" shape="square" :size="65"></el-avatar>
    </div>
    <div class="title-name">金金和他的粉丝朋友们</div>
    <div class="title-right"> 占位占位占位</div>
  </div>
</template>

<script>
import avatar from '@/assets/avatar1.png'
import "@/assets/fonts/font.css"
export default {
  name: "TitleBar",
  data(){
    return {
      avatar:avatar
    }
  }
}
</script>

<style scoped>
.title{
  width: 100%;
  height: 100%;
}
.title-logo{
  position: relative;
  top: calc(50% - 2rem);
  left: 1rem;
  width: 65px;
  float: left;
}
.title-name{
  position: relative;
  top: calc(50% - 25px);
  width: 450px;
  height: 50px;
  font-size: 45px;
  left: calc(50% - 300px);
  float: left;
  font-family: TitilFont;
}
.title-right{
  position: relative;
  right: 10px;
  float: right;
}

</style>
