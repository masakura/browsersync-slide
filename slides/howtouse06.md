### プロキシ + ローカルファイル

事前に CSS ファイルをダウンロードしておいて...

```
$ mkdir -p css
$ wget -O css/style.css http://www.aratana.jp/css/style.css

$ browser-sync start --proxy http://www.aratana.jp/ --serveStatic . --files .
```

* お客さんのウェブサイトの CSS をいじるときに
* API サーバーと SPA を別々に実行するときに (CORS 対策)
