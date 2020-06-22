<template>
<div id="header">
    <b-navbar toggleable="lg" type="dark">
    <b-navbar-brand href="#">Gitty</b-navbar-brand>

    <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

    <b-collapse id="nav-collapse" is-nav>
      <b-navbar-nav>
        <b-nav-item href="#">Support Server</b-nav-item>
        <b-nav-item href="#">Feedback</b-nav-item>
      </b-navbar-nav>

      <!-- Right aligned nav items -->
      <b-navbar-nav class="ml-auto">
        <b-nav-item href="#"><i class="fab fa-github-alt"></i></b-nav-item>
      </b-navbar-nav>
    </b-collapse>
  </b-navbar>
</div>    
</template>


<script>
export default {
    
}
</script>



<style scoped>

#header{
    background-color: #edf057;
    color: #000000 !important ;
}

</style>