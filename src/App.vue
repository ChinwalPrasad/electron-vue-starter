<template>
  <div id="app">
    <navigation></navigation>
    <router-view/>
  </div>
</template>
<script>
import Navigation from './components/Navigation.vue';
export default {
  components: { Navigation },
}
</script>
<style>
  @import './assets/css/style.css';
</style>
