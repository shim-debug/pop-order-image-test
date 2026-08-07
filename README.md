# pop-order-image-test

POP用紙オンライン発注システム(pop_order_gas)の商品画像を配信するGitHub Pagesリポジトリです。

従来のGoogle Drive→Base64方式から、GitHub Pages上のHTTPS画像を直接読み込む方式へ
2026-08-07に本番移行しました。本番Webアプリ(Code.gs)はこのリポジトリの
`images/` 配下を以下のURLで参照しています。

```
https://shim-debug.github.io/pop-order-image-test/images/
```

## 画像ファイル命名ルール

`images/` 配下に「商品コード.jpg」の命名規則で配置します(例: `P01.jpg`)。
現在はP01〜P13の13商品分を配置しており、すべて`image/jpeg`であることを確認済みのため、
拡張子は`.jpg`に統一しています。

## 商品追加時の運用手順

新しい商品の画像を追加する場合は、対応する商品コードと同名のJPEGファイルを
`images/` 配下に追加してください(例: 商品コード`P14`なら`P14.jpg`)。
