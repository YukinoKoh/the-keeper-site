<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <h2>
      荷物の受け取りや受け渡し、忙しく家にいない時に不便と感じていませんか？<br>
      家にあるサーフボード、ゴルフバッグ、貸すことは無理と思っていませんか？<br>
    </h2>
    <!--<img alt="Vue logo" src="./../assets/logo2.png">-->
    <ul>
      <li><a href="https://router.vuejs.org" target="_blank" rel="noopener">Privacy Policy</a></li>
      <li><a href="https://vuex.vuejs.org" target="_blank" rel="noopener">Terms of Service</a></li>
    </ul>
    <a href="#" class="myButton">+</a>
  </div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
#app{
  background-color: #000;
}
h1 {
  color: #ffffff;
  font-size: 48px;
}
h2 {
  color: #a3d4ff;
  font-size: 18px;
  font-weight: 500;
}
h3 {
  margin: 40px 0 0;
}

ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #2864f0;
}
.myButton {
    -moz-box-shadow: 0px 3px 3px -2px #2f65b7;
    -webkit-box-shadow: 0px 3px 3px -2px #2f65b7;
    box-shadow: 0px 3px 3px -2px #2f65b7;
    background-color:#fff;
    -moz-border-radius:37px;
    -webkit-border-radius:37px;
    border-radius:37px;
    display:inline-block;
    cursor:pointer;
    color:#2f65b7;
    font-family:Arial;
    font-size:24px;
    padding:20px;
    width: 25px;
    height: 25px;	
    text-decoration:none;
    position: fixed;
    bottom: 48px;
    right: 48px;
}
.myButton:hover {
	background-color:#a3d4ff;
}
.myButton:active {
	position:relative;
	top:1px;
}
</style>
