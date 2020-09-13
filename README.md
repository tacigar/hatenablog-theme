### Hatena Blog Theme

シンプルなはてなブログ用のテーマです。

### 使い方

GoogleフォントとFont Awesome使ってるので、**ヘッダのタイトル下**に以下を挿入する。

```html
<link href="https://fonts.googleapis.com/css2?family=Kosugi+Maru&display=swap" rel="stylesheet">
<link href="https://use.fontawesome.com/releases/v5.6.1/css/all.css" rel="stylesheet">
```

`npm run build` して生成された `build/main.css` の中身をコピーして**デザインCSS**にそのまま貼り付ける。

### 開発時

開発中はいちいちビルドして貼り付けるの面倒臭いので、代わりに**デザインCSS**に以下を書き込んで、`npm start` する。

```css
@import "http://localhost:3000/main.css"
```
