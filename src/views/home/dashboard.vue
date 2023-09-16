<template>
  <div class="main-dashboard">
    <div class="dashboard-left">
      <fun-area/>
    </div>
    <div class="dashboard-right">
      <div class="dashboard-right-up">
        <notice/>
      </div>
      <div class="dashboard-right-down">
        <div class="dashboard-right-down-left">
          <useful-tools/>
        </div>
        <div class="dashboard-right-down-right">
          <common-links/>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import FunArea from "@/views/home/FunArea";
import Notice from "@/views/home/Notice";
import UsefulTools from "@/views/home/UsefulTools";
import CommonLinks from "@/views/home/CommonLinks";
export default {
  name: "dashboard",
  components: {CommonLinks, UsefulTools, Notice, FunArea}
}
</script>

<style scoped>
.main-dashboard{
  height: 100%;
  width: 100%;
  display: grid;
  grid-template-columns: 1fr 1fr;
}
.dashboard-left{

}
.dashboard-right{

  display: grid;
  grid-template-rows: 1fr 1fr;
}
.dashboard-right-up{

}
.dashboard-right-down{

  display: grid;
  grid-template-columns: 1fr 1fr;
}
.dashboard-right-down-left{

}
.dashboard-right-down-right{

}
</style>
