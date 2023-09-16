<template>
  <div class="main-tools">
    <description desc="常用工具"/>
  </div>
</template>

<script>
import Description from "@/components/description/description";
export default {
  name: "UsefulTools",
  components: {Description}
}
</script>

<style scoped>
.main-tools{
  background-color: #f5fff7;
  height: calc(100% - 2rem);
  width: calc(100% - 2rem);
  border-radius: 1.5rem;
  margin: 1rem;
  box-shadow: 0.5rem 0.5rem 0.5rem rgba(0,0,0,.3);
}
</style>
