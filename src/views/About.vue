<template>

  <div class="about">
    <img alt="image" id="washi" src="../assets/img/harunasubi.png">
    

    <div id="profile">
      <h2>Hirakawa Haruna</h2>
      <h2>SNS</h2>
        <p>Twitter: <a class="aqw" href="https://twitter.com/86cats2">@86cats2</a></p>
        <p>Fabble: <a class="aqw" href="https://fabble.cc/marunasubi">Marunasubi</a></p>

      <h2>Awards</h2>
        <p>2023.03 第81回学生児童発明くふう展 入選</p>
        <p>2022.03 第80回学生児童発明くふう展 奨励賞</p>
        <p>2021.03 AppJammingSummit2021 Most Creative Award（Senior部門）</p>
        <p>2021.03 全国選抜小学生プログラミング大会 グランプリ</p>
        <p>2020.12 Tech Kids GrandPrix2020 LINE賞、2位</p>
        <p>2019.12 全日本小中学生ロボット選手権小学生の部 経済産業大臣賞</p>
        <p>2019.09 Tech Kids GrandPrix2019 サイバーエージェント賞</p>

      <h2>活動</h2>
        <p>2023.04 神山まるごと高専奨学生（Rubyコース）</p>
        <p>2021.10 セキュリティキャンプ全国大会オンラインDトラック 修了</p>
        <p>2020.12 未踏ジュニアスーパークリエイター 認定</p>

      <h2>Articles</h2>
        <p>2022.19 Life is Tech! <a class="aqw" href="https://life-is-tech.com/news/interview/221021-girls">【CodeGirlsStoriesINTERVIEW#02】地域と連携し、アプリ開発を社会で役立てたい！</a></p>
        <p>2022.03 プレジデントファミリー春号 「超サイエンスキッズを育てたお宅を拝見」</p>
        <p>2021.12 Dream Navi1月号特集「プログラミング教育を考える」 </p>
        <p>2020.12 こどもとIT <a class="aqw" href="https://www.watch.impress.co.jp/kodomo_it/news/1300807.html">小中高生がユーザーテストを回し、独自の視点と技術力で”未踏”の課題解決に取り組む</a></p>
        <p>2021.03 CyberAgent FEATUReS <a class="aqw" href="https://www.cyberagent.co.jp/way/features/list/detail/id=25908">プログラミングを武器に、ボーダレスな活躍をする宮崎県のキッズプログラマー</a></p>
        <p>2021.02 LINEentry公式ブログ <a class="aqw" href="http://line-entry-blog.line.me/archives/8676390.html">[LINErntry編集部コラム]TKGP2020を振り返って</a></p>
        <p>2019.11 こどもとIT<a class="aqw" href="https://www.watch.impress.co.jp/kodomo_it/news/1216065.html">小学生プログラマーの裾野広がる、英語とネットを駆使して世界を視野に</a></p>
    </div>

  </div>

</template>

<style>
#about p{
  color: #000000;
}
#profile{
  color: #000000;
  font-family:  "ヒラギノ角ゴ ProN W3", HiraKakuProN-W3, 游ゴシック, "Yu Gothic", メイリオ, Meiryo, Verdana, Helvetica, Arial, sans-serif;
  text-align: left;
  float: left;
  margin: 100px;   /* 外側の余白を40pxにする */
}
#washi{
      display:flex;
}

.about h2 {
  border-bottom: solid 5px skyblue;
  position: relative;
}

.about h2:after {
  position: absolute;
  content: " ";
  display: block;
  border-bottom: solid 5px #FD974F;
  bottom: -5px;
  width: 20%;
}
.aqw{
  color: #FD974F;
}
</style>