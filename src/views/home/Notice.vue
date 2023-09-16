<template>
  <div class="main-notice">
    <description desc="公告栏"/>
  </div>
</template>

<script>
import Description from "@/components/description/description";
export default {
  name: "notice",
  components: {Description}
}
</script>

<style scoped>
.main-notice{
  height: calc(100% - 2rem);
  width: calc(100% - 2rem);
  background-color: #fff2f2;
  border-radius: 1.5rem;
  margin: 1rem;
  box-shadow: 0.5rem 0.5rem 0.5rem rgba(0,0,0,.3);
}
</style>
