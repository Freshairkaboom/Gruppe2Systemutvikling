# Prosjektrapport

## Introduksjon


## Team
- Lars A. Strand
- Adrian Johansen
- Bjørn Tore Follegg
- Shaima Nazand
- Monica Johansen
- Ramona Cretulescu
- Christoffer Johansen
### Individuell beskrivelse, gruppemedlems bidrag til prosjektet(legges til på slutten av oppgavetiden)
### Refleksjon over lært/erfart i prosjektet. 


## Foranalyse

### Problembeskrivelse

### Bakgrunn

### Hensikt og mål for prosjektet

### Overordnet kravspesifikasjon

### Interessenter og brukerbeskrivelser

### Funksjonelle krav

### Ikke-funksjonelle krav

### Krav til universell utforming

### Informasjonssikkerhet og personvern


## Analyse

### Aktører og UseCase(UC)

### UC-diagram

### UC-beskrivelser

### Aktivitetsdiagram
Aktivitetsdiagram er et viktig verktøy som brukes i applikasjonsutviklings- prosessen for å få oversikt over hvordan hver aktivitet i applikasjonen fungerer i systemet fra begynnelse til slutt, slik at det er lettere å forstå hva som skjer nå en aktør utfører de forskjellige aktivitetene i use case diagrammene. I denne seksjonen beskrives de forskjellige aktivitetene i HytteApp med tilhørende diagram.

Aktør: Hytteeier
UC1: Registrer bruker
Aktivitetsdiagrammet viser hvordan aktøren hytteeier oppretter en bruker i systemet. Aktiviteten går fra å trykke på "registrer deg" på logg inn siden, som deretter tar deg inn på et skjema der du fyller ut informasjon som navn, epost, telefonnummer og hytteadresse. Når informasjonen er fylt ut, trykker hytteeier på "registrer deg" knappen. Systemet validerer innholdet i skjemaet for å sjekke at innholdet er godkjent. Dersom det ikke er det får hytteeier opp rød skrift på de feltene som må fikses på, og de kan fikse det og trykke på "registrer deg" igjen. Dersom det er godkjent så registreres bruker i databasen, og bruker blir sendt tilbake til logg inn skjermen med en popup melding som sier:  "Brukeren er opprettet, vennligst logg inn".

Figur 1: Aktivitetsdiagram for "registrer bruker" for aktøren Hytteeier.

UC2: Logger inn
Aktivitetsdiagrammet viser hvordan aktøren hytteeier logger inn som bruker av systemet. Aktiviteten går fra å skrive inn brukernavn og passord i feltene på logg inn siden og, deretter trykke på logg inn knappen. Systemet verifiserer da brukeren. Dersom det ikke blir godkjent, nullstilles feltene for brukernavn og passord, og man får en popup melding som sier: "Feil ved innlogging, sjekk brukernavn og passord." Dersom det er godkjent, får brukeren en sesjonskode som gjør at applikasjonen husker at man er logget inn til neste gang, og så blir brukeren tatt til hjem siden.

Figur 2: Aktivitetsdiagram for "logg inn" for aktøren Hytteeier.

UC3: Bestiller brøyting

Aktør: Brøytemannskap
UC1: Får henvendelser på appen om hvilke hytter de skal måke

Aktør: Administrasjon
UC1: Får statistikk fra appen

Aktør: Statens kartverk

Aktør:Systemutviklere

### Flytdiagram

### Datamodell (ER-modell)

### Domenemodell (UML-modell)


## Design

### Systemdesign og klassediagram

### Systemarkitektur og teknologivalg

### Maskinvarespesfikasjon

### Utviklingsverktøy og teknologi

### Konfigurasjon-/versjonskontroll

### Brukergrensesnitt

### Designmål

### Prototype - skjermbilder - Figma


## Kvalitetssikring

### Overordnet testbeskrivelse

### Overordnet testplan

### Prosjektstyring

### Roller/ansvar

### Milepælsplan

### Risikovurdering

### Møtelogg


## Systemutviklingsprosessmodell

### Velge og beskrive prosessmodell/systemutviklingsmodell/metode. Begrunne tilpasninger. Skissere alt.


## Referanser (APA7)




