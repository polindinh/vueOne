<template>
  <div id="app">
    <myHeader msg="This is the header" />
    <myButton />
    <myBody/>
    <myFooter/>
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
import myHeader from "./components/Header.vue";
import myButton from "./components/Button.vue";
import myBody from "./components/Body.vue";
import myFooter from "./components/Footer.vue";


export default {
  name: "App",
  components: {
    myHeader,
    myButton,
    myBody,
    myFooter
  }
};
</script>

<style>
body{
  margin:0;
  padding:0;
  width:100vw;
  height: 100vh;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  /* margin-top: 60px; */
  
}
</style>
