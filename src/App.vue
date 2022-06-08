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
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
}
</style>
