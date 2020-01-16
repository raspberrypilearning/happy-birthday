## Lage et bursdagskort

La oss bruke det du har lært om HTML og CSS for å lage ditt eget tilpassede bursdagskort.

+ Åpne [denne trinketen](https://trinket.io/html/b33e4f4ca8){:target="_blank"}.

Vi har skrevet mye kode for å komme i gang, men bursdagskortet ser ganske kjedelig ut så langt, så du skal gjøre noen endringer i HTML- og CSS-koden.

+ Klikk på knappen på forsiden av kortet, og du bør se at det åpner seg for å vise innsiden.

![skjermbilde](images/birthday-click.png)

+ Gå til linje 14 i HTML-koden. Prøv å redigere teksten for å tilpasse kortet ditt.

![skjermbilde](images/birthday-card-html.png)

+ Kan du finne HTML-koden for robot-bildet, og endre ordet `robot` til `sun`?

\--- hints \--- \--- hint \---

+ Se på linje 17 for å finne koden.
+ Endre ordet `robot` til `sun`, og du vil se at bildet endres!

![screenshot](images/birthday-card-sun.png)

\--- /hint \--- \--- /hints \---

You can use any of the words `boy`, `diamond`, `dinosaur`, `flowers`, `girl`, `rainbow`, `robot`, `spaceship`, `sun`, `tea`, or `trophy` for a birthday card, or `cracker`, `elf`, `penguin`, `present`, `reindeer`, `santa`, or `snowman` if you would prefer to make a Christmas card.

You can also edit the CSS code of the birthday card.

+ Klikk på fanen for `style.css`. Den første delen er alle CSS-stilene for **utsiden** av kortet.

+ Endre `background-color` (bakgrunnsfarge) til `lightgreen` (lysegrønn).

![skjermbilde](images/birthday-card-outside.png)

+ Du kan også endre størrelsen på et bilde. Gå til `#outside-pic` i CSS-koden, og endre `width` (bredde) og `height` (høyde) på det utvendige bildet til `200px` (`px` står for piksler).

![skjermbilde](images/birthday-card-size.png)

+ Skriften kan også endres. Gå til `#outside-title` CSS og endre `font-family` (skriftfamilie) til `Comic Sans MS` og `font-size` (skriftstørrelse) til `16pt`.

![screenshot](images/birthday-card-font.png)

You can use other fonts, for example:

+ `<span style="font-family: Arial;">arial</span>`
+ `<span style="font-family: impact;">Impact</span>`
+ `<span style="font-family: tahoma;">Tahoma</span>`