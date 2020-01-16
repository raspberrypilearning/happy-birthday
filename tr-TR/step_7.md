## Doğum günü kartı yapmak

Kendi özel doğum günü kartınızı oluşturmak için HTML ve CSS hakkında öğrendiklerinizi kullanalım.

+ [Bu trinketi](https://trinket.io/html/b33e4f4ca8){:target="_blank"} açın.

Başlangıç için birçok kod yazdık, ancak doğum günü kartı oldukça sıkıcı görünüyor, bu nedenle HTML ve CSS kodunda bazı değişiklikler yapacaksınız.

+ Kartın önündeki düğmeye tıkladığınızda, kartın iç kısmının açıldığını görmelisiniz.

![ekran görüntüsü](images/birthday-click.png)

+ HTML kodunun 14. satırına gidin. Kartınızı özelleştirmek için metni düzenlemeyi deneyin.

![ekran görüntüsü](images/birthday-card-html.png)

+ Robot resminin HTML kodunu bulup, `robot` kelimesini `güneş` kelimesi ile değiştirebilir misiniz?

\--- hints \--- \--- hint \---

+ Kodu bulmak için 17. satıra bakın.
+ `robot` kelimesini `güneş` kelimesi ile değiştirdiğinizde resmin de değiştiğini göreceksiniz!

![screenshot](images/birthday-card-sun.png)

\--- /hint \--- \--- /hints \---

You can use any of the words `boy`, `diamond`, `dinosaur`, `flowers`, `girl`, `rainbow`, `robot`, `spaceship`, `sun`, `tea`, or `trophy` for a birthday card, or `cracker`, `elf`, `penguin`, `present`, `reindeer`, `santa`, or `snowman` if you would prefer to make a Christmas card.

You can also edit the CSS code of the birthday card.

+ `style.css` sekmesine tıklayın. İlk bölüm, kartın **dış** tarafı için CSS stilleridir.

+ `background-color` satırındaki değeri `lightgreen` (açık yeşil) ile değiştirin.

![ekran görüntüsü](images/birthday-card-outside.png)

+ Bir resmin boyutunu da değiştirebilirsiniz. `#outside-pic` CSS koduna gidin ve dış resmin `width` (genişliğini) ve `height` (yüksekliğini) `200px` (`px`, piksel anlamına gelir) olarak değiştirin.

![ekran görüntüsü](images/birthday-card-size.png)

+ Yazı fontu da değiştirilebilir. `#outside-title` CSS koduna gidin ve `font-family` değerini `Comic Sans MS` olarak ve `font-size` (font boyutunu da) `16 pt` olarak değiştirin.

![screenshot](images/birthday-card-font.png)

You can use other fonts, for example:

+ `<span style="font-family: Arial;">Arial</span>`
+ `<span style="font-family: impact;">Impact</span>`
+ `<span style="font-family: tahoma;">Tahoma</span>`