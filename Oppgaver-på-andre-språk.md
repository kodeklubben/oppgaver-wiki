

# Oppgaver på andre språk

Oppgavesidene er satt opp slik at de kan brukes på flere språk. Det er krav til
alle læremidler i norsk skole at de skal være tilgjengelige på både bokmål og
nynorsk, dessuten er det flere oppgaver der vi har tatt utgangspunkt i en
engelsk versjon. Videre kan sidene utvides til ethvert språk, men det er noen
ting som må på plass først.

## Kodeklubben/oppgaver

På oppgavesidene er det mulig å filtrere oppgaver etter gitte kriterier. Dette
filteret følger språkvalget som er gjort, og må være oversatt til det aktuelle
språket. Lag en ny
[filtertags](https://github.com/kodeklubben/oppgaver/blob/master/filtertags/translation_nb.yml)-fil
med oversettelser. I [[Den gode oppgaven|Den-gode-oppgaven]] finner du
forklaringer for hvordan de ulike taggene brukes. Gi filen navnet
`translation_nb.yml`, der `nb` byttes ut med [ISO
639-1-koden](https://en.wikipedia.org/wiki/List_of_ISO_639-1_codes) for det
aktuelle språket.

I filen
[keys.yml](https://github.com/kodeklubben/oppgaver/blob/master/filtertags/keys.yml)
må du legge til den samme språkkoden som over for at brukeren skal kunne
filtrere oppgaver på riktig språk.

## CodeClub-viewer

Brukergrensesnittet må også oversettes, slik at brukeren får bruke nettsiden på
riktig språk. Du må begynne med å lage en _fork_ av [CodeClub-viewer]() på samme
måte som du laget for [[oppgave-repoet|Komme-i-gang-med-Git]].

Så må du oversette [filen med
brukergrensesnittet](https://github.com/kodeklubben/codeclub-viewer/blob/master/src/constants/captions_nb.js)
til det aktuelle språket. Lagre filen som `captions_nb.js`, der `nb` byttes ut
med ISO 639-1-koden.

Til slutt må du laste opp et flagg (i svg-format) som symboliserer språket i
[denne
mappen](https://github.com/kodeklubben/codeclub-viewer/tree/master/src/assets/graphics),
med filnavnet `flag_nb.svg`. Igjen må `nb` byttes ut med riktig ISO 639-1-kode.
Pass på at bildefilen er lisensiert for bruk på Lær Kidsa Koding sine nettsider.

## Oppsummering

For å starte opp et nytt språk må du minst gjøre følgende:

- Oversette
  [filtertags](https://github.com/kodeklubben/oppgaver/blob/master/filtertags/translation_nb.yml).

- Legge til språket i
  [keys](https://github.com/kodeklubben/oppgaver/blob/master/filtertags/keys.yml).

- Oversette
  [captions](https://github.com/kodeklubben/codeclub-viewer/blob/master/src/constants/captions_nb.js).

- Laste opp flagg
  [her](https://github.com/kodeklubben/codeclub-viewer/tree/master/src/assets/graphics).
