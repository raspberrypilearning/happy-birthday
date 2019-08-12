## Lage et bursdagskort

La oss bruke det du har lært om HTML og CSS for å lage ditt eget tilpassede bursdagskort.

+ Åpne [denne trinketen](https://trinket.io/html/41e51ef0b2){:target="_blank"}.

Vi har skrevet mye kode for å komme i gang, men bursdagskortet ser ganske kjedelig ut så langt, så du skal gjøre noen endringer i HTML- og CSS-koden.

+ Klikk på knappen på forsiden av kortet, og du bør se at det åpner seg for å vise innsiden.

![skjermbilde](images/birthday-click.png)

+ Gå til linje 14 i HTML-koden. Prøv å redigere teksten for å tilpasse kortet ditt.

![skjermbilde](images/birthday-card-html.png)

+ Kan du finne HTML-koden for robot-bildet, og endre ordet `robot` til `sun`?

--- hints ---
 --- hint ---

+ Se på linje 17 for å finne koden.
+ Endre ordet `robot` til `sun`, og du vil se at bildet endres!

![skjermbilde](images/birthday-card-sun.png)
--- /hint ---
--- /hints ---

Du kan bruke et av ordene `boy`, `diamond`, `dinosaur`, `flowers`, `girl`, `rainbow`, `robot`, `spaceship`, `sun`, `tea`, eller `trophy` til et bursdagskort, eller `cracker`, `elf`, `penguin`, `present`, `reindeer`, `santa`, eller `snowman` hvis du foretrekker å lage et julekort.

Du kan også redigere CSS-koden på bursdagskortet.

+ Klikk på fanen for `style.css`. Den første delen er alle CSS-stilene for **utsiden** av kortet.

+ Endre `background-color` (bakgrunnsfarge) til `lightgreen` (lysegrønn).

![skjermbilde](images/birthday-card-outside.png)

+ Du kan også endre størrelsen på et bilde. Gå til `#outside-pic` i CSS-koden, og endre `width` (bredde) og `height` (høyde) på det utvendige bildet til `200px` (`px` står for piksler).

![skjermbilde](images/birthday-card-size.png)

+ Skriften kan også endres. Gå til `#outside-title` CSS og endre `font-family` (skriftfamilie) til `Comic Sans MS` og `font-size` (skriftstørrelse) til `16pt`.

![skjermbilde](images/birthday-card-font.png)

Du kan bruke andre skrifter, for eksempel:

+ `<span style="font-family: Arial;">Arial</span>`
+ `<span style="font-family: impact;">Impact</span>`
+ `<span style="font-family: tahoma;">Tahoma</span>`