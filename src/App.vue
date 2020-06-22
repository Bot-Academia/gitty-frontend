<template>
  <div id="app">
   <appheader></appheader>
   <appintro></appintro>
   <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1440 320"><path fill="#edf057" fill-opacity="1" d="M0,256L1440,64L1440,0L0,0Z"></path></svg>
   <features></features>
    <appfooter></appfooter>
  </div>
</template>

<script>
import header from "./components/header.vue";
import intro from "./components/intro";
import footer from "./components/footer";
import screenshot from "./components/screenshot";
export default {
  name: "App",
  components: {
    appheader: header,
    appintro: intro,
    appfooter: footer,
    features: screenshot,
  },
};
</script>

<style>
body {
  font-family: "Poppins", sans-serif;
  background-color: #24252a;
  min-height: 100%;
  display: flex;
  flex-direction: column;
}
html {
  scroll-behavior: smooth;
  min-height: 100%;
  min-width: 100%;
  position: relative;
  max-width: 100%;
}
</style>
