<template>
  <div id="app">
    <!-- the router outlet, where all matched components would ber viewed -->
    <div class="links">
      <router-link v-bind:to="'/'">Home</router-link>
      <router-link v-bind:to="'/about'">About</router-link>
      <router-link v-bind:to="'/contact'">Contact</router-link>
    </div>
    <router-view></router-view>
  </div>
</template>

<script>
export default {
  name: 'app',
}
</script>
<!-- styling for the component -->
<style>

body {
  margin: 0;
}

#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #fff;
}

.links {
  /*z-index: 1;*/
  text-align: right;
}

a {
  text-decoration: none;
  color: #fff;
  margin-left: 20px;
  margin-right: 20px;
}

a:visited {
  color: #fff;
}
</style>
