<template>
  <div id="app">
   <appheader></appheader>
   <appintro></appintro>
   <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1440 320"><path fill="#edf057" fill-opacity="1" d="M0,256L1440,64L1440,0L0,0Z"></path></svg>
  </div>
</template>

<script>
import header from "./components/header.vue";
import intro from "./components/intro";

export default {
  name: "App",
  components: {
    appheader: header,
    appintro: intro,
  },
};
</script>

<style>

</style>
