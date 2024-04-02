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
ER-diagrammet for HytteApp representerer en detaljert databasemodell som inneholder seks entiteter. Disse kartlegger forholdet mellom hytteeiere og deres hytter. Diagrammet inkluderer tilknyttede tjenester som værvarsling og brøytingsbestillinger, sortert etter hytteadresser og datoer. På venstre side av diagrammet finner vi Hytteeiere-tabellen, hvor hver bruker er unikt identifisert med brukernavn og telefonnummer. Tilhørigheten til flere hytter er illustrert i Hytte-tabellen med ID-nummer og sted. Daglige værvarsler knyttetes til Hytte-tabellen gjennom VærvarselEnDag-tabellen, som sikrer relevante oppdateringer for hver enkelt dag. Brøytebestilling-tabellen organiserer logistikken knyttet til brøyteoppdrag, som er essensielt for hyttens tilgjengelighet. Den inneholder all nødvendig informasjon for planlegging og gjennomføring av brøyting. Brøytemannskap-tabellen gir en innsikt i de ansatte som utfører brøytearbeidet, og kobler dem til tjenestene for å sikre en effektiv strukturering av brøyteoppdragene. Forholdene mellom disse tabellene reflekterer det nødvendige behovet for koordinering mellom tjenestene og informasjon. 

Hytteeier- entitet er mange til mange- forhold med Hytte-tabellen, som kan reflektere at en eier kan ha flere hytter. Hytte-entitet er i forhold til både VærvarselEnDag og Brøytebestilling, noe som understreker at hver hytte kan motta tilpassende tjenester basert på dato og behov. Forbindelsen mellom Brøytebestilling-tabellen og Brøytemannskap-tabellen sikrer at passende ressurser tildeles riktig for hvert oppdrag. 


### Domenemodell (UML-modell)
En domenemodell er et forenklet kart over et spesifikt område, for eksempel et programvaresystem eller en bedrift. Den viser de viktige tingene og hvordan de er knyttet til hverandre. Dette gjør det lettere for alle parter å forstå hva systemet gjør og hvordan det fungerer. Den viser de viktige entitetene og hvordan de er knyttet til hverandre. En domenemodell konsentrerer seg på de viktigste elementene, som for eks. entitetene, og hvordan de er knyttet til hverandre, som er også kalt «relasjoner», innenfor et gitt domene.  

## Design

### Systemdesign og klassediagram

### Systemarkitektur og teknologivalg

### Maskinvarespesfikasjon

### Utviklingsverktøy og teknologi
Dette er litt vanskelig å skrive noe om da vi ikke fysisk skal lage appen, men et grunnlag ville vært som følgende:
- For app-utvikling kunne vi ha brukt et rammeverk som React Native for å kunne bygge for både iOS og Android. Fordelen her er at det holde med én kodebase.
- Backend-utviklingen kunne foregått på Node.js for eksempel da det er godt egnet for utvikling av skalerbare serverapplikasjoner. Express.js er en slags miniversjon av Node.js som er meget enkelt å lære.
- Databasen kunne vært bygd i MySQL. Særlig fordi MySQL er som vi kjenner til gir meget stabil og pålitelig ytelse.
- Google Maps API for kart ville vært en god idé. Særlig fordi den gir mulighet for interaktive kart i appen.
- Dessuten har vi allerede brukt GitHub for deling av prosjektomfang og samarbeid i utviklingsteamet.

### Konfigurasjon-/versjonskontroll

### Brukergrensesnit

#### Den skal være enkelt å bruke:
Appen skal være lett å forstå og enkel å bruke for mennesker i alle aldre og med ulike tekniske ferdigheter. Det er viktig at hytteappen er enkel å bruke for alle, avhengig av tekniske kompetanse og alder. Poenget er å gi et brukervennlig syn og erfaring for både de som er vant til å bruke mobiler og PC, og også de som ikke pleier å bruke teknologi ofte.
Tekstene som skal brukes i appen må være lett å forstå og skrevet i et språk som er enkel og forståelig. 

Det er viktig å unngå slang, forkortelser og ord som kan være vanskelig å forstå for noen folk. Tekniske ord og termer må forklares med en definisjon. Korte avsnitt og setninger gjør det let å lese og forstå, unødvendig fet tekst og store bokstaver kan være veldig irriterende å lese. 
Menyer skal være logisk bygget opp og tekster skal være enkle og forståelige. Det er at appens menyer er lett å forstå pluss at de er strukturert logisk, da vil brukeren raskt og enkelt finne det de leter etter ved bruk av kategorier og underkategorier.

Appen vil gi brukere veiledning og hjelp, og de kan få hjelp gjennom for eks. at appen har en brukerveiledning som beskriver alle appens funksjoner, og når brukeren trenger det vil kontekstbaserte hjelpetekster bli vist. Eller eventuelt en seksjon som svarer på ofte stilte spørsmål (FAQ) som kan være en stor mulighet for å få hjelp fra Hytteservice. 

#### Effektivitet:
Appen skal gjøre det mulig for brukere å fullføre vanlige oppgaver raskt og enkelt, målet med appen er å gjøre den effektiv for brukere, og appen kan være strømlinjeformet slik at brukere kan spare tid og gjøre det de trenger rask og enkel. Appen skal gi brukerne informasjon som er brukbar samt forståelig.

#### Attraktivt:
Det er viktig at appen har et moderne design som er enkelt å bruke og appellerer til målgruppen den er lagd for, appens design skal også gjenspeile følelsene og prinsippene som ligger grunn til hytteliv.  Det er viktig at bruken av bilder, farger og typografi er nøye vurdert og tilpasset målgruppen.

#### Pålitelighet:
Det er viktig at applikasjonen er stabil og fungerer godt og feilfritt. Målet med appen er å gi brukere en følelse av trygghet og pålitelighet. Informasjon i appen bør alltid være oppdatert og korrekt sånn at brukere må kunne stole på at appens informasjon er pålitelig, og den skal sikre brukerens data og personvern.

#### Startvinduet:
Et sted i startvindu, for eks. øverst i startvinduet, skal brukeren se en karusell som viser bilder av alle de forskjellige hyttene, dette kan gjøre det lett for brukeren å få et innblikk av hyttene, som kan hjelpe brukere å velge raskt en hytte og som de kan lese mer informasjon om. 
Hver hytte skal ha en oversikt over kommende brøyting under karusellen.
Et eget separat avsnitt som inneholder nødvendig informasjon om hytte brukere valgte, og dette kan skal gi brukere oversikt over værforholdene på hytta sånn at brukere kan planlegge turen i henhold til disse forholdene.
Hurtig tilgang til meldinger og innstillinger på startvindu, et sted der brukere kan lett finne det og få tilgang til både innstillinger og meldinger. Dette lar brukere raskt og enkelt få tilgang til alle funksjoner som brukere oftest bruker

#### Innstillinger:
Hytteapp bør gi brukere muligheten til å kontrollere deres profil, preferanser og hytter. Profildata som navn, e-post og telefonnummer må enkelt oppdateres, det skal være lett å legge til nye nytter og endre informasjon om hytter som allerede eksisterer eller fjerne hytte som brukeren ikke trenger. 
Det skal være mulig å endre språket til appen for de som ikke snakker norks/bokmål. Brukere må ha brukerveiledning som inneholder viktig informasjon og råd om hvordan de skal bruke hver funksjon i appen. 
 
#### Meldinger:
En sterk og kraftig meldingsfunksjon i hytteappen som lar brukere snakke og kommunisere effektivt både med brøytemannskap og kabintjeneste, på denne måten kan alle, inkludert brukere, enkelt holde seg oppdatert samt få hjelp med det de trenger. 
En liste som har oversikt over alle meldinger som har blitt sendt og mottatt fra brøytemannskap og kabintjeneste burde vises i appen, dette kan gi brukere kommunikasjonshistorie for enkel referanse.
Hytteappen burde gi folk muligheten til å starte en samtale med brøytemannskap eller kabintjeneste, dette lar brukere å spørre spørsmål om de de lurer på, gi tilbakemeldinger og som de skal få svar tilbake raskt. 

#### Brøytingsplan:
Hytteappen bør gjør bestilling av brøyting veldig enkelt og raskt, brukere må få det de trenger uten å bli forsinket eller irritert på grunn av appens enkle grensesnitt og trinn. Det må være lett for brukeren a finne kalenderen som viser alle tilgjengelige brøytetider.   
Det skal være mulig for brukeren å velge brøytings tid for eks. morgen, ettermiddag eller kveld. Appen må mulig gjøre for brukeren å sette inn et mobilnummer som den kan få viktige SMS-varslinger. En bekreftelsesside kan være veldig hjelpsom som for brukere hvor den inneholder alle nødvendige detaljer om bestillingen. Dette kan gi trygghet til både deg og brukeren at bestillingen er bekreftet. 


### Designmål
#### For hytteeiere skal appen tilby følgende funksjoner:
- Enkel registrering av hytter og brukerprofiler.
- Bestilling av brøyting med nøyaktig dato og tid for ankomst og avreise.
- Mulighet for å velge hvem som skal motta SMS-varsel om brøyting.
- Vise værvarsel for hytteadressen.
- Mulig å kommunisere med hytteservice og brøytemannskap.

#### Hytteservice bør gi følgende funksjoner:
- En samlet liste over alle hytter som trenger brøyting, sammen med detaljert informasjon om hver hytte og prosessen med å bestille dem.
- Mulighet til å planlegge effektive brøyteruter basert på informasjon om hyttene og bestillingene.
- Generering av omfattende statistikk over brøyteaktivitet fordelt på hytteområder, tidsperioder og andre faktorer.
- Enkel tilgang til brukerprofiler, hytter og bestillinger.

#### Ytelse:
- Appen må være stabil, rask og responsiv.
- For de viktigste funksjonene skal appen fungere offline, det betyr at brukere kan bestille brøyting og se relevante innhold selv uten internettforbindelse.

#### Tilgjengelighet:
- Appen må være tilgjengelig på Android og iOS.
- Appen bør ha universell utforming (UU) slik at alle kan bruke den, uavhengig av funksjonsevne.

#### Sikkerhet:
- Appen må håndtere personvern i samsvar med GDPR og gjeldende sikkerhetsstandarder.
- Appen bør ha sikker håndtering og kryptering av brukerdata.

#### Utforming/Design:
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
For å gjennomføre et bra systemutviklingsprosjekt, så kan det være greit å ha oversikt over hva som kan gå galt i prosjektet. Dette gjør vi ved å identifisere potensielle risikoer, analysere hyppighet og alvorlighetsgrad på hvert punkt, og kalkulere en overordnet risikoscore. Desto høyere risikoscore, desto større fokus bør man ha på dem i prosjektet. Man bør også ha en risikohåndteringsplan, der man legger ut om spesifikke tiltak vi utfører dersom det skjer noe uforutsett. I et prosjekt som driver med Kanban metodikk bør man håndtere slike risikoer så snart de dukker opp, kalle inn til ekstraordinære møter, sende private meldinger eller iallefall ta det opp ved neste planlagte møte. Risikohåndteringsgrad er en kalkulert score basert på hvor sterke håndteringstiltak som må til, og hvor høy prioritet det har, altså hvor raskt man skal håndtere dem. 

Tabell: Risikoanalyse

Risikoanalysen lister opp det vi ser på som risikoer, komplett med hyppighet - hvor ofte vi tror det kommer til å skje, alvorlighetsgrad - hvor alvorlig det er om det inntreffer, og produktet av de to, som utgjør risikoscore.

Tabell: Risikohåndteringsplan

Risikohåndteringsplanen gjentar de foregående risikoene, men beskriver tiltakstyngde, hvor mye arbeid som må til for å fikse det, og hvilken prioritet det har å fikse det. Risikohåndteringsgrad er produktet av de to. De spesifikke tiltakene er beskrevet til slutt.

#### Identifisering av risikoer


### Møtelogg

## Systemutviklingsprosessmodell

### Velge og beskrive prosessmodell/systemutviklingsmodell/metode. Begrunne tilpasninger. Skissere alt.

## Referanser (APA7)

Asbjørn Rolstadås (2018.24.april). kravspesifikasjon
https://snl.no/kravspesifikasjon
