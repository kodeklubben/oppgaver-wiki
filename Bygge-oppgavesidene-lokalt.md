<p align="center">
<img border="0" alt="W3Schools" src="https://github.com/kodeklubben/oppgaver-wiki/blob/master/images/kodeklubb-byggeren/node-yarn-logo.png" height="150t">
</p>

# Bygg oppgavesidene på din egen datamaskin

Arbeider du med større oppgaver, kan det ofte være lurt å bygge nettsidene for å
se hvordan oppgaven vil se ut for barna. Det er fort gjort å gjøre en liten feil
når en lager lister, skriver kodeblokker, eller bruker noen av Lær kidsa kodings
egendefinerte titler.

[![Viser localhost, teksteditor, og Lær kidsa koding sin
nettside](https://github.com/Oisov/oppgave/wiki/images/kodeklubb-byggeren/localhost.png "Viser localhost, teksteditor, og Lær kidsa koding sin
nettside")](https://github.com/Oisov/oppgave/wiki/Bygge-oppgavesidene-lokalt/edit)

## Komme i gang

Først må du passe på at du har **node** og **yarn** installert. Det er ulike
måter å gjøre dette på avhengig av om du bruker Mac, Linux eller Windows.

### Installere node på Windows

_Merk:_ Versjonen vi bruker av **node** er `9.8.0`, men dagens versjon er
nyere enn dette. Det er viktig at du bruker versjon `9.8.0` av **node** for å kunne bygge oppgavesidene lokalt på datamaskinen din.

_En måte_ å komme i gang på er å først installere
[nvm-windows](https://github.com/coreybutler/nvm-windows/releases). Last ned
filen `nvm-setup.zip`. Du installerer **nvm** ved å trykke på den når den er
ferdig nedlastet på din maskin. Deretter kan du installere den anbefalte
versjonen av **node** spesifisert i filen
[`.nvmrc`](https://github.com/kodeklubben/codeclub-viewer/blob/master/.nvmrc)
ved å kjøre

    nvm install 9.8.0

i kommandolinjen.

_En annen måte_ er å installere **node** manuelt fra deres egen nettside. Gå
til [nodejs.org](https://nodejs.org/download/release/v9.8.0) og last ned filen
`node-v9.8.0-x64.msi`. Du installerer **node** ved å trykke på filen når den er
ferdig nedlastet på din maskin.

### Installere node på Mac eller Linux

_En måte_ å komme i gang på er å først installere
**nvm**. Skriv

    curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.34.0/install.sh | bash

i kommandolinjen. Deretter kan du installere den anbefalte versjonen av
**node** spesifisert i filen
[`.nvmrc`](https://github.com/kodeklubben/codeclub-viewer/blob/master/.nvmrc)
ved å kjøre

    nvm install 9.8.0

i kommandolinjen.

_En annen måte_ er å installere **node** manuelt fra deres egen nettside. Gå
til [nodejs.org](https://nodejs.org/download/release/v9.8.0) og last ned filen
`node-v9.8.0.pkg`. Du installerer **node** ved å trykke på filen når den er
ferdig nedlastet på din maskin.

### Installere yarn på Windows

Gå til hjemmesiden til
[yarn](https://yarnpkg.com/lang/en/docs/install/#windows-stable). Trykk på
`Download Installer` og følg veiledningen.

### Installere yarn på Mac og Linux

Skriv

    curl -o- -L https://yarnpkg.com/install.sh | bash

i kommandolinjen.

### Komme i gang med LKK-byggeren

Når **node** and **yarn** er installert, bytt til mappen hvor din _fork_ av
oppgave-repoet ligger (ikke _i_ mappen med din fork, men 'ved siden av') og
skriv

```
git clone https://github.com/kodeklubben/codeclub-viewer.git
cd codeclub-viewer
yarn
yarn start
```

i kommandolinjen. Deretter kan du åpne nettsiden på http://localhost:8080.

MERK:

- Dersom du nylig endret versjonen av **node**, og du får en feilmelding under
  `yarn start`, prøv å slette `node_modules`-mappen og kjør
  `yarn` igjen for å installere det på nytt.
- Det er viktig at mappen med din fork av oppgave repoet faktisk heter
  `oppgaver`, ellers så får du en feilmelding `no such file or directory, open`
  og så en sti til `filtertags/keys.yml`.
