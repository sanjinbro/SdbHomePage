<template>
  <div class="main-homepage">
    <div class="main-title">
      <title-bar/>
    </div>
    <div class="nav-bar">
      <nav-bar/>
    </div>
    <div class="main-container">
      <dashboard/>
    </div>
  </div>
</template>

<script>
import TitleBar from "@/views/home/TitleBar";
import NavBar from "@/views/home/NavBar";
import Dashboard from "@/views/home/dashboard";
export default {
  name: 'Home',
  data() {
    return {

    }
  },
  methods: {
  },
  components: {
    Dashboard,
    NavBar,
    TitleBar
  }
}
</script>

<style scoped>
.main-homepage{
  height: 98%;
  width: 99%;
}
.main-title{
  height: 10%;
  background-color: lightsalmon;
}
.nav-bar{
  height: 7%;
  background-color: lightcyan;
}
.main-container{
  height: 83%;
  background-color: lavender;
  border-radius: 0.8rem;
}
</style>
