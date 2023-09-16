<template>
  <div class="main-desc">{{desc}}</div>
</template>

<script>
export default {
  name: "description",
  props:['desc'],
  data() {
    return {}
  },
}
</script>

<style scoped>
.main-desc{
  margin: 1rem;
  font-size: 32px;
  font-family: TitilFont;
  width: 130px;
  height: 32px;

}
</style>
