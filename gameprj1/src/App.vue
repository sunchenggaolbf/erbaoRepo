<template>
  <div id="app">
    <Page1 />
  </div>
</template>

<script>
import Page1 from './pages/page1.vue';

export default {
  name: 'App',
  components: {
    Page1,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin: 0px;
  padding:0px;
}
</style>
