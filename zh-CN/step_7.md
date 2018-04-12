## 制作一张生日贺卡

让我们使用学到的 HTML 和 CSS 相关知识来制作你自己的定制生日贺卡。

+ 打开 [这个 trinket](http://jumpto.cc/web-card){:target="_blank"}。

我们编写了许多代码来使你们入门，但生日贺卡目前看起来相当无趣，因此你要对 HTML 和 CSS 代码做出一些改动。

+ 点击贺卡封面的按钮，你会看到封面开启，展示出内页。

![screenshot](images/birthday-click.png)

+ 转向 HTML 代码的第 14 行。尝试编辑文本来使你的贺卡个性化。

![screenshot](images/birthday-card-html.png)

+ 你能否找到机器人图片的 HTML 代码，然后把 `robot` 这个词改为 `sun`？

--- hints ---
--- hint ---
+ 请查看第 17 行找到该代码。
+ 将 `robot` 这个词改为 `sun`，你会发现图片随之改变！

![screenshot](images/birthday-card-sun.png)
--- /hint ---
--- /hints ---

你的生日贺卡可使用 `boy`、`diamond`、`dinosaur`、`flowers`、​`girl`、`rainbow`、`robot`、`spaceship`、`sun`、`tea` 或 `trophy` 中的任何一个词，如果你想制作一张圣诞贺卡，你可以使用 `cracker`、`elf`、`penguin`、`present`、`reindeer`、`santa` 或 `snowman`。

你还可以编辑生日贺卡的 CSS 代码。

+ 点击 `style.css` 选项卡。第一部分是贺卡**外部**的所有 CSS 样式。

+ 将 `background-color` 变更为 `lightgreen`。

![screenshot](images/birthday-card-outside.png)

+ 你还可以更改图片的尺寸。转向 `#outside-pic` CSS 代码，将外部图片的 `width` 和 `height` 更改为 `200px`（`px` 指像素）。

![screenshot](images/birthday-card-size.png)

+ 字体也可进行更改。转向 `#outside-title` CSS 并将 `font-family` 更改为 `Comic Sans MS`，`font-size` 更改为 `16pt`。

![screenshot](images/birthday-card-font.png)

你可以使用其他字体，比如：
+ `<span style="font-family: Arial;">arial</span>`
+ `<span style="font-family: impact;">Impact</span>`
+ `<span style="font-family: tahoma;">Tahoma</span>`
