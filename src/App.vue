<template>
  <div>
    <appheader></appheader>
    <features></features>
    <appfooter></appfooter>
  </div>
</template>

<script>
import header from "./components/header.vue";
import footer from "./components/footer";
import screenshot from "./components/screenshot";

export default {
  name: "App",
  components: {
    appheader: header,
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
