<template>
  <div>
    <div style="z-index: 0; float:left; height: 50px;">
      <router-link to="/">
        <img src="http://localhost:8088/img/logo.jpg" alt="LOGO">
      </router-link>
    </div>
    <div class="top">
      <router-link to="/login">
        登陆
      </router-link>
      <span>&nbsp;</span>
      <router-link to="/home">
        <i class="fa fa-user fa-2x"> </i>
      </router-link>
      <span>&nbsp;</span>
      <a href="#">
        <i class="fa fa-bell fa-2x"> </i>
      </a>
      <span>&nbsp;</span>
      <a href="#">
        <i class="fa fa-phone fa-2x"> </i>
      </a>
      <span>&nbsp;</span>
      <a href="#">
        <i class="fa fa-cog fa-2x"> </i>
      </a>
    </div>
  </div>
</template>

<script>
export default {
  name: "Navigation"
}
</script>

<style scoped>
.top {
  float: right;
  margin: 0 20px;
}
</style>
