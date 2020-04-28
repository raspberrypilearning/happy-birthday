## Doğum günü kartı yapmak

Hadi şimdi kendi özel doğum günü kartınızı oluşturmak için HTML ve CSS hakkında öğrendiklerinizi kullanalım.

+ [Bu trinketi](https://trinket.io/html/b33e4f4ca8){:target="_blank"} açın.

Başlangıç için birçok kod yazdık, ancak doğum günü kartı oldukça sıkıcı görünüyor, bu nedenle HTML ve CSS kodunda bazı değişiklikler yapacaksınız.

+ Kartın önündeki düğmeye tıkladığınızda, kartın iç kısmının açıldığını görmelisiniz.

![ekran görüntüsü](images/birthday-click.png)

+ HTML kodunun 14. satırına gidin. Kartınızı özelleştirmek için metni düzenlemeyi deneyin.

![ekran görüntüsü](images/birthday-card-html.png)

+ Robot resminin HTML kodunu bulup, `robot` kelimesini `sun` kelimesi ile değiştirebilir misiniz?

\--- hints \--- \--- hint \---

+ Kodu bulmak için 17. satıra bakın.
+ `robot` kelimesini `sun` kelimesi ile değiştirdiğinizde resmin de değiştiğini göreceksiniz!

![ekran görüntüsü](images/birthday-card-sun.png)

\--- /hint \--- \--- /hints \---

Doğum günü kartı yapmak için; `boy`, `diamond`, `dinosaur`, `flowers`, `girl`, `rainbow`, `robot`, `spaceship`, `sun`, `tea`, or `trophy` kelimelerini; Yılbaşı kartı yapmayı dilerseniz de `cracker`, `elf`, `penguin`, `present`, `reindeer`, `santa`, veya `snowman` kelimelerinden herhangi birini kullanabilirsiniz.

Doğum günü kartının CSS kodunu da düzenleyebilirsiniz.

+ `style.css` sekmesine tıklayın. İlk bölüm, kartın **dış** tarafı için CSS stilleridir.

+ `background-color` satırındaki değeri `lightgreen` (açık yeşil) ile değiştirin.

![ekran görüntüsü](images/birthday-card-outside.png)

+ Bir resmin boyutunu da değiştirebilirsiniz. `#outside-pic` CSS koduna gidin ve dış resmin `width` (genişliğini) ve `height` (yüksekliğini) `200px` (`px`, piksel anlamına gelir) olarak değiştirin.

![ekran görüntüsü](images/birthday-card-size.png)

+ Yazı fontu da değiştirilebilir. `#outside-title` CSS koduna gidin ve `font-family` değerini `Comic Sans MS` olarak ve `font-size` (font boyutunu da) `16 pt` olarak değiştirin.

![ekran görüntüsü](images/birthday-card-font.png)

Diğer yazı tiplerini kullanabilirsiniz, örneğin:

+ `<span style="font-family: Arial;">Arial</span>`
+ `<span style="font-family: impact;">Impact</span>`
+ `<span style="font-family: tahoma;">Tahoma</span>`