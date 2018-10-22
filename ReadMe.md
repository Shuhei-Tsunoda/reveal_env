# Reveal env

このリポジトリは、
[reveal.js](https://github.com/hakimel/reveal.js)を使ってスライドを作るためのひな型です。

## 必須

下記のソフトウェアをインストールしてください。

- [Node.js](https://nodejs.org/ja/)
- [Yarn](https://yarnpkg.com/lang/ja/)


## インストール方法

このリポジトリのディレクトリで`$ yarn install`を実行してください。

## 使い方

### スライドの編集

`./slides.md`を編集してください。

### プレゼンテーションの開始

`$ yarn run start`を実行してください。

### PDFへ出力

`$ yarn run export`を実行してください。
`./dist/slides.pdf`が作られます。

### プレゼンテーションの操作

- スライド移動: 矢印キー
- スライド全体を見る: Esc
- フルスクリーンモード: F（解除はEsc）
- 発表者モード用ウィンドウを出す: S
- ズーム: Alt + クリック
