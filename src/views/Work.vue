<template>
  <div class="work">
    <h1>作品一覧</h1>
        <div class="paper">
      <img src="../assets/img/lefty-holder.png">
      <h2>左利き用チョークフォルダー</h2>
      <p>左利きの人が黒板に文字を書きやすくするためのチョークホルダー。<br>＜TinkerCAD＞<br>2023年3月</p>
    </div>
    <div class="paper">
      <img src="../assets/img/3bags.png">
      <h2>3bags</h2>
      <p>防災用品の提案と管理ができるアプリ。非常時にはBluetoothを使った通信ができる。<br>＜Flutter＞<br>2023年2月</p>
    </div>
    <div class="paper">
      <img src="../assets/img/scope.png">
      <h2>Scope</h2>
      <p>簡単なチェスがコンセプトのボードゲーム<br>＜Unity,C#＞<br>2022年2月</p>
    </div>
    <div class="paper">
      <img onclick="location.href='https://fabble.cc/marunasubi'" src="../assets/img/tatchpen.png">
      <h2>タッチペン固定装置</h2>
      <p>握力がなくてもタッチペンを手に固定して使うことができる装置。<br>＜TinkerCAD＞<br>2021年4月</p>
    </div>
    <div class="paper">
      <img src="../assets/img/brushtalken.png">
      <h2>Brushtalk with translation function</h2>
      <p>翻訳機能付きビデオチャット<br>＜HTML, CSS, JavaScript＞<br>2021年3月</p>
    </div>
    <div class="paper">
      <img onclick="location.href='https://brushtalk-5c0f3.web.app/'" src="../assets/img/brushtalk.png">
      <h2>ぶらっしゅとーく</h2>
      <p>小さい子からお年寄りまで使えるコミュニケーションアプリ<br>＜Vue.js＞<br>2020年11月</p>
    </div>
    <div class="paper">
      <img onclick="location.href='https://scratch.mit.edu/projects/511557389/'" src="../assets/img/medisense.png">
      <h2>Medisense</h2>
      <p>病気判断アプリ<br>＜Scratch＞<br>2020年1月</p>
    </div>
    <div class="paper">
      <img onclick="location.href='https://www.youtube.com/shorts/SbbKUTC4uNs'" src="../assets/img/magicwand.png">
      <h2>Magic Wand</h2>
      <p>目の見えない人が信号の色を判別するための装置（模型）<br>＜Micro:bit, Makecode, TinkerCAD＞<br>2019年12月</p>
    </div>
    <div class="paper">
      <img onclick="location.href='https://scratch.mit.edu/projects/510518474/'" src="../assets/img/sinsoroban.png">
      <h2>真そろばん道場</h2>
      <p>「そろばん道場」を使いやすくしたもの<br>＜Scratch＞<br>2019年8月</p>
    </div>
    <div class="paper">
      <img onclick="location.href='https://scratch.mit.edu/projects/511331101/'" src="../assets/img/soroban.png">
      <h2>そろばん道場</h2>
      <p>そろばんを始めたばかりの人がたまの動かし方を覚えるためのアプリ<br>＜Scratch＞<br>2019年2月</p>
    </div> 
  </div>
</template>

<style>
.paper {
  border-bottom: 3px solid #aaa;
  background-color: #6B818E;
  padding: 2em;
  color: #ffffff;
}

#work {
  background-color: "#FER2E4";
}

.paper {
  margin-top: 100px;
}

.qqq {
  color: #FCD4D5;
}

.work h1{
  position: relative;
  display: inline-block;
  padding: 0 65px;
  text-align: center;
}

.work h1:before,
.work h1:after {
  position: absolute;
  top: calc(50% - 3px);
  width: 50px;
  height: 6px;
  content: '';
  border-top: solid 2px #000;
  border-bottom: solid 2px #000;
}

.work h1:before {
  left: 0;
}

.work h1:after {
  right: 0;
}

.work img{
  width: 60%;
}
</style>