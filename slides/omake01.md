### 開発用ウェブサーバーを使う理由
ひとつのブラウザーでしか使わない場合でも使ったほうがいい

* file:/// スキームだと動かない HTML5 API がある
  - `//example.com/foo.min.js` もできない
* URL のパースの時によく失敗する
* HTTPS じゃないと動かないものでも使える
  - `--https` を追加してください
