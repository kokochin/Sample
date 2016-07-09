coding_rule
===


# 共通
- Encoding: UTF-8
- インデント: 空白4個
- リテラルはダブルクォーテーション(")を使用する。
- 命名にはスネーク記法を使用。(2単語以上になる場合に"_"を使用する)
    - 良い例 header, menu_page
    - 悪い例 Header, menuPage

# html
- 要素: 小文字
- イコール(=)の隣: 空白なし `<meta charset="UTF-8">`
- 改行: 一行なら無し、複数行の場合は改行
- できるだけclassよりもidを多用する
- スタイル: できるだけhtmlには書かず、cssに記述する
    - 良い例 `<div style="font-size: 12px">`
    - 悪い例 `<div id="section">`
- 属性間はスペースを開ける  
    - 良い例 `<link rel="stylesheet" type="text/css" href="./stylesheets/stylesheet.css">`
    - 悪い例 `<link rel="stylesheet"type="text/css"href="./stylesheets/stylesheet.css">`

# css
- {}の前には空白を一つ入れる  
    - 良い例
        ```
            body {
            }
        ```  
    - 悪い例
        ```
            body{
            }
        ```
- :の後に空白を1つ開ける  
    - 良い例: `font-size: 12px;`  
    - 悪い例: `font-size:12px;`
- 上から、要素、ID、クラス
  コメントで区切る。
- サイズの単位: PC版はpx、スマホ版はem

# javascript
- min.jsは編集してはいけない。
- function()の後ろに空白を入れる

    - 良い例
    ```
    function() {
    }
    ```

    - 悪い例
    ```
    function(){
    }
    ```

- if-elseの書き方は以下に従う

    ```
    if () {
    } else {
    }
    ```

- 演算子の隣には空白を入れる

    - 良い例
    ```
    if (a == b) {
    }
    ```

    - 悪い例
    ```
    if (a==b) {
    }
    ```

