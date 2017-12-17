<template>
  <div class="home">
    <h1>{{ msg }}</h1>
    <h5>{{ tagline }}</h5>
  </div>
</template>

<script>
export default {
  name: 'Home',
  data () {
    return {
      msg: 'Welcome',
      tagline: 'Lorem ipsum dolor sit amet'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.home {
  height: 100vh;
  width: 100vw;
  margin-top: -85px;
  background-image: url('../assets/background.jpeg');
  background-size: cover;
  background-repeat: no-repeat;
  /*z-index: 2;*/
}

h1 {
  text-transform: uppercase;
  font-size: 6em;
  letter-spacing: 5px;
  padding-top: 150px;
}

h5 {
  font-weight: normal;
  font-size: 1.3em;
  letter-spacing: 10px;
  margin-top: -90px;
}


</style>
