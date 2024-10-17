# bookmarklet-development-template

ブックマークレットを開発する時の雛形です。

This is a template for developing bookmarklets.

## 概要

このプロジェクトは、ブックマークレットを簡単に開発するためのテンプレートです。
Google Closure Compiler を使用して、JavaScript コードを圧縮し、ブックマークレットとして使用できる形式に変換します。

This project is a template for easy development of bookmarklets.
It uses Google Closure Compiler to compress and convert JavaScript code into a format that can be used as a bookmarklet.

## ファイル構成

```
.
├── README.md
├── dist
│ └── bookmarklet.js
├── node_modules
├── package-lock.json
├── package.json
└── src
    └── main.js
```

## 使用方法

### 依存関係のインストール

まず、プロジェクトの依存関係をインストールします。

First, install the project dependencies.

```sh
npm install
```

### コードを書く
`src/main.js`にブックマークレットに変換したいJavaScriptのコードを書きます。

Write the JavaScript code you want to convert to a bookmarklet in `src/main.js`.

### ビルド

次に、ビルドスクリプトを実行してブックマークレットを生成します。

Next, run the build script to generate the bookmarklet.

```sh
npm run build
```

ビルドが成功すると、`dist/bookmarklet.js`にブックマークレットが生成されます。

If the build is successful, a bookmarklet will be generated in `dist/bookmarklet.js`.

ブックマークレットの使用
生成された`dist/bookmarklet.js`の内容をコピーし、ブラウザのブックマークに貼り付けて使用します。

Using the bookmarklet
Copy the contents of the generated `dist/bookmarklet.js` and paste it into your browser's bookmarklet.
