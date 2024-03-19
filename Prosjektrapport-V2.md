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

En interessent kan omfatte enkeltpersoner, team eller organisasjoner som er interesserte i eller som kan påvirke direkte eller indirekte av utviklingsprosessen og det endelige utfallet av prosjektet. Interessentene i HytteApp inkluderer ulike gruppe interessenter, hver med spesifikke forventninger og interesser i forhold til appens funksjonalitet, ytelse og daglig bruk. 

Blant de direkte interessentene er hytteeierne, som primært bruker verktøyet for å registrere seg og bestille brøytetjenester. Dette viser tydelig viser deres ønske for tilgjengelighet og brukervennlighet. Deretter har vi brøytemannskapet, de operative interessentene, som er avhengige av dette appen for å koordinere og utføre sitt daglig arbeid. En annen direkte interessentgruppe er administrasjon og Hytteservice. Deres intensjon med HytteApp er å håndtere bestillinger og overvåke brøyteoperasjonene, samt hente ut rapporter og innsikt som kan brukes for å forbedre tjenesten.  

En annen kategori ville inkludere de som har en indirekte innvirkning i HytteApp-prosjektet. Dette omfatter de som har ansvaret for sikre at forskrifter, standarder regelverk blir etterfulgt. Et eksempel på en indirekte aktør som likevel har stor betydning for appen, er Statens Kartverk. Deres rolle er å levere kritiske eiendomsdata som er nødvendige for nøyaktig lokalisering av hytter. Dette er essensielt for at brøyting kan planlegges og gjennomføres effektivt. En annen indirekte aktør er de regulatoriske myndighetene, som sørger for at HytteApp følger personvernlovgivingen GDPR og standarder for universell utforming. Dette er avgjørende for tjenestens tilgjengelighet og lovlighet. 


### Funksjonelle krav

### Ikke-funksjonelle krav

### Krav til universell utforming

### Informasjonssikkerhet og personvern


## Analyse

### Aktører og UseCase(UC)

### UC-diagram

### UC-beskrivelser

### Aktivitetsdiagram

### Flytdiagram

### Datamodell (ER-modell)

ER-diagrammet for HytteApp representerer en detaljert databasemodell inneholder som seks entiteter som kartlegger forholdet mellom hytteeiere og deres hytter. Diagrammet inkluderer tilknyttede tjenester som værvarsel og brøytingsbestillinger, sortert etter hytteadresser og datoer. På venstre side av diagrammet finner vi Hytteeiere tabellen, der hver bruker er unikt identifisert med brukernavn og telefonnummer. Tilhørighet til flere hytter er illustrert i Hytte-tabellen med ID-nummer og sted. Daglige værvarsler knyttetes til Hytter-tabellen gjennom VærvarselEnDag-tabellen, som sikrer relevante oppdateringer for hver dag. Brøytebestilling-tabellen organiserer logistikken knyttet til brøyteoppdragene, noe som er essensielt for hyttens tilgjengelighet. Den inneholder all nødvendige informasjon for planlegging og gjennomføring av brøyting. Brøytemannskap-tabellen gir en innsikt i de ansatte som utfører brøytearbeidet, og kobler dem til tjenestene, noe som sikrer effektiv strukturering av brøyteoppdragene. Forholdene mellom disse tabellene reflekterer det nødvendige behovet for koordinering av tjenester og informasjon:
Hytteeier- entitet er mange til mange- forhold med Hytte-tabellen, som kan reflektere at en eier kan ha flere hytter. Hytte-entitet er i forhold til både VærvarselEnDag og Brøytebestilling, noe som understreker at hver hytte kan motta tilpassende tjenester basert på dato og behov. Forbindelsen mellom Brøytebestilling-tabellen og Brøytemannskap-tabellen sikrer at passende ressurser tildeles riktig for hvert oppdrag. 


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




