## Sünnipäevakaardi tegemine

Kasuta seda, mida oled õppinud HTML-i ja CSS-i kohta, et luua sinu enda kohandatud sünnipäevakaart.

+ Ava [see trinket](http://jumpto.cc/web-card){:target="_blank"}.

Oleme kirjutanud palju koodi, et saaksid alustada, kuid sünnipäevakaart tundub siiani üsna igav, seega hakkad sina HTML-i ja CSS-koodi mõnevõrra muutma.

+ Klõpsa kaardi esiküljel asuvat nuppu ja peaksid nägema seda avanemas, et paljastada sisu.

![kuvatõmmis](images/birthday-click.png)

+ Mine HTML-koodi 14. reale. Proovi oma kaardi kohandamiseks teksti redigeerida.

![kuvatõmmis](images/birthday-card-html.png)

+ Kas leiad roboti pildi HTML-koodi ja kas oskad muuta sõna `robot` `päikeseks`?

\--- hints \--- \--- hint \---

+ Koodi leidmiseks vaata rida 17.
+ Muuda sõna `robot` `päikeseks`ja näed, kuidas pilt muutub!

![kuvatõmmis](images/birthday-card-sun.png) \--- /hint \--- \--- hints \---

Võid kasutada ükskõik millist järgnevatest sõnadest `poiss`, `teemant`, `dinosaurus`, `lilled`, `tüdruk`, `vikerkaar`, `robot`, `kosmoselaev`, `päike`, `tee` või `trofee` sünnipäevakaardi jaoks või `paukrakett`, `päkapikk`, `pingviin`, `kingitus`, `põhjapõder`, `jõuluvana` või `lumememm`, kui eelistaksid teha jõulukaarti.

Samuti saad muuta sünnipäevakaardi CSS-koodi.

+ Vajuta vahelehte `style.css`. Esimene osa on kõik CSS-i stiilid kaardi **välisosa** jaoks.

+ Muuda `taustavärv` `heleroheliseks`.

![kuvatõmmis](images/birthday-card-outside.png)

+ Samuti saad muuta pildi suurust. Mine `#välispilt` CSS-koodini ja muuda pildi välisosa `laius` ja `kõrgus` `200px`-ni (`px` tähistab piksleid).

![kuvatõmmis](images/birthday-card-size.png)

+ Font saab muuta ka. Minge `# out-title` CSS-ile ja muutke `font-perekonna` kuni `Comic Sans MS` ja `font-suurust` kuni `16pt`.

![ekraanipilt](images/birthday-card-font.png)

Võite kasutada ka teisi fonte, näiteks:

+ `<span style="font-family: Arial;">arial</span>`
+ `<span style="font-family: impact;">Mõju</span>`
+ `<span style="font-family: tahoma;">Tahoma</span>`