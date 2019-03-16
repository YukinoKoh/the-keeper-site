<template>
  <div id="app">
    <!--<div class="top-text text-left">
      <p><img class="top-logo" alt="Vue logo" src="./assets/logo3.png">
      The keeper</p>
    </div>-->
    <img alt="Vue logo" src="./assets/logo3.png">
    <HelloWorld msg="The keeper"/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'app',
  components: {
    HelloWorld
  }
}
</script>

<style>
body{
  background-color: #408bee;
  margin: 0;
}
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  margin-top: 60px;
}
.text-left{
  text-align: left;
}
.text-right{
  text-align: right;
}
.top-text{
  vertical-align: middle;
  color: #fff;
}
.top-logo{
  margin: 0;
  width: 80px;
}
</style>
