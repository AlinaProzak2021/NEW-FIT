<template>
  <div id="app">
    <aboutPl></aboutPl>
  </div>
</template>
<script>
 import aboutPl from './mainPage/blockcircle.vue'

export default {
  name: "app",
  components: {
     aboutPl
  },
};
</script>
<style>
* {
  margin: 0;
  padding: 0;
}
html,
body {
  width: 100%;
  height: 100%;
  
}
 
#app {
  width: 100%;
  height: 100%;
}
</style>
