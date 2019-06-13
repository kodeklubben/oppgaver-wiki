
<p align="center">
<img border="0" alt="W3Schools" src="https://github.com/kodeklubben/oppgaver-wiki/blob/master/images/kodeklubb-byggeren/node-yarn-logo.png" height="150t">
</p>


# Bygg oppgavesidene på din egen datamaskin

Arbeider du med større oppgaver, kan det ofte være lurt å bygge nettsidene for å
se hvordan oppgaven vil se ut for barna. Det er fort gjort å gjøre en liten feil
når en lager lister, skriver kodeblokker, eller bruker noen av Lær kidsa kodings
egendefinerte titler.

[![Viser localhost, teksteditor, og Lær kidsa koding sin nettside](https://github.com/Oisov/oppgave/wiki/images/kodeklubb-byggeren/localhost.png "Viser localhost, teksteditor, og Lær kidsa koding sin nettside")](https://github.com/Oisov/oppgave/wiki/Bygge-oppgavesidene-lokalt/_edit)

## Komme i gang

Først må du passe på at du har [node](https://nodejs.org/en/) og
[yarn](https://yarnpkg.com/en/) installert.

### Installere node

En av de enkleste måtene å komme i gang på er å først installere
[nvm](https://github.com/creationix/nvm#installation) eller
[nvm-windows](https://github.com/coreybutler/nvm-windows). Deretter kan du
installere den anbefalte versjonen av node spesifisert i fila `.nvmrc` ved å
kjøre

    nvm install

i kommandolinjen.

### Installere yarn

Installeringen av `yarn` kan være litt vanskeligere, men dersom du følger
instruksjonene på [yarn-hjemmesiden](https://yarnpkg.com/lang/en/docs/install/)
burde det gå fint.

### Komme i gang med LKK-byggeren

Når `node` and `yarn` er installert, bytt til mappen hvor din _fork_ av oppgave
repoet ligger (ikke _i_ mappen med din fork, men 'ved siden av') og skriv 

```
git clone https://github.com/kodeklubben/codeclub-viewer.git
cd codeclub-viewer
yarn
yarn start
```

i kommandolinjen. Deretter kan du åpne nettsiden http://localhost:8080.

[![Bygging av kodeklubbens nettside fra terminalen](https://github.com/Oisov/oppgave/wiki/images/kodeklubb-byggeren/yarn-start.png "Bygging av kodeklubbens nettside fra terminalen")](https://github.com/Oisov/oppgave/wiki/images/kodeklubb-byggeren/yarn-start.png)

MERK: Dersom du nylig endret versjonen av `node`, og du får en feilmelding under
`yarn start` (eller `yarn build`), prøv å slette `node_modules`-mappen og kjør
`yarn` igjen for å installere det på nytt.


## Bygging og tjener

Metoden ovenfor bygger nettsidene hver gang en fil lagres. Ønsker du i stedet å
bygge filene én gang (det er dette som skjer når Lær kidsa koding sin side
legges ut på nettet) kan du kjøre

```
yarn build
yarn serve
```
