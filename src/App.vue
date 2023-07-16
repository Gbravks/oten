<template>
  <div>
    <NavBar />
    <router-view />
  </div>
</template>

<script>
import NavBar from './components/layout/NavBar.vue';

export default {
  name: 'App',
  components: {
    NavBar,
  },
};
</script>

<style>
/* Add any global styles here */
</style>