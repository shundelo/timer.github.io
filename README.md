# timer.github.io
<!DOCTYPE html>
<html lang="ja">
  <head>
    <meta charset="UTF-8">
    <title>Myタイマー</title>
    <script src="script.js" defer></script>
    <link rel="stylesheet" href="style.css">
  </head>

  <body>
    <h1>This is my Timer！</h1>

    <!-- この中にタイマーを書いていきます。 -->
    <div id="timerApp">
      <!-- タイマーの時間を表示する場所
           具体的な中身は、後からJSで生成していく -->
      <p id="timerString"></p>

      <!-- タイマーをスタート/ストップ/リセット
            するボタンを置く場所 -->
      <div id="timerButton">
        <!-- onClick=" ~~~ "と言うところで、
              ボタンを押したときに呼ばれる関数を指定する -->
        <input type="button" value="スタート" onClick="OnStartButtonClick();">
        <input type="button" value="ストップ" onClick="OnStopButtonClick();">
        <input type="button" value="リセット" onClick="OnResetButtonClick();">
      </div>
    </div>

  </body>
</html>
