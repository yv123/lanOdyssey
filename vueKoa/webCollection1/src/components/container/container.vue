<template>
  <div class="page-container">
    <header-nav></header-nav>
    <router-view class="main-layout"></router-view>
  </div>
</template>

<script>
import headerNav from './header.vue'

export default {
  components: {
    headerNav
  }
}
</script>

<style>
.page-container{
  overflow: hidden;
}
.main-layout {
  /* padding-top: 10px; */
  position: absolute;
  top: 60px;
  width: 100%;
}
</style>
