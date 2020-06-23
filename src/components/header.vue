<template>
<div id="header">
    <b-navbar toggleable="lg" type="light">
    <b-navbar-brand @click="change1('apphome')" class="brand">Gitty</b-navbar-brand>

    <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

    <b-collapse id="nav-collapse" is-nav>
      <b-navbar-nav>
        <b-nav-item href="https://discord.gg/VNXVUt6">Support Server</b-nav-item>
        <b-nav-item @click="change2('contact')">Feedback</b-nav-item>
      </b-navbar-nav>

      <!-- Right aligned nav items -->
      <b-navbar-nav class="ml-auto">
        <b-nav-item href="https://github.com/Bot-Academia/gitty" target="_blank"><i class="fab fa-github-alt"></i></b-nav-item>
      </b-navbar-nav>
    </b-collapse>
  </b-navbar>
</div>    
</template>

<script>
export default {
    methods: {
        change1(item) {
            this.$emit("namewasreset", item);
        },
        change2(item) {
            this.$emit("namewasreset", item);
        },
    }
};
</script>

<style scoped>

#header{
    background-color: #edf057;
}

.brand{
  font-size: 2rem;
}

i{
    font-size: 25px;
}
.brand{
    cursor: pointer;
}
</style>
