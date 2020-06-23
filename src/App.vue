<template>
  <div id="app">
   <appheader @namewasreset="selected = $event"></appheader>
    <component :is="selected">
    </component>
    <appfooter></appfooter>
  </div>
</template>

<script>
import header from "./components/header.vue";
import footer from "./components/footer";
import apphome from "./apphome";
import contact from "./contact";
export default {
  name: "App",
    data(){
      return{
            selected: "apphome",
        };
    },
  components: {
    appheader: header,
    appfooter: footer,
    apphome: apphome,
    contact: contact
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
