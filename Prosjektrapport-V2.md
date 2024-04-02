# Prosjektrapport

## Introduksjon

## Team

- Lars A. Strand
- Adrian Johansen
- Bjørn Tore Follegg
- Shaima Nazand
- Monica Azaria Johansen
- Ramona Cretulescu
- Christoffer Johansen

### Individuell beskrivelse, gruppemedlems bidrag til prosjektet(legges til på slutten av oppgavetiden)

### Refleksjon over lært/erfart i prosjektet.

## Foranalyse

### Problembeskrivelse

Hytteservice står overfor utfordringer knyttet til ineffektivitet og unødvendige kostnader i forbindelse med brøyting av hytteområder. Uten en nøyaktig oversikt over hytter som er i bruk, må alle områder brøytes ved snøfall, noe som fører til økte kostnader, tidssløsing og unødvendig slitasje på utstyr. Det mangler også en effektiv måte å kommunisere med hytteeiere og planlegge brøyteaktiviteter.

### Bakgrunn

Hytteservice har lenge levert tjenester til hytteeiere over hele landet, men med vinterhalvåret kommer spesifikke utfordringer knyttet til brøyting av veier og områder rundt hyttene. Den nåværende praksisen med å brøyte basert på estimater og generell kunnskap om hyttebruk har vist seg å være ineffektiv og kostbar. Nå skal det automatiseres og digitaliseres for å tilby en bedre løsning enn det de har.

### Hensikt og mål for prosjektet

Gjennom utviklingen av HytteApp ønsker Hytteservice å modernisere sin tilnærming til brøytingstjenester, samtidig som de opprettholder sitt omdømme for kvalitet og pålitelighet i markedet.

Formålet med prosjektet er å utvikle en mobilapplikasjon, HytteApp, som effektiviserer og forbedrer brøyteprosessen for Hytteservice og hytteeierne. Målene inkluderer:

Å redusere kostnader ved unødvendig brøyting og slitasje på utstyr.
Å utvikle en funksjonell og brukervennlig HytteApp.
Å forbedre kundeopplevelsen for hytteeiere gjennom en enkel og pålitelig bestillingsprosess.
Å øke effektiviteten til Hytteservice gjennom bedre ressursallokering og planlegging av brøyteoppdrag.
Å sikre at løsningen oppfyller personvernkravene, spesielt GDPR, og har universell utforming for tilgjengelighet.

### Overordnet kravspesifikasjon

I tillegg til å beskrive produktets funksjoner og operasjonelle egenskaper, spiller kravspesifikasjonen også en sentral rolle i å definere produktets mål og formål. Den gir et klart rammeverk for utviklingsteamet og bidrar til å sikre at alle interessenter har en felles forståelse av hva produktet skal oppnå. Videre fungerer kravspesifikasjonen som et viktig verktøy for kommunikasjon mellom ulike teammedlemmer.

I tillegg til å tilrettelegge for kommunikasjon og forståelse, hjelper kravspesifikasjonen også med å håndtere risikoer knyttet til produktutviklingen. Ved å identifisere og dokumentere kravene tydelig, kan mulige utfordringer og feil oppdages og løses tidlig i prosessen. Dette bidrar til å minimere risikoen for kostbare omgjøringer senere i utviklingsfasen.

I en stadig skiftende teknologisk verden er det viktig å kunne tilpasse seg endringer raskt. Ved å være fleksible i kravspesifikasjonen kan utviklingsteamet bedre håndtere utfordringer og muligheter, øke sjansene for suksess og levere et produkt som tilfredsstiller kundens behov.

### Interessenter og brukerbeskrivelser

### Funksjonelle krav

- Registering og innlogging for hytteeiere
- Mulighet for å bestille brøyting
- Varslingssytem via SMS når brøyting er fullført
- Integrasjon mot Statens Kartverk for å hente hytteadresser

- Funksjonelle krav (brukerregistrering, bestilling, motta sms, værvarsel, administrasjon)

### Ikke-funksjonelle krav

#### Sikkerhet og personvern:

Appen må overholde GDPR-krav og andre relevante lover og forskrifter angående personvern. Dette inkluderer sikker lagring og håndtering av brukerdata, samt kryptering av sensitiv informasjon under overføring.

#### Universell utforming (UU):

Appen må være tilgjengelig og brukervennlig for alle, uavhengig av eventuelle funksjonshemminger eller teknisk kunnskap. Dette inkluderer tilpasninger for syns-, hørsels- og motoriske utfordringer.

#### Ytelse og skalerbarhet:

Appen må kunne håndtere et stort antall brukere samtidig uten at det går på bekostning av ytelsen. Videre må den være skalerbar for å kunne tilpasse seg økende brukerbase og funksjonalitetsbehov over tid.

#### Pålitelighet og tilgjengelighet:

Appen må være stabil og pålitelig, med minimal nedetid og feilhåndtering. Videre må den være tilgjengelig på ulike plattformer og enheter, inkludert mobile enheter og nettlesere.

#### Brukervennlighet og responsivt design:

Appen må ha et intuitivt og responsivt grensesnitt som er enkelt å navigere og forstå for brukerne. Den må også tilpasses forskjellige skjermstørrelser og enheter for optimal brukeropplevelse.

#### Teknologisk plattform:

Valg av teknologisk plattform må være godt dokumentert og begrunnet, med fokus på sikkerhet, fleksibilitet og vedlikeholdbarhet over tid.

#### Teknisk dokumentasjon:

Det må være tilstrekkelig teknisk dokumentasjon og brukerveiledninger tilgjengelig for å hjelpe både utviklere og brukere med å forstå og bruke appen effektivt.

### Universell utforming

I forhold til utvikling av HytteApp er det en del spørsmål som må stilles i forhold til hvorvidt vi skal ta hensyn til spesielle brukerbehov, eller om vi holder oss til etablerte standarder. Vi må svare på om vi overholder Web Content Accessibility Guidelines 2.1 (World Wide Web Consortium, 2018) og likestillings- og diskrimineringsloven (Lovdata, 2017), og om designet vårt kan sies å være inkluderende.

For å godkjenne design bør designere vise til hvordan de har tatt hensyn til UU i produktet, hvilke hensyn og virkemidler som er brukt i forhold til etablerte standarder, og hvilke nye hensyn som er tatt. Deretter må de som godkjenner designene gå over om det som er tatt hensyn til og implementert i designet er nok til å overholde WCAG og likestillings- og diskrimineringsloven. I designfasen, spesifikt i etterkant av prototyping, kan det være hjelpsomt å involvere testgrupper for å se på om de forskjellige hensynene faktisk fungerer.

Det er viktig å dokumentere ikke bare alle hensyn som tas, men også hvilke hensyn som ennå ikke er tatt. Dette kan gjøres ved hjelp av å inkludere en tilgjengelighetserklæring i applikasjonen. En slik erklæring er et verktøy som viser til hvorvidt applikasjonen er i samsvar med UU, og lister opp alle bruddene på UU, hvilke brukergrupper som blir påvirket av bruddene, samt en måte for brukere å melde fra om brudd og sende klage til diskrimineringsnemda. I erklæringen kan man også legge ut om hvorfor ikke alle standardene er fulgt, hva som gjøres med det, og evt. hvor lang tid det vil ta før bruddene fikses. Et godt eksempel på en slik erklæring er på USN sin egen nettside (Universitetet i Sørøst-Norge, 2024), se referanse for link.

## Analyse

### Aktører og UseCase(UC)

### UC-diagram

### UC-beskrivelser

### Aktivitetsdiagram

Figur 1: Aktivitetsdiagram over brøyting

I diagrammet over så starter det med login / bruker registrering. Hvis man har en bruker så blir man sendt til login siden hvor man kan input data som blir sendt til validering. Om dette blir godkjent så blir man videresendt til hjemmesiden / appen. Hvis man ikke har en bruker så må man fylle ut data som deretter blir sendt for validering, om dette stemmer blir man sendt til login side, og hvis det ikke stemmer så får man en feilmelding og blir sendt tilbake.

Etter man har kommet seg inn på siden / appen så velger man brøyting hvor bruker får muligheten til å velge hytte. Om brukeren har en hytte lagret så kan brukeren velge den og fortsette. Om brukeren ikke har en hytte så må man registrere en adresse som blir sjekket om er riktig eller ikke. Etter at brukeren har valgt en adresse så kan han bestille brøyting. Brukeren kan også velge om han vil legge inn telefonnummer for en SMS når brøytingen er ferdig, men dette er ikke et krav

Figur 2: Aktivitetsdiagram over værvarsel

I dette aktivitetsdiagrammet kan man se værvarselet ut fra den adressen man har valgt. Om brukeren har en adresse så blir man sendt siden der værvarselet vises. Hvis brukeren ikke har en adresse så kan man registrere en adresse som blir sendt til validering. Om den blir godkjent blir bruker send til adresse valg hvor man kan velge sin adresse for å se værvarselet. Hvis ikke så kommer det opp en feilmelding og brukeren kan prøve på nytt.

Figur 3: Aktivitetsdiagram over kontaktskjema

I dette aktivitetsdiagrammet så er brukeren inne på kontaktsiden, her kan brukeren kontakte bedriften / brøytemannskapet. Bruker får et utfyllingsskjema som blir sendt til bedriften. Om det kommer en feilmelding så blir brukeren bedt om å prøve på ny eller brukeren kan avslutte oppgaven.

### Datamodell (ER-modell)

### Domenemodell (UML-modell)
- En domenemodell er et forenklet kart over et spesifikt område, for eksempel et programvaresystem eller en bedrift. Den viser de viktige tingene og hvordan de er knyttet til hverandre. Dette gjør det lettere for alle parter å forstå hva systemet gjør og hvordan det fungerer. 
Den viser de viktige entitetene og hvordan de er knyttet til hverandre

## Design

### Systemdesign og klassediagram

### Systemarkitektur og teknologivalg

### Maskinvarespesfikasjon

### Utviklingsverktøy og teknologi

### Konfigurasjon-/versjonskontroll

### Brukergrensesnitt
## De beste brukergrensesnittene til HytteAppen:
# Det er enkelt å bruke:
- Appen skal være lett å forstå og enkel å bruke for mennesker i alle aldre og med ulike tekniske ferdigheter.
- Menyer skal være logisk bygget opp og tekster skal være enkle og forståelige.
- Appen vil gi brukere veiledning og hjelp.

# For å sikre at et brukervennlig grensesnitt er tilgjengelig, kan man:
- Bruk korte, lettforståelige tekster.
- Ha en tydelig struktur.
- Bruk hensiktsmessig kontraster og farger.
- Unngå overdreven kompleksitet.
- Test appen på målgruppens medlemmer.
# Effektivitet:
- Appen skal gjøre det mulig for brukere å fullføre vanlige oppgaver raskt og enkelt.
- Pløying bør være en enkel prosess med bare noen få trinn.
 Appen må gi brukerne forståelig informasjon.

# Attraktivt:
- Appen bør ha et moderne design som er enkelt å bruke og appellerer til målgruppen.
- Det er viktig at bruken av bilder, farger og typografi er nøye vurdert og tilpasset målgruppen.

# Pålitelighet:
- Det er viktig at applikasjonen er stabil og fungerer feilfritt.
- Appen må ha oppdatert og nøyaktig informasjon.
- Appen skal beskytte brukernes datasikkerhet og personvern.

# Layouten:

# Startvinduet:
- En "karusell" med bilder av brukerens hytter.
- En oversikt over den kommende brøytingen for hver hytte.
- Værmelding for hytta som ble valgt.
- Hurtig tilgang til meldinger og innstillinger.

# For å sikre brukervennlig grensesnitt kan man gjøre følgende:
- Bruk tekster som er lett å forstå.
- Vær tydelig på strukturen.
- Bruk riktig kontraster og farger.
- Unngå for mye komplisering.
- Test applikasjonen med målgruppens medlemmer.
- Når du designer appen, er universell utforming (UU) veldig viktig.

# Innstillinger:
- Mulig å endre profildata.
- Hytter kan legges til, endres eller slettes.
- Mulighet til å velge språk og innstillinger for varsler.
- Mulighet til å se hjelp og brukerveiledning.
- For å sikre at brukergrensesnittet er enkelt og tilfredsstiller målgruppen, er det viktig å involvere brukerne i designprosessen (hvis mulig).

# Meldinger:
- En liste over alle meldinger som har blitt sendt og mottatt.
- Mulighet til å sortere meldinger etter type (brøytemannskap, hyttetjeneste).
- Mulig å sende filer og bilder.
- Mulighet til å begynne en diskusjon med brøytemanskap eller hytteservice.

# Brøytingsplan:
- En kalender som viser tilgjengelige brøytetider.
- Mulig å velge brøytingstid (f.eks. morgen, ettermiddag eller kveld).
- Mulig å inkludere et mobilnummer for SMS-varsling.
- En bekreftelsesside som inneholder alle nødvendige detaljer om bestillingen.

### Designmål
# For hytteeiere skal appen tilby følgende funksjoner:
- Enkel registrering av hytter og brukerprofiler.
- Bestilling av brøyting med nøyaktig dato og tid for ankomst og avreise.
- Mulighet for å velge hvem som skal motta SMS-varsel om brøyting.
- Vise værvarsel for hytteadressen.
- Mulig å kommunisere med hytteservice og brøytemannskap.

# Hytteservice bør gi følgende funksjoner:
- En samlet liste over alle hytter som trenger brøyting, sammen med detaljert informasjon om hver hytte og prosessen med å bestille dem.
- Mulighet til å planlegge effektive brøyteruter basert på informasjon om hyttene og bestillingene.
- Generering av omfattende statistikk over brøyteaktivitet fordelt på hytteområder, tidsperioder og andre faktorer.
- Enkel tilgang til brukerprofiler, hytter og bestillinger.

# Ytelse:
- Appen må være stabil, rask og responsiv.
- For de viktigste funksjonene skal appen fungere offline, det betyr at brukere kan bestille brøyting og se relevante innhold selv uten internettforbindelse.

# Tilgjengelighet:
- Appen må være tilgjengelig på Android og iOS.
- Appen bør ha universell utforming (UU) slik at alle kan bruke den, uavhengig av funksjonsevne.

# Sikkerhet:
- Appen må håndtere personvern i samsvar med GDPR og gjeldende sikkerhetsstandarder.
- Appen bør ha sikker håndtering og kryptering av brukerdata.

# Utforming/Design:
- Det er viktig at appen har et design som er moderne, brukervennlig og attraktivt for målgruppen.
- Det er viktig at designet er konsistent, lett å forstå og bruker gode bilder, fargepalett og typografi.
- Det er viktig at appens visuelle identitet er i samsvar med Hytteservices merkevareidentitet.

### Prototype - skjermbilder - Figma

## Kvalitetssikring

### Overordnet testbeskrivelse

### Overordnet testplan

### Prosjektstyring

### Roller/ansvar
Ettersom vi benytter oss av Kanban metodikk ved å bare plukke oppgaver og gjennomføre dem, har vi liten behov for offisielle roller. I denne seksjonen beskriver vi hvem som har hatt hvilke roller, og hvem som har tatt på seg nødvendig ansvar i prosjektet.

#### Roller:
- Møteleder: Lars
- Skribent/sektretær (til møtereferater): Adrian

#### Andre ansvarsområder:
- Sette opp prosjektbrettet: Adrian
- Vurdere pull requests: Alle

### Milepælsplan

I milepælsplanen så er det satt opp ukesvis hva vi hadde planlagt å jobbe med i hvilke uker, og hvilke planlagte frister som gjaldt for de arbeidsoppgavene.

Tabell: Milepælsplan

### Risikovurdering

### Møtelogg

## Systemutviklingsprosessmodell

### Velge og beskrive prosessmodell/systemutviklingsmodell/metode. Begrunne tilpasninger. Skissere alt.

## Referanser (APA7)

Asbjørn Rolstadås (2018.24.april). kravspesifikasjon
https://snl.no/kravspesifikasjon
