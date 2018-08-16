# Hvordan undervise i og vurdere programmering

Her får du noen tips til hvordan du kan motivere elevene dine til å lære
programmering, hvordan du kan undervise på en god måte, og hvordan du kan
vurdere elevene i etterkant.

## Hvorfor programmering i skolen?

Programmering handler i hovedsak om to ting: *modellering* og *koding*. Mange
tenker bare på det siste når de hører ordet programmering. Men det er minst like
viktig å legge vekt på programmeringens krav til planlegging og beskrivelse av
løsning på et problem. Når vi programmerer deler vi opp problemet i mindre
deler, som hver for seg kan løses med en bit kode. Til sammen utgjør
kodesnuttene et program som gjør det vi vil. Vi kan også starte med å jobbe med
mange små problemer, og så sette det sammen til et større program til slutt.

### Valg av programmeringsspråk

Det finnes mange programmeringsspråk å velge mellom. Som lærer står du i en
posisjon hvor du velger hvor elevene skal starte, og du kan legge en plan for
hvor elevene går videre. Under får du noen forslag til rekkefølge på
programmeringsspråk. Disse er valgt ut fra hvor enkelt det er å sette i gang med
(blokkbasert er enklere enn tekstbasert), hvilke oppgaver vi tenker elevene
raskt vil fatte interesse for (ofte mulighet for å lage spill), og hvilke
ressurser som er tilgjengelige. Du bør også ta hensyn til hva du kan eller
kjenner til fra før, og kanskje hvilken kompetanse som er tilgjengelig i
nærmiljøet til din skole.

Dersom skolen din har investert i en bestemt type fysiske enheter, som Arduino,
Micro:bit, Lego Mindstorms, Raspberry Pi eller andre, så vil det være naturlig å
velge denne fremfor andre. Merk at det fins simulatorer på nett, for eksempel
[for Micro:bit](https://makecode.microbit.org/?lang=no), som kan brukes i stedet
for fysiske enheter.

Når elevene begynner å få kjennskap til flere ulike programmeringsspråk kan en
del av oppgaven du gir dem være å velge det språket som passer best for å løse
oppgaven.

#### Forslag til rekkefølge på programmeringsspråk

Mange velger å starte med Scratch som det første programmeringsspråket, mye
fordi det er blokkbasert, og det er tilgjengelig på mange språk (både bokmål og
nynorsk). For en enda mer grunnleggende introduksjon til programmering kan vi
anbefale å starte med CodeStudio, og så gå videre med Scratch og følge en av
rekkefølgene i tabellen under. Merk at Micro:bit kan programmeres både som
blokker og som tekst. Python er et relativt enkelt tekstbasert
programmeringsspråk som åpner mange dører videre til andre språk. Web-språkene
ligner på hverandre, men det er alltid en fordel å forstå grunnleggende
prinsipper i programmering før man går i gang med de tekstbaserte språkene.

<table>
    <thead>
        <tr>
            <th>Språk 1</th>
            <th>Språk 2</th>
            <th>Språk 3</th>
            <th>Språk 4</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td rowspan=5>Scratch</td>
            <td>HTML+CSS</td>
            <td>JavaScript</td>
            <td>Elm</td>
        <tr>
            <td>Micro:bit</td>
            <td>Arduino</td>
            <td></td>
        </tr>
        <tr>

            <td rowspan=3>Python</td>
            <td>Arduino</td>
            <td></td>
        </tr>
        <tr>
            <td>ComputerCraft</td>
            <td></td>
        </tr>
        <tr>
            <td>Processing</td>
            <td></td>
        </tr>
        </tr>
    </tbody>
</table>

## Hvordan undervise i programmering?

Programmering er et praktisk fag som krever at elevene får jobbe på egen hånd.
Du må gi tydelige instruksjoner i starten, la elevene prøve seg frem, og veilede
slik at de kommer videre dersom de står bom fast.

### Samarbeid og deling

Det er sjelden noen som utvikler programvare helt alene. Vi bygger videre på
andres arbeid, og vi gjør vårt eget arbeid tilgjengelig for videreutvikling av
andre. Derfor er det ofte naturlig å la elevene samarbeide i grupper. Du kan for
eksempel begynne med å ha par som jobber sammen hele tiden, og senere la elevene
planlegge sammen, kanskje i litt større grupper, men prøve å kode på egenhånd.

Samarbeid i programmering kan også være å gi tilbakemeldinger på hverandres
arbeid. Elevene kan læres opp til å kommentere egen kode underveis og
dokumentere arbeidsprosessen sin. Andre elever kan lese koden og prøve å forstå
hva den gjør. Oppmuntre elevene til å snakke sammen, stille spørsmål og hjelpe
hverandre!

#### GitHub

En viktig arena for mange som driver med programmering er
[GitHub](https://github.com/). Hvordan du bruker denne plattformen kan du lese
mer om i veiledningen [[Komme-i-gang-med-Git]]. Det finnes funksjoner som lar
deg opprette områder elevene kan bruke for å levere inn eget arbeid som du så
kan vurdere.

### Tips og triks

Bruk tid i starten av hver økt på å gi tydelige instruksjoner. Dette er spesielt
viktig de første gangene. Vis hvordan elevene finner frem til oppgavetekst og
starter programvaren som skal brukes - gjerne gjør stegene sakte og få elevene
til å gjøre dem med deg.

Gi en motiverende innledning til hver oppgave som skal gjøres. Bruker du
oppgavene fra oppgavesamlingen vår kan du ta utgangspunkt i introduksjonen til
oppgaven. Sørg for at elevene forstår hva målet er, og har de verktøyene og
forutsetningene som kreves for å kunne komme dit (med litt veiledning
underveis).

Bruk tid på å snakke med elevene. La dem forklare deg hva de gjør og hvordan de
tenker. Å snakke høyt, tegne og forklare kan hjelpe elevene med prosessen og
forståelsen på en helt annen måte enn om du gir dem løsningen med en gang. Det
kan også hende at de finner en annen like god eller bedre løsning, eller i alle
fall noe som fungerer, som de så kan gå tilbake og justere på senere.

Kodeforståelse er en viktig del av programmeringsfaget. Målet er at elevene skal
bli mer eller mindre selvstendige programmerere, da må de kunne lese og forstå
kode. Det er lett for elevene å spørre "hvorfor fungerer det ikke?" og vente på
svar fra deg. Prøv å få elevene til å lese sin egen kode, sammenligne med
eksempelkode som fungerer og finne feilen selv. Det er ikke mulig å programmere
helt feilfritt, så en selvstendig programmerer må forstå og lære av sine egne
(og andres) feil. Kodeforståelse er spesielt viktig når elevene skal programmere
noe der det ikke finnes en fasit, men de må selv ta valg om hvordan koden skal
utformes for best mulig resultat.

Du kan gjerne bryte opp timen underveis for å diskutere problemstillinger flere
elever har møtt. Kanskje noen hadde en elegant løsning de kan vise for hele
klassen? Pass på å trekke fram løsninger fra flere elever og grupper, ikke
alltid de samme!

## Vurdering av programmering

Det finnes mange måter å vurdere elevenes arbeid i programmering. Du bør ikke
bare vurdere sluttproduktet og om det fungerer, men arbeidsprosessen, løsningene
elevene har valgt og lesbarheten. For eksempel kan en elev ha løst oppgaven på
en veldig elegant måte, men uten kommentarer er det ikke sikkert noen kan lese
koden og enkelt forstå hva som skjer. Eller motsatt: koden kan se kronglete ut,
men eleven kan ha vist mange gode tanker i planleggingsarbeidet sitt likevel.

### Vurderingskriterier

Under er noen forslag til vurderingskriterier du kan bruke. Under hvert spørsmål
står kriteriene rangert fra lavest til høyest måloppnåelse. Tilpass kriteriene
til dine egne behov og din undervisning. Kom gjerne med tilbakemeldinger for å
utvide og forbedre listen!

__Fungerer programmet?__

1. Eleven har laget et program som gjør det minste som kreves for at det skal
  fungere.

2. Eleven har laget et program som fungerer og er relativt brukervennlig.

3. Eleven har laget et program som fungerer som forventet og er brukervennlig.

__Er koden leselig?__

1. Eleven har skrevet kode med korrekt syntaks.

2. Eleven har skrevet kode med korrekt syntaks med tydelig inndeling mellom de
  ulike delene, og noe forklaring.

3. Eleven har skrevet kode med korrekt syntaks og kommentarer som gjør den
  forståelig for en leser.

__Er koden god?__

1. Eleven har skrevet kode som fungerer.

2. Eleven har brukt hensiktsmessige funksjoner og løkker.

3. Eleven behersker innebygde funksjoner og gjør valg av kode men hensyn på
  kjøretid.

__Feilsøking__

1. Eleven kan finne feil i koden ved hjelp av feilmeldinger.

2. Eleven kan finne og rette opp feil i koden ved hjelp av feilmeldinger.

3. Eleven kan lese og forstå koden, samt finne og rette opp feil.

## Flere ressurser

Dersom du skal undervise programmering over en lengre periode, og spesielt om du
skal undervise i valgfag programmering, anbefaler vi å lese [Udir sin
veiledning](https://www.udir.no/laring-og-trivsel/lareplanverket/veiledning-lp/valgfag-programmering/)
til valgfag programmering.

I 2014 skrev Espen Clausen [et
blogginnlegg](https://espenec.wordpress.com/2014/10/07/hvorfor-skal-vi-bruke-programmering-i-skolen/)
om programmering i skolen, der han skriver hvorfor vi skal drive med
programmering i skolen. Videre gir han noen forslag til hvordan det kan
gjennomføres enkle kodeprosjekter i grunnskolen. Andre innlegg på bloggen hans
tar for seg programmering i skolen, både andre programmeringsspråk og ulike
erfaringer.
