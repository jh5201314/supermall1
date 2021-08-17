<template>
  <div id="app">
    <router-view/>
    <main-tab-bar/>
    <tab-bar/>
  </div>
</template>

<script>
import TabBar from './components/common/tabbar/TabBar.vue'
import MainTabBar from './components/content/mainTabbar/MainTabBar.vue'
export default {
  name: 'App',
  components: {
    MainTabBar,
    TabBar
  }
}
</script>

<style>
@import "assets/css/base.css"
</style>
