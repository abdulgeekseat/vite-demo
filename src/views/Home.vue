<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <About/>
  </div>
</template>

<script>
// @ is an alias to /src
import About from './About.vue'

export default {
  name: 'Home',
  components: {
    About
  }
}
</script>
