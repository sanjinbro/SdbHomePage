<template>
  <div class="main-links">
    <description desc="常用连接"></description>
  </div>
</template>

<script>
import Description from "@/components/description/description";
export default {
  name: "CommonLinks",
  components: {Description}
}
</script>

<style scoped>
.main-links{
  height: calc(100% - 2rem);
  width: calc(100% - 2rem);
  background-color: #fff8ee;
  border-radius: 1.5rem;
  margin: 1rem;
  box-shadow: 0.5rem 0.5rem 0.5rem rgba(0,0,0,.3);
}
</style>
