<template>
  <div id="app">
    <div>
      <Header msg="This is the header"/>
    </div>
    <div>
      <div id="button">
        <Button/>
      </div>
    </div>
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
import Header from './components/Header.vue'
import Button from './components/Button.vue'



export default {
  name: 'App',
  components: {
    Header,
    Button
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  /* margin-top: 60px; */
  margin:0;
  padding:0;
}
</style>
