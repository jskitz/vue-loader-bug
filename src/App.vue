<template>
  <GirlReadingIllustration class='svg-image'/>
</template>

<script>
import GirlReadingIllustration from './components/GirlReadingIllustration.vue'

export default {
  name: 'App',
  components: {
    GirlReadingIllustration
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
.svg-image {
  width: 400px;
}
</style>
