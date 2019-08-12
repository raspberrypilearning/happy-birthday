## Doğum günü kartı yapmak

Kendi özel doğum günü kartınızı oluşturmak için HTML ve CSS hakkında öğrendiklerinizi kullanalım.

+ [Bu trinketi](https://trinket.io/html/b33e4f4ca8){:target="_blank"} açın.

Başlangıç için birçok kod yazdık, ancak doğum günü kartı oldukça sıkıcı görünüyor, bu nedenle HTML ve CSS kodunda bazı değişiklikler yapacaksınız.

+ Kartın önündeki düğmeye tıkladığınızda, kartın iç kısmının açıldığını görmelisiniz.

![ekran görüntüsü](images/birthday-click.png)

+ HTML kodunun 14. satırına gidin. Kartınızı özelleştirmek için metni düzenlemeyi deneyin.

![ekran görüntüsü](images/birthday-card-html.png)

+ Robot resminin HTML kodunu bulup ve `robot` kelimesini `güneş` kelimesi ile değiştirebilir misiniz?

\--- hints \--- \--- hint \---

+ Kodu bulmak için 17. satıra bakın.
+ `robot` kelimesini `güneş` kelimesi ile değiştirdiğinizde resmin değiştiğini göreceksiniz!

![ekran görüntüsü](images/birthday-card-sun.png) \--- /hint \--- \--- /hints \---

`çocuk`, `elmas`, `dinozor`, `çiçek`, `kız`, `gökkuşağı`, `robot`, `uzay gemisi`, `güneş`, `çay`veya `ödül kelimesinden herhangi birini kullanabilirsiniz. Bir doğum günü kartı için` ya da `kraker`, `elf`, `penguen`, `mevcut`, `ren geyiği`, `santa`veya `kardan adam` Noel kartı yapmayı tercih ederseniz.

Doğum günü kartının CSS kodunu da düzenleyebilirsiniz.

+ `style.css` sekmesine tıklayın. İlk bölüm, kartın **dış** tarafı için CSS stilleridir.

+ `background-color`'u `lightgreen` (açık yeşil) ile değiştirin.

![ekran görüntüsü](images/birthday-card-outside.png)

+ Bir resmin boyutunu da değiştirebilirsiniz. `#dis-resim` CSS koduna gidin ve dış resmin `width` (genişliğini) ve `height` (yüksekliğini) `200px` (`piksel`, anlamına gelir) olarak değiştirin.

![ekran görüntüsü](images/birthday-card-size.png)

+ Yazı fontu da değiştirilebilir. `#dis-baslik` CSS koduna gidin ve `font-family`'i `Comic Sans MS` ve `font-size` (font boyutunu) `16 pt` olarak değiştirin.

![ekran görüntüsü](images/birthday-card-font.png)

Diğer yazı tiplerini kullanabilirsiniz, örneğin:

+ `<span style="font-family: Arial;">Arial</span>`
+ `<span style="font-family: impact;">Etki</span>`
+ `<span style="font-family: tahoma;">Tahoma</span>`