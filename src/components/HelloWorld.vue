<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <h4>
      荷物の受け取りや受け渡し、忙しく家にいない時に不便と感じていませんか？<br>
      子供の送り迎え急な用事でできない時、猫の手でも借りたい..と感じていませんか？<br>
    </h4>
    <h2> The Keeperは<br>「助けてもらいたいけど色々な人を紹介するなんて...アレンジが面倒...」<br>な方のためのサービスです！</h2>
    <img alt="image UI" src="./../assets/chat-ui1.png">
    <br>
    <br>
      <h5>「平日にサーフボードを渡すのは無理だ。。なぜか急に山田がサーフィンする気になってボード貸してって言っているが。。いつも暇そうな近所のカフェの店主に預けられたらな、、でも店主は山田のこと知らないから、説明が面倒だ。。諦めるしかないのか。せっかくサーフィン友達ができそうなのに><..」そんな時にThe keeperを使いましょう。</h5>
    <br>
    <a href="#" class="tryButton">試してみる</a>
    <h4>使い方</h4>
    <h3>1. 依頼人はThe keeperへ受取人を連絡する</h3>
    <img alt="image UI" src="./../assets/chat-ui-1.png">
    <h3>2. 受取人はThe keeperから送られたQRコードで認証を受けて受取りを完了する</h3>
    <img alt="image UI" src="./../assets/chat-ui-2.png">
    <h3>3. 依頼人は受取り完了の通知を受け取る</h3>
    <img alt="image UI" src="./../assets/chat-ui-3.png">
    <br>
    <a href="#" class="tryButton">試してみる</a>
    <ul>
      <li><a href="https://router.vuejs.org" target="_blank" rel="noopener">Privacy Policy</a></li>
      <li><a href="https://vuex.vuejs.org" target="_blank" rel="noopener">Terms of Service</a></li>
    </ul>
    <!--<a href="#" class="myButton">+</a>-->
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
  color: #ffffff;
  font-size: 24px;
  font-weight: 500;
  margin: 40px;
}
h3 {
  color: #ffffff;
  font-size: 24px;
  font-weight: 500;
  margin: 20px;
}
h4 {
  color: #a3d4ff;
  font-size: 18px;
  font-weight: 500;
  margin: 10px 0 0 0;
}
h5 {
  color: #a3d4ff;
  width: 80%;
  text-align: center;
  font-size: 14px;
  font-weight: 300;
  margin: 0px auto;
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
  color: #a3d4ff;
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
.tryButton {
  -moz-box-shadow: 0px 3px 7px 2px #2f65b7;
  -webkit-box-shadow: 0px 3px 7px 2px #2f65b7;
  box-shadow: 0px 3px 7px 2px #2f65b7;
  margin: 0 auto;
  -moz-border-radius:24px;
  -webkit-border-radius:24px;
  border-radius:24px;
  display:inline-block;
  cursor:pointer;
  color:#2864f0;
  font-family:Arial;
  font-size:17px;
  padding:16px 31px;
  text-decoration:none;
  background-color:#fff;
}
.tryButton:hover {
  background-color:#a3d4ff;
}
.tryButton:active {
  position:relative;
  top:1px;
}
</style>
