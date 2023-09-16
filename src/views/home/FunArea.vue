<template>
  <div class="main-fun-area">
    <description desc="娱乐排行"/>
  </div>
</template>

<script>
import Description from "@/components/description/description";
export default {
  name: "funArea",
  components: {Description}
}
</script>

<style scoped>
.main-fun-area{
  background-color: #eefcff;
  height: calc(100% - 2rem);
  width: calc(100% - 2rem);
  border-radius: 1.5rem;
  margin: 1rem;
  box-shadow: 0.5rem 0.5rem 0.5rem rgba(0,0,0,.3);
}

</style>
