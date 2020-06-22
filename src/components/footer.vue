<template>
  <div class="footer" id="footers">
    <p>
        <span class="copyright">&copy; <a href="https://github.com/Bot-Academia" target="_blank">Bot-Academia</a></span>
        <span class="version">V 1.0.0</span>
    </p>
  </div>
</template>

<script>
export default {
  name: "appfooter",
};
</script>

<style scoped>
a {
    color:darkgray;
  text-decoration: none;
}
a:hover{
    color: white;
      transition: 0.3s;
}
.footer {
    height: 50px;
  font-family: 'Poppins', sans-serif;
  font-size: large;
  position: relative;
  bottom: 0;
  width: 100%;
  left: 0;
  background-color: rgb(23, 24, 27);
  color:darkgray;
  text-align: center;

}
p {
  font-size: larger;
}
.version{
    float: right;
    margin-top: 10px;
    margin-right: 10px;
    margin-bottom: 10px;
}
.copyright{
    margin-left: 10px;
    margin-top: 10px;
    float: left;
    margin-bottom: 10px;
}
</style>