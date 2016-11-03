### Live reload

カレントディレクトリの全てのファイルの変更を監視
```html
$ browser-sync start --server --files .
```

html/css/js だけの変更を監視
```html
$ browser-sync start --server --files "**/*.html, **/*.css, **/*.js"
```

変更した瞬間、ブラウザーが自動でリロードされます!
