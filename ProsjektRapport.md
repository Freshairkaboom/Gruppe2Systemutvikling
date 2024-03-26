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


# Kravanalyse

## Funksjonelle Krav:
- Registering og innlogging for hytteeiere
- Mulighet for å bestille brøyting
- Varslingssytem via SMS når brøyting er fullført
- Integrasjon mot Statens Kartverk for å hente hytteadresser

- Funksjonelle krav (brukerregistrering, bestilling, motta sms, værvarsel, administrasjon)

## Ikke-funksjonelle krav:

### Sikkerhet og personvern: 
Appen må overholde GDPR-krav og andre relevante lover og forskrifter angående personvern. Dette inkluderer sikker lagring og håndtering av brukerdata, samt kryptering av sensitiv informasjon under overføring.

### Universell utforming (UU): 
Appen må være tilgjengelig og brukervennlig for alle, uavhengig av eventuelle funksjonshemminger eller teknisk kunnskap. Dette inkluderer tilpasninger for syns-, hørsels- og motoriske utfordringer.

### Ytelse og skalerbarhet: 
Appen må kunne håndtere et stort antall brukere samtidig uten at det går på bekostning av ytelsen. Videre må den være skalerbar for å kunne tilpasse seg økende brukerbase og funksjonalitetsbehov over tid.

### Pålitelighet og tilgjengelighet: 
Appen må være stabil og pålitelig, med minimal nedetid og feilhåndtering. Videre må den være tilgjengelig på ulike plattformer og enheter, inkludert mobile enheter og nettlesere.

### Brukervennlighet og responsivt design: 
Appen må ha et intuitivt og responsivt grensesnitt som er enkelt å navigere og forstå for brukerne. Den må også tilpasses forskjellige skjermstørrelser og enheter for optimal brukeropplevelse.

### Teknologisk plattform: 
Valg av teknologisk plattform må være godt dokumentert og begrunnet, med fokus på sikkerhet, fleksibilitet og vedlikeholdbarhet over tid.

### Teknisk dokumentasjon: 
Det må være tilstrekkelig teknisk dokumentasjon og brukerveiledninger tilgjengelig for å hjelpe både utviklere og brukere med å forstå og bruke appen effektivt.



###
Universell utforming

I forhold til utvikling av HytteApp er det en del spørsmål som må stilles i forhold til hvorvidt vi skal ta hensyn til spesielle brukerbehov, eller om vi holder oss til etablerte standarder. Vi må svare på om vi overholder Web Content Accessibility Guidelines 2.1 (World Wide Web Consortium, 2018) og likestillings- og diskrimineringsloven (Lovdata, 2017), og om designet vårt kan sies å være inkluderende.

For å godkjenne design bør designere vise til hvordan de har tatt hensyn til UU i produktet, hvilke hensyn og virkemidler som er brukt i forhold til etablerte standarder, og hvilke nye hensyn som er tatt. Deretter må de som godkjenner designene gå over om det som er tatt hensyn til og implementert i designet er nok til å overholde WCAG og likestillings- og diskrimineringsloven. I designfasen, spesifikt i etterkant av prototyping, kan det være hjelpsomt å involvere testgrupper for å se på om de forskjellige hensynene faktisk fungerer.

Det er viktig å dokumentere ikke bare alle hensyn som tas, men også hvilke hensyn som ennå ikke er tatt. Dette kan gjøres ved hjelp av å inkludere en tilgjengelighetserklæring i applikasjonen. En slik erklæring er et verktøy som viser til hvorvidt applikasjonen er i samsvar med UU, og lister opp alle bruddene på UU, hvilke brukergrupper som blir påvirket av bruddene, samt en måte for brukere å melde fra om brudd og sende klage til diskrimineringsnemda. I erklæringen kan man også legge ut om hvorfor ikke alle standardene er fulgt, hva som gjøres med det, og evt. hvor lang tid det vil ta før bruddene fikses. Et godt eksempel på en slik erklæring er på USN sin egen nettside (Universitetet i Sørøst-Norge, 2024), se referanse for link.

## Design av teknologi
- Frontend
- Backend
- Database
- Mass transit (RabbitMq)

## Kvalitetssikring og testing
- Overordna testplan/testbeskrivelse

## Kontekst/Bakgrunn

## Karakterisering av prosjektet

## Interessenter

## Omfang

## Eksklusjoner

##
Referanser:

World Wide Web Consortium. (2018). Web Content Accessibility Guidelines (WCAG) 2.1. Hentet fra https://www.w3.org/TR/WCAG21/
Kultur- og likestillingsdepartmentet. (2017) Lov om likestilling og forbud mot diskriminering (likestillings- og diskrimineringsloven). Hentet fra https://lovdata.no/dokument/NL/lov/2017-06-16-51
Universitetet i Sørøst-Norge. (2024) Tilgjengelighetserklæring. Hentet fra https://uustatus.no/nb/erklaringer/publisert/d186395f-72ef-4445-aeb8-8e4093eb7639
