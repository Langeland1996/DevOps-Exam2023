## OPPGAVE 1
[ ] Task A
[x] Task B

## OPPGAVE 2
[x] Task A
[ ] Task B

## OPPGAVE 3
[x] Task A
[ ] Task B

## OPPGAVE 4
[ ] Task A
[ ] Task B

## OPPGAVE 5
#A - Kontinuerlig Integrering

**Definisjon av Kontinuerlig Integrering (CI):**
Kontinuerlig integrering (CI) er en praksis innen programvareutvikling der kodeendringer fra flere utviklere integreres regelmessig i en felles kodebase. Målet er å oppdage og løse integrasjonsproblemer tidlig i utviklingsprosessen. Dette oppnås ved å automatisere byggeprosessen og kjøre automatiserte tester for å sikre at den integrerte koden ikke bryter eksisterende funksjonalitet.

**Fordeler med å bruke CI:**

1. **Tidlig oppdagelse av feil:** CI hjelper med å identifisere feil tidlig i utviklingsprosessen, noe som reduserer kostnadene ved feilretting senere i prosjektet.
2. **Økt kodekvalitet:** Regelmessig integrasjon av kode bidrar til å opprettholde en høyere standard for kodekvalitet ved å sikre at koden er i samsvar med prosjektets retningslinjer og standarder.
3. **Raskere leveranser:** CI automatiserer bygg- og testprosessen, noe som resulterer i raskere og mer pålitelige leveranser av programvare.
4. **Bedre samarbeid:** Utviklere kan jobbe parallelt uten å bekymre seg for at deres endringer vil forstyrre andre. Dette fører til bedre samarbeid i teamet.

**Hvordan jobber vi med CI i GitHub praktisk?**

I GitHub kan du implementere CI ved å bruke GitHub Actions. Her er en praktisk tilnærming for et utviklingsteam på fire/fem utviklere:

1. **Konfigurer CI-filen:**
    - Opprett en CI-konfigurasjonsfil (for eksempel **`.github/workflows/pipeline.yml`**) i prosjektrepositoriet.
    - Definer trinnene som skal utføres under CI-prosessen, for eksempel bygging av programvare, kjøring av enhetstester, eller statisk kodeanalyse.
2. **Automatiserte bygg og tester:**
    - Konfigurer CI til å bygge prosjektet automatisk ved hver push til hovedgrenen eller når det åpnes en pull request.
    - Integrer enhetstester for å sikre at ny kode ikke bryter eksisterende funksjonalitet.
3. **Varslinger og rapporter:**
    - Konfigurer CI til å gi varsler til teamet ved feil under bygg- eller testprosessen.
    - Generer rapporter og artefakter for å lette feilsøking og evaluering av kodekvalitet.
4. **Daglig bruk i teamet:**
    - Oppfordre utviklere til å gjøre hyppige små endringer og pushe ofte for å dra nytte av CI.
    - Sørg for at teamet overvåker CI-resultatene regelmessig og håndterer eventuelle feil umiddelbart.

Ved å implementere CI i GitHub på denne måten, kan utviklingsteamet oppnå kontinuerlig integrasjon og dra nytte av de nevnte fordelene for å forbedre effektiviteten og kvaliteten på utviklingsprosessen.

#B - Sammenligning av Scrum/Smidig og DevOps fra et Utviklers Perspektiv

Scrum/Smidig Metodikk:

**Hovedtrekk:**
Scrum er en rammeverk innenfor smidig metodikk som fokuserer på iterativ utvikling, der funksjonalitet leveres i korte perioder kalt sprinter. Sentrale elementer inkluderer produktbacklog, sprintbacklog, daglige stående møter, sprint review, og retrospektiv. Smidig metodikk, generelt sett, verdsetter samarbeid, kundefokus, og evnen til å tilpasse seg endringer.

**Styrker:**

1. **Fleksibilitet:**
    - I et prosjekt der kundens krav endres fort, tillater Scrum tilpasning gjennom sprinter, slik at teamet raskt kan reagere på endringer og levere verdifull funksjonalitet.
2. **Tidlig tilbakemelding:**
    - Sprintreview gir kunden mulighet til å gi tilbakemelding tidlig i prosessen, slik at eventuelle misforståelser eller endringer kan adresseres raskt.
3. **Teamengasjement:** 
    - Selvorganiserende team er mer engasjerte og motiverte, da de har mer kontroll over sitt arbeid. Dette kan føre til høyere produktivitet og innovasjon.

**Utfordringer:**

1. **Usikkerhet:**
    - Hvis prosjektet har betydelig usikkerhet rundt kravene, kan Scrum føre til endringer midt i sprinter, som kan påvirke progresjonen og stabiliteten.
2. **Liten struktur:**
    - Noen komplekse prosjekter krever en høy grad av struktur og planlegging, og Scrum kan oppleves som for fleksibelt eller ustrukturert.

DevOps Metodikk:

**Grunnleggende prinsipper og praksiser:**
DevOps fokuserer på å bryte ned barrierer mellom utvikling og drift, fremmer automasjon og kontinuerlig integrasjon/leveranse (CI/CD). Dette skaper et samarbeid som akselererer utvikling og forbedrer stabilitet. Kjerneprinsippet er å integrere utviklings- og driftsprosesser gjennom hele livssyklusen.

**Påvirkning på kvalitet og tempo:**

- Kvalitet: Automatisert testing og overvåking kan forbedre programvarekvaliteten.
- Tempo: Automatisering av leveranseprosessen reduserer manuelle feil og akselererer utrullinger.

**Styrker:**

1. **Raskere leveranse:**
    - Automatisert CI/CD i DevOps reduserer manuelle trinn, slik at utviklere kan rulle ut endringer raskt og pålitelig, akselererende leveransetempoet.
2. **Stabilitet:**
    - Sammenhengen mellom utviklings- og driftsteam i DevOps reduserer konflikter og misforståelser, noe som fører til økt systemstabilitet.
3. **Automatisert testing:**
    - Implementering av automatiserte tester i DevOps-syklusen bidrar til å oppdage feil tidlig, forbedre kvaliteten og redusere risikoen for feil i produksjon.

**Utfordringer:**

1. **Kulturendring:**
    - Å få teamet og organisasjonen til å akseptere en endring i kulturen, hvor utviklere og driftsfolk samarbeider tettere, kan være vanskelig og møte motstand.
2. **Kompleksitet:**
    - Implementering av automasjon og integrasjon av ulike verktøy kan være komplekst, spesielt i større organisasjoner med eksisterende systemer.

### **Programvarekvalitet:**

**Scrum/Smidig:**

- *Fokus:* Tidlig tilbakemelding og kontinuerlig forbedring gjennom iterasjoner.
- *Fordeler:* Kunden er involvert gjennom hele prosessen, noe som reduserer risikoen for misforståelser. Gjentatte testingssykluser i hver iterasjon gir mulighet for rask feilretting.
- *Potensielle utfordringer:* Rask tilpasning til endringer kan føre til at noen tekniske aspekter blir nedprioritert, og kvalitetskontroll kan lide hvis testing blir forsømt.

**DevOps:**

- *Fokus:* Automatisering av testing og kontinuerlig integrasjon for å sikre kvalitet gjennom hele utviklingsløpet.
- *Fordeler:* Automatisert testing bidrar til å oppdage og løse feil tidlig, og kontinuerlig integrasjon sikrer at kodeintegrasjon skjer jevnlig, reduserer risikoen for store konflikter ved sammenføyning.
- *Potensielle utfordringer:* Implementering av automatisert testing kan være kompleks, og i noen tilfeller kan det være utfordrende å skape full testdekning.

### **Leveransetempo:**

**Scrum/Smidig:**

- *Fokus:* Jevn leveranse av funksjonalitet gjennom sprinter.
- *Fordeler:* Hyppige leveranser gir kunden mulighet til å se og bruke funksjonalitet raskt, og teamet kan tilpasse seg endringer i krav effektivt.
- *Potensielle utfordringer:* Utrullinger kan variere i kompleksitet, og i noen tilfeller kan det oppstå utfordringer med å opprettholde et konstant leveranstempo.

