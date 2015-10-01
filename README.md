# README
## 環境構築
 - rbenv: 0.4.0
 - ruby: ruby 2.1.2p95
 - rails: 2.0.0-p481
 - Node: v0.10.35
 - Bower: 1.5.2
 - 使用テンプレート: middleman-blog-bootstrap-template

 [環境構築方法](http://qiita.com/5t111111/items/7a7600b463256f1d4122)

## ブログ作成

### サーバー起動

```
bundle exec middleman
```

http://localhost:4567/
に接続すれば確認できます。

###  記事作成

```
bundle exec middle article "title"
```

### デプロイ

```
git checkout gh-pages
bundle exec middleman build
bundle exec middleman deploy
```
