## Sünnipäevakaardi tegemine

Kasuta seda, mida oled õppinud HTML-i ja CSS-i kohta, et luua sinu enda kohandatud sünnipäevakaart.

+ Ava [see trinket](https://trinket.io/html/b33e4f4ca8){:target="_blank"}.

Oleme kirjutanud palju koodi, et saaksid alustada, kuid sünnipäevakaart tundub siiani üsna igav, seega hakkad sina HTML-i ja CSS-koodi mõnevõrra muutma.

+ Klõpsa kaardi esiküljel asuvat nuppu ja peaksid nägema seda avanemas, et paljastada sisu.

![kuvatõmmis](images/birthday-click.png)

+ Mine HTML-koodi 14. reale. Proovi oma kaardi kohandamiseks teksti redigeerida.

![kuvatõmmis](images/birthday-card-html.png)

+ Kas leiad roboti pildi HTML-koodi ja kas oskad muuta sõna `robot` `päikeseks`?

\--- hints \--- \--- hint \---

+ Koodi leidmiseks vaata rida 17.
+ Muuda sõna `robot` `päikeseks`ja näed, kuidas pilt muutub!

![screenshot](images/birthday-card-sun.png)

\--- /hint \--- \--- /hints \---

You can use any of the words `boy`, `diamond`, `dinosaur`, `flowers`, `girl`, `rainbow`, `robot`, `spaceship`, `sun`, `tea`, or `trophy` for a birthday card, or `cracker`, `elf`, `penguin`, `present`, `reindeer`, `santa`, or `snowman` if you would prefer to make a Christmas card.

You can also edit the CSS code of the birthday card.

+ Vajuta vahelehte `style.css`. Esimene osa on kõik CSS-i stiilid kaardi **välisosa** jaoks.

+ Muuda `taustavärv` `heleroheliseks`.

![kuvatõmmis](images/birthday-card-outside.png)

+ Samuti saad muuta pildi suurust. Mine `#välispildi` CSS-koodini ja muuda pildi välisosa `laius` ja `kõrgus` `200px`-ni (`px` tähistab piksleid).

![kuvatõmmis](images/birthday-card-size.png)

+ Fonti saab ka muuta. Mine `#välispealkirja` CSS-ile ja muuda `fondi perekond` `Comic Sans MS-iks` ja `fondi suurus` `16pt-ks`.

![screenshot](images/birthday-card-font.png)

You can use other fonts, for example:

+ `<span style="font-family: Arial;">arial</span>`
+ `<span style="font-family: impact;">Impact</span>`
+ `<span style="font-family: tahoma;">Tahoma</span>`