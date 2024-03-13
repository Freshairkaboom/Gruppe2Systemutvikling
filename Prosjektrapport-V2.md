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
Aktivitetsdiagram er et viktig verktøy som brukes i applikasjonsutviklings- prosessen for å få oversikt over hvordan hver aktivitet i applikasjonen fungerer i systemet fra begynnelse til slutt, slik at det er lettere å forstå hva som skjer når en aktør utfører de forskjellige aktivitetene i use case diagrammene. I denne seksjonen beskrives de forskjellige aktivitetene i HytteApp med tilhørende diagram.

#### Aktør: Bruker
UC1: Registrer bruker
Aktivitetsdiagrammet viser hvordan aktøren Bruker oppretter en bruker i systemet. Aktiviteten går fra å trykke på "registrer deg" på logg inn siden, som deretter tar deg inn på et skjema der du fyller ut informasjon som navn, epost, telefonnummer og hytteadresse. Når informasjonen er fylt ut, trykker Bruker på "registrer deg" knappen. Systemet validerer innholdet i skjemaet for å sjekke at innholdet er godkjent. Dersom det ikke er det får Bruker opp rød skrift på de feltene som må fikses på, og de kan fikse det og trykke på "registrer deg" igjen. Dersom det er godkjent så registreres bruker i databasen, og bruker blir sendt tilbake til logg inn skjermen med en popup melding som sier: "Brukeren er opprettet, vennligst logg inn".

Figur 1: Aktivitetsdiagram for "registrer bruker" for aktøren Bruker.

UC2: Logger inn

Aktivitetsdiagrammet viser hvordan aktøren Bruker logger inn som bruker av systemet. Aktiviteten går fra å skrive inn brukernavn og passord i feltene på logg inn siden og, deretter trykke på logg inn knappen. Systemet verifiserer da brukeren. Dersom det ikke blir godkjent, nullstilles feltene for brukernavn og passord, og man får en popup melding som sier: "Feil ved innlogging, sjekk brukernavn og passord." Dersom det er godkjent, får brukeren en sesjonskode som gjør at applikasjonen husker at man er logget inn til neste gang, og så blir brukeren tatt til hjem siden.

Figur 2: Aktivitetsdiagram for "logg inn" for aktøren Bruker.

UC3: Bestiller brøyting

Aktivitetsdiagrammet viser hvordan aktøren Bruker bestiller brøyting. Aktiviteten går fra å sjekke om brukeren har en bruker. Hvis ikke, må brukeren registrere bruker. Hvis ja, så sjekker systemet om du har en aktiv sesjon. Hvis ja, så kommer du til hjem siden, og hvis ikke, så må du logge inn og så kommer du til hjem siden. Så kan du trykke på "bestill brøyting" knappen på hjem siden, og så velger du i kalenderen hvilken dato du vil ha brøyting til, og så trykker du på "bestill" knappen som dukker opp. Til slutt kommer brukeren tilbake til hjem siden og får en grønn popup melding som sier "Du har bestilt brøyting til dato: *dato her*". 

Figur 3: Aktivitetsdiagram for "bestill brøyting" for aktøren Bruker.

UC4: Viser værvarsel

Aktivitetsdiagrammet viser hvordan aktøren Bruker viser værvarsel. Aktiviteten går fra å sjekke om brukeren har en bruker. Hvis ikke, må brukeren registrere bruker. Hvis ja, så sjekker systemet om du har en aktiv sesjon. Hvis ja, så kommer du til hjem siden, og hvis ikke, så må du logge inn og så kommer du til hjem siden. Så kan du trykke på "vis værvarsel" knappen på hjem siden, og systemet vil hente værvarsel via API og vise det til brukeren i et nytt vindu. Herfra kan brukeren velge å gå tilbake til hjem siden når de er ferdige å se på værmeldingen.

Figur 4: Aktivitetsdiagram for "vis værvarsel" for aktøren Bruker.

UC5: Sender melding

Aktivitetsdiagrammet viser hvordan aktøren Bruker sender melding. Aktiviteten går fra å sjekke om brukeren har en bruker. Hvis ikke, må brukeren registrere bruker. Hvis ja, så sjekker systemet om du har en aktiv sesjon. Hvis ja, så kommer du til hjem siden, og hvis ikke, så må du logge inn og så kommer du til hjem siden. Så kan du trykke på "kontakt HytteService" knappen på hjem siden, og Bruker blir tatt til en side der man får en tekstboks. Man skriver deretter inn meldingen i tekstboksen, og trykker "Send melding" knappen. Bruker blir da tatt tilbake til hjem siden.

Figur 5: Aktivitetsdiagram for "sender melding" for aktøren Bruker.

UC6: Leser meldinger

Aktivitetsdiagrammet viser hvordan aktøren Bruker sender melding. Aktiviteten går fra å sjekke om brukeren har en bruker. Hvis ikke, må brukeren registrere bruker. Hvis ja, så sjekker systemet om du har en aktiv sesjon. Hvis ja, så kommer du til hjem siden, og hvis ikke, så må du logge inn og så kommer du til hjem siden. Bruker kan deretter trykke på notifikasjoner for å se en liste over mottatte meldinger med tittel, tekst og dato den ble sendt. De kan trykke på et element i listen for å se hele meldingen. Når de har lest meldingen ferdig kan de svare på den, og deretter bli tatt til "send melding" siden, eller gå tilbake til hjem siden.

Figur 6: Aktivitetsdiagram for "leser meldinger" for aktøren Bruker.

#### Aktør: Brøytemannskap
UC1: Får henvendelser på appen om hvilke hytter de skal måke

#### Aktør: Administrasjon
UC1: Får statistikk fra appen

#### Aktør: Statens kartverk

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




