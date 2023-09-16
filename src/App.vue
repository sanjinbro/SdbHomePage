<template>
  <div id="app">
    <router-view></router-view>
  </div>
</template>

<script>
export default {
  name: 'app'
}
</script>

<style>
#app{
  height: 100%;
  width: 100%;
  display: grid;
  place-items: center;
}
html{
  height: 100%;
  border: 0;
  padding: 0;
  margin: 0;
}
body{
  height: 100%;
  margin: 0;
}
</style>
