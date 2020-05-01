## バースデーカードをつくる

HTMLとCSSについて学んできたことを利用して、独自のバースデーカードをつくってみましょう。

+ [このtrinket](https://trinket.io/html/b33e4f4ca8){:target="_blank"}を開きます。

みなさんがはじめられるようにたくさんのコードを書きましたが、これまでのバースデーカードはかなり退屈なので、HTMLコードとCSSコードを少し変更します。

+ カードの前面にあるボタンを押すと、中が見えるようにカードが開くはずです。

![スクリーンショット](images/birthday-click.png)

+ HTMLコードの14行目に移動します。文字列を編集してカードを変更してみましょう。

![スクリーンショット](images/birthday-card-html.png)

+ ロボット画像のHTMLコードを見つけて、`robot`という単語を`sun`に変更できますか？

\--- hints \--- \--- hint \---

+ コードを見つけるために17行目を見てください。
+ `robot`という単語を`sun`に変更してください。画像が変わるのがわかります！

![スクリーンショット](images/birthday-card-sun.png)

\--- /hint \--- \--- /hints \---

You can use any of the words `boy`, `diamond`, `dinosaur`, `flowers`, `girl`, `rainbow`, `robot`, `spaceship`, `sun`, `tea`, or `trophy` for a birthday card, or `cracker`, `elf`, `penguin`, `present`, `reindeer`, `santa`, or `snowman` if you would prefer to make a Christmas card.

You can also edit the CSS code of the birthday card.

+ Click on the tab for `style.css`. The first part is all of the CSS styles for the **outside** of the card.

+ Change the `background-color` to `lightgreen`.

![screenshot](images/birthday-card-outside.png)

+ You can also change the size of an image. Go to the `#outside-pic` CSS code, and change the `width` and `height` of the outside image to `200px` (`px` stands for pixels).

![screenshot](images/birthday-card-size.png)

+ The font can be changed too. Go to the `#outside-title` CSS and change the `font-family` to `Comic Sans MS` and the `font-size` to `16pt`.

![screenshot](images/birthday-card-font.png)

You can use other fonts, for example:

+ `<span style="font-family: Arial;">arial</span>`
+ `<span style="font-family: impact;">Impact</span>`
+ `<span style="font-family: tahoma;">Tahoma</span>`