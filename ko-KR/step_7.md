## 생일 카드 만들기

그럼 지금까지 배운 HTML과 CSS를 이용하여 자신만의 생일 카드를 만들어 봅시다.

+ [trinket 열기](http://jumpto.cc/web-card){:target="_blank"}.

지금까지 많은 Code를 작성했으나, 생일 카드는 지금까지 꽤 지루해 보였으므로 아래와 같이 HTML 및 CSS 코드를 일부 변경해야 합니다.

+ 카드 앞면의 버튼을 클릭하면 내부가 보이도록 열립니다.

![스크린샷](images/birthday-click.png)

+ HTML Code의 14행으로 이동하여, 자신만의 문구를 쓰세요.

![스크린샷](images/birthday-card-html.png)

+ HTML Code에서 `robot` 이미지를 `sun` 이미지로 바꾸세요.

\--- hints \--- \--- hint \---

+ 17행에 있는 코드를 보세요.
+ `robot`을 `sun`으로 바꾸면, 이미지가 바뀝니다!

![스크린샷](images/birthday-card-sun.png) \--- /hint \--- \--- /hints \---

`boy`, `diamond`, `dinosaur`, `flowers`, `girl`, `rainbow`, `robot`, `spaceship`, `sun`, `tea`, or `trophy` 를 생일 카드에 쓸 수 있으며, or `cracker`, `elf`, `penguin`, `present`, `reindeer`, `santa`, `snowman` 를 크리스마스 카드에 쓸 수 있습니다.

생일 카드의 CSS 코드도 수정해야 합니다.

+ `style.css` 탭을 클릭하여, **outside(바깥쪽)** 스타일을 수정하십시오.

+ `background-color`를 `lightgreen`으로 바꾸세요.

![스크린샷](images/birthday-card-outside.png)

+ 이미지 사이즈도 변경할 수 있는데, `#outside-pic` CSS 코드에서 `width`(너비)와 `height`(높이) 값을 수정하여, 바깥 쪽에 있는 이미지를 `200px`로 수정합니다. (`px`는 픽셀을 의미합니다.)

![스크린샷](images/birthday-card-size.png)

+ 폰트는 `#outside-title` 에서 `font-family`를 수정하면 되는데, `Comic Sans MS` 글씨체로 수정할 수 있으며, `font-size` 를 `16pt`로 수정할 수 있습니다.

![스크린샷](images/birthday-card-font.png)

다른 폰트를 사용하고 싶으시다면 아래와 같이 코드를 작성하시면 됩니다.

+ `<span style="font-family: Arial;">arial</span>`
+ `<span style="font-family: impact;">Impact</span>`
+ `<span style="font-family: tahoma;">Tahoma</span>`