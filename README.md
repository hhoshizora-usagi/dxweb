# dxweb
DX Web ページの複数パターン集

基本形（合同会社two verse トップページ）をもとにしたカラーバリエーションです。レイアウト・文章は共通で、色だけが違います。

| No. | 配色 | イメージ | ファイル |
|--|--|--|--|
| 00 | エバーグリーン × マスタード | 基本形（元の配色） | [00-evergreen/index.html](00-evergreen/index.html) |
| 01 | ネイビー × ゴールド | 信頼感のあるコーポレート | [01-navy-gold/index.html](01-navy-gold/index.html) |
| 02 | テラコッタ × サンド | あたたかく、やさしい | [02-terracotta/index.html](02-terracotta/index.html) |
| 03 | ラベンダー × ミント | やわらかく、かわいい | [03-lavender-mint/index.html](03-lavender-mint/index.html) |
| 04 | チャコール × オレンジ | モダンで、パキッと目立つ | [04-charcoal-orange/index.html](04-charcoal-orange/index.html) |
| 05 | インディゴ × コーラル | DX・テック感 | [05-indigo-coral/index.html](05-indigo-coral/index.html) |

## しくみ
- `index.html` … 全パターンの一覧ページ
- `assets/style.css` … 全パターン共通のデザイン
- `assets/main.js` … スライドショー・スマホメニュー・ページ上部へ戻るボタンなど
- 各フォルダの `index.html` … 先頭の `:root{ ... }` に色の変数がまとまっています。ここを書きかえると新しい色違いが作れます。

## メモ
- 写真とロゴマークは https://enzineroom.jp/goal/ の画像を読みこんでいます（インターネット接続が必要です）。
- 色の組み合わせは、文字とボタンの読みやすさ（コントラスト）を確認済みです。
