<template>
  <div>
    <img alt="Vue logo" src="./assets/logo.png">
    <Block />
    <Textbox />
  </div>
</template>

<script>
import Block from './components/Block'
import Textbox from './components/Textbox'

export default {
  name: 'App',
  components: {
    Block,
    Textbox
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2d5883;
  margin-top: 60px;
}
</style>
