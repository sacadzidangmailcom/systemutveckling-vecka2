# Systemutveckling - Vecka 2

## 1. Skillnaden mellan vattenfallsmodellen och agil metodik

### Vattenfallsmodellen
- **Planering:** En stor, detaljerad plan görs på en gång.  
- **Process:**  
  - Krav: alla krav skrivs från början.  
  - Design: alla skärmar ritas upp direkt.  
  - Kodning: all kod skrivs i ett svep.  
  - Test: test sker först när allt är färdigt.  
  - Lansering: appen släpps komplett till alla användare.  
- **Resultat:**  
  - Alla funktioner finns på plats vid lansering.  
  - Ändringar efteråt är mycket svåra och kostsamma.  
  - Fel som upptäcks kan innebära att man måste börja om från början.  

### Agil metodik
- **Planering:** Man börjar med de viktigaste funktionerna och planerar stegvis.  
- **Process:**  
  - Projektet delas upp i **sprintar** (små delar).  
  - Exempel:  
    - Sprint 1: inloggning och uppladdning av bilder.  
    - Sprint 2: följa andra och se flöde.  
    - Sprint 3: direktmeddelanden.  
    - Sprint 4: kommentarer och gilla-funktion.  
  - Varje sprint testas och förbättras med hjälp av kundfeedback.  
- **Resultat:**  
  - Flexibilitet – planerna kan ändras efter kundens behov.  
  - Kontinuerlig förbättring och snabbare leverans av nytta.  

---

## 2. Vad är ett Git-commit och varför är det viktigt?

- Ett **commit** i Git är som att spara en version av ditt arbete lokalt på din dator.  
- Varje commit innehåller en beskrivande text om vad som ändrats.  
- **Varför viktigt?**  
  - Gör det möjligt att gå tillbaka om något blir fel.  
  - Låter dig se vad som ändrats och när.  
  - Underlättar samarbete – flera personer kan jobba parallellt utan att störa varandra.  

---

## 3. Vad innebär samarbete med GitHub?  
### Branches, Pull Requests och Merge

- **Samarbete med GitHub:**  
  Flera personer kan arbeta på samma projekt online, dela kod och granska varandras ändringar.  

- **Branch:**  
  En kopia av projektet där du kan lägga till eller ändra något utan att påverka huvudversionen (main).  

- **Pull Request (PR):**  
  En begäran om att få slå ihop ändringar från din branch till main. PR används också för att diskutera och granska kod innan den läggs in.  

- **Merge:**  
  När en pull request godkänns och dina ändringar blir en del av huvudprojektet (main).  