**DevOps:**

- *Fokus:* Rask og pålitelig leveranse gjennom automatisering og kontinuerlig integrasjon/leveranse.
- *Fordeler:* Redusert manuell inngripen øker hastigheten på utviklingsløpet, og automatisering av utrullinger gir stabilitet og pålitelighet.
- *Potensielle utfordringer:* Å implementere CI/CD og automatiserte utrullinger krever investeringer i infrastruktur og kulturell endring, og dette kan ta tid.

### **Sammenligning og Kontrast:**

- **Påvirkning på programvarekvalitet:**
    - *Scrum/Smidig:* Kvaliteten er avhengig av grundige testingssykluser i hver iterasjon og samarbeid med kunden for å unngå misforståelser.
    - *DevOps:* Automatisering og kontinuerlig integrasjon sikrer kvaliteten gjennom hele utviklingsløpet.
- **Leveransetempo:**
    - *Scrum/Smidig:* Hyppige leveranser gir jevn fremdrift, men tempoet kan variere avhengig av kompleksiteten til hver iterasjon.
    - *DevOps:* Automatisert CI/CD akselererer leveransetempoet ved å eliminere manuelle hindringer, og gir pålitelige utrullinger.
- **Fordelaktige aspekter i ulike situasjoner:**
    - *Scrum/Smidig:* Mer egnet for prosjekter der hyppige endringer er forventet og hvor kundeengasjement er nøkkelen.
    - *DevOps:* Effektivt i prosjekter som krever rask og pålitelig utrulling av endringer, spesielt der systemstabilitet er kritisk.

# **C. Det Andre Prinsippet - Feedback**

### **Etablere Feedback-mekanismer:**

1. **Beta Testing:**
    - Lanser den nye funksjonaliteten i en begrenset beta-versjon for en gruppe brukere.
    - Inviter brukere til å delta frivillig og gi tilbakemeldinger basert på deres erfaringer.
2. **Brukerundersøkelser:**
    - Opprett spørreskjemaer eller intervjuer for å få kvantitative og kvalitative svar.
    - Still spørsmål som fokuserer på brukeropplevelse, brukervennlighet og oppfyllelse av behov.
3. **In-App Feedback:**
    - Implementer en enkel måte for brukere å gi tilbakemeldinger direkte i applikasjonen.
    - Legg til en "Feedback" -knapp eller et skjema som gjør det enkelt for brukere å uttrykke sine synspunkter.

### **Analyser og Drøft Behovene:**

1. **Organisering av Feedback:**
    - Kategoriser tilbakemeldingene i relevante grupper, for eksempel brukervennlighet, ytelse eller manglende funksjoner.
2. **Hold Brukerworkshops:**
    - Inviter brukere til workshops for å diskutere og validere funksjonaliteten.
    - Dette gir innsikt i deres perspektiver og behov som kan ha blitt oversett.

### **Kontinuerlig Forbedring:**

1. **Iterativ Utvikling:**
    - Bruk feedbacken til å iterere over designet og funksjonaliteten.
    - Implementer forbedringer basert på tilbakemeldinger for å sikre at produktet evoluerer.
2. **A/B Testing:**
    - Utfør A/B-testing med varianter av funksjonaliteten for å identifisere den mest effektive løsningen basert på faktiske brukerdata.

### **Integrering i Utviklingslivssyklusen:**

1. **Tidlig Fase:**
    - Få feedback allerede i tidlige designfaser for å unngå kostbare endringer senere.
    - Utfør brukertesting på prototyper for å validere konseptene.
2. **Midtveis:**
    - Beta-test for å fange opp eventuelle problemer før den offisielle lanseringen.
    - Organiser regelmessige oppdateringer basert på feedback.
3. **Etter Lansering:**
    - Fortsett å samle inn og analysere feedback selv etter lanseringen.
    - Bruk tilbakemelding til å planlegge fremtidige oppdateringer og nye funksjoner.