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

## Foranalyse
### Problembeskrivelse:
Hytteservice står overfor utfordringer knyttet til ineffektivitet og unødvendige kostnader i forbindelse med brøyting av hytteområder. Uten en nøyaktig oversikt over hytter som er i bruk, må alle områder brøytes ved snøfall, noe som fører til økte kostnader, tidssløsing og unødvendig slitasje på utstyr. Det mangler også en effektiv måte å kommunisere med hytteeiere og planlegge brøyteaktiviteter.

### Bakgrunn:
Hytteservice er et firma som leverer ulike tjenester til hytteeiere over hele landet, inkludert vaktmestertjenester, vedlevering, brøyting og strøing. Særlig i vinterhalvåret er brøyting til hytter og hytteområder en sentral aktivitet. For å effektivisere og forenkle brøyteprosessen samt forbedre kommunikasjonen med hytteeiere, ønsker Hytteservice å utvikle en applikasjon, HytteApp.

### Hensikt:
HytteApp-prosjektet har som hensikt å utvikle en applikasjon som gir Hytteservice og hytteeiere en bedre oversikt over brøytebehov og en enklere måte å bestille og utføre brøyting på. Ved å tilby en brukervennlig plattform ønsker Hytteservice å redusere kostnader, spare tid og minimere slitasje på utstyr samtidig som de forbedrer kundeopplevelsen og effektiviteten i tjenesteleveransen.

### Målsettinger:

Utvikle en første versjon av HytteApp som støtter brøytetjenester og forenkler oversikt og bestilling av brøyting i hytteområder.
Muliggjøre registrering av hytteeiere som brukere, bestilling av brøyting ved å melde planlagt ankomst til hytta, og sending/mottak av meldinger til/fra Hytteservice/brøytemannskap.
Integrere værvarsling for hytteadresse og knytte HytteApp til en sentral hos Hytteservice.no for å sende SMS-varsler til hytteeiere ved behov for brøyting.
Hente adresser til hytter fra Statens Kartverk og sikre at appen overholder kravene til personvern i henhold til GDPR.
Tilby en universelt utformet app for hytteeiere som er enkel å bruke og tilgjengelig for ulike brukergrupper.
Implementere en administrasjonsmodul for Hytteservice-administrasjonen for å vise oversikter og generere statistikk, inkludert antall brøytede hytter siste periode og oversikt over hytteområder med mest brøyting siste periode.

## Problembeskrivelse:
Hytteservice, et firma som tilbyr ulike tjenester til hytteeiere, opplever utfordringer knyttet til effektiviteten og kostnadene ved brøytingstjenester i hytteområder. Mangel på nøyaktig informasjon om hvem som befinner seg på eller skal bruke hyttene fører til unødvendig brøyting av veier og gårdsplasser. Dette fører til høye kostnader, økt slitasje på utstyr og økt tidsbruk. Dette ineffektive systemet fører også til redusert kundeopplevelse og kan svekke Hytteservice sitt omdømme. 

## Bakgrunn:
Hytteservice har lenge levert tjenester til hytteeiere over hele landet, men med vinterhalvåret kommer spesifikke utfordringer knyttet til brøyting av veier og områder rundt hyttene. Den nåværende praksisen med å brøyte basert på estimater og generell kunnskap om hyttebruk har vist seg å være ineffektiv og kostbar. Nå skal det automatiseres og digitaliseres for å tilby en bedre løsning enn det de har.

## Hensikt og målsettinger for prosjektet:
Gjennom utviklingen av HytteApp ønsker Hytteservice å modernisere sin tilnærming til brøytingstjenester, samtidig som de opprettholder sitt omdømme for kvalitet og pålitelighet i markedet. 

Formålet med prosjektet er å utvikle en mobilapplikasjon, HytteApp, som effektiviserer og forbedrer brøyteprosessen for Hytteservice og hytteeierne. Målene inkluderer:

Å redusere kostnader ved unødvendig brøyting og slitasje på utstyr.
Å utvikle en funksjonell og brukervennlig HytteApp. 
Å forbedre kundeopplevelsen for hytteeiere gjennom en enkel og pålitelig bestillingsprosess.
Å øke effektiviteten til Hytteservice gjennom bedre ressursallokering og planlegging av brøyteoppdrag.
Å sikre at løsningen oppfyller personvernkravene, spesielt GDPR, og har universell utforming for tilgjengelighet.


### Brukerbehov
#### Brukerhistorier.
Brukerhistorier er et verktøy som brukes i gjennomføring av prosjekter, spesielt som et virkemiddel i SCRUM og Kanban arbeidsmetoder, for å oversette kravspesifikasjoner til konkrete ønsker som utviklere kan deretter kan prøve å oppfylle ved å lage konkrete arbeidsoppgaver som gjennomføres av prosjektteam. Her er noen av brukerhistoriene vi har tenkt ut som kan være relevant for bruken av HytteApp.

- Som hytteeier ønsker jeg å kunne bestille måking på en raskt og effektiv måte, så jeg kan komme til en ferdigbrøytet hytte.
- Som brøytemannskap ønsker jeg en rask og effektiv kommunikasjon med de som eier hyttene, så jeg vet hvilke hytter som skal brøytes, og jeg slipper unødig slitasje på utstyret.
- Som administrator ønsker jeg en forenklet og oversiktig bestilling av måking, så jeg slipper unødvendig kostnader og at jeg kan overvåke og optimalisere tjenesten.
- Som bruker av hytteappen ønsker jeg at den er i tråd med GDPR og at den har universiell utforming, så den er sikker og tilgjengelig for alle brukere


## Kravanalyse
### Funksjonelle Krav:
- Registering og innlogging for hytteeiere
- Mulighet for å bestille brøyting
- Varslingssytem via SMS når brøyting er fullført
- Integrasjon mot Statens Kartverk for å hente hytteadresser

- Funksjonelle krav (brukerregistrering, bestilling, motta sms, værvarsel, administrasjon)
- Ikke-funksjonelle krav (Universell utforming, GDPR)

## Design av teknologi
- Frontend
- Backend
- Database
- Mass transit (RabbitMq)

## Kvalitetssikring og testing
- Overordna testplan/testbeskrivelse
- UseCase:

- Definisjon:  UseCase er en beskrivelse av en sekvens av handlinger som utføres av brukerne innenfor er system, som gir observerbar verdi til en aktør. Aktøren kan være en person eller et annet system. UseCase fokuserer på hva systemet gjør og ikke hvordan det gjøres. 

- Formål: Hovedformålet med UseCase er å fange opp funksjonelle krav ved å beskrive hvordan systemet skal oppføre seg i forskjellige sitasjoner. De hjelper med å sikre at systemet dekker alle forventede interaksjoner med brukere eller eksterne systemer. 

- Aktører: Entiteter (vanligvis brukere eller eksterne systemer) som interagerer med systemer. 

- Forutsetninger: Betingelse som må være oppfylt før brukstilfellet starter. 

- Resultat: Den endelige tilstanden etter at UseCase er utført, som viser den oppnådde verdien eller endringer i systemet. 

- Bruksmønster:

- Definisjon: Begrepet «bruksmønster» brukes ofte om hverandre med «UseCase», men det kan også referere til en mer generell ide om mønstre eller vaner i hvordan brukere interagerer med systemet over tid. Det kan også vise til et sett med UseCase som tilsammen skaper en komplett funksjonell funksjon av systemet. 

- Formål: Bruksmønstre bidrar til å identifisere og forstå vanlige måter systemet blir brukt på, noe som kan hjelpe designere og utviklere med å fokusere brukernes behov og forbedre brukeropplevelsen.

- Tilnærming: Analysere og dokumentere vanlige oppgaver eller mål som brukere forsøker å oppnå ved å bruke systemet og identifisere gjentatte interaksjoner som kan optimaliseres eller støttes bedre gjennom design. 

- Sammenheng mellom UseCase og Bruksmønster 

- Komplementære Verktøy: UseCase og bruksmønster fungerer sammen for å gi et fullstendig bilde av hvordan systemet vil bli brukt. UseCase gir detaljerte, spesifikke eksempler på interaksjoner, mens bruksmønster kan avsløre bredere mønstre i bruk og brukerbehov. 

- Design og utvikling: Sammen bidrar disse tilnærmingene til å forme systemdesignet ved å fokusere på brukerens perspektiv, og sikrer at sluttproduktet oppfyller brukerens krav og forventinger. 

- Ved å bruke UseCase og forstå bruksmønster, kan utviklingsteamene lage mer intuitive og brukervennlige applikasjoner og systemer som bedre møter målgruppens behov. 







## UseCase og Brukermønster


## Kontekst/Bakgrunn

## Karakterisering av prosjektet

## Interessenter

## Omfang

## Eksklusjoner
