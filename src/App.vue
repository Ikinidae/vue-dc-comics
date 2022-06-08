<template>
  <div id="app">
    <MyHeader/>
    <MyMain/>
    <MyFooter/>
  </div>
</template>

<script>
import MyHeader from './components/Header/MyHeader.vue'
import MyMain from './components/Main/MyMain.vue'
import MyFooter from './components/Footer/MyFooter.vue'

export default {
  name: 'App',
  components: {
    MyHeader, MyMain, MyFooter
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
  // padding-left: 10%;
  // padding-right: 10%;
}
</style>
