# Vue.js入門

---

## Vue.jsとは

- 2014年にリリースされたJSフレームワーク
- 開発者がデザイナーでデザイナーに理解のあるFW
  - トランジションとか使いやすいらしい
- チュートリアルとか使ってるサイトとか
  - https://github.com/vuejs/awesome-vue

---

## なんでVue.jsがはやってんの？

- 学習コストが低い
- スケールが柔軟
- 多言語ドキュメントが充実してる

---

## そもそもフレームワークとは

- アプリケーションの骨組み
- 開発は部品を作って行くイメージ
- 設計思想が単一なのでコードに統一感がでる

---

## ライブラリなどの紹介

- ライブラリを使うと少ないコードで洗練されたUIが書ける
- どっちもReact、Angularでも使える
- Element
  - http://element.eleme.io
- Onsen UI
  - https://ja.onsen.io/

---

## Hello World

```html
<!DOCTYPE html>
<html>
<body>
    <div id="app">
        <h1>{{ message }}</h1>
    </div>
    <script src="https://cdn.jsdelivr.net/npm/vue"></script>
    <script>
        var app = new Vue({
            el: '#app',
            data: {
                message: 'Hello Vue.js'
            }
        })
    </script>
</body>
</html>
```
@[7]

---

<div style="text-align: center;">
<span style="font-size: 200%;">終</span><br/>
<u>制作・著作</u><br/>
ysmn
</div>
