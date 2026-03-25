{% include navbar.html %}{% include top-box.html %}
## 🚀 Læringssti i programmering
Her finner dere en systematisk læringssti dere kan følge selv. Den består av masse videoer, og oppgaver.

Dette vil ikke erstatte fysisk forelesning og seminar, se forelesningsplan [her](https://uit-bed-1304-h26.github.io/forelesningsplan.html). Forelesningsnotatene er samlet i en egen GitHub-bok for faget, [trykk her](https://markusaase97.github.io/BED-1304-bok/notebooks/00/intro.html) for å komme til boka.

___

| **Tema** | **Videoer i detalj** | **Introduksjonsvideo** | **Oppgaver/progresjon** |
| 🟢 1. Introduksjon | [Velkommen](https://youtu.be/DPkvKuK4B5A) · [Installasjon](https://youtu.be/lYwkKKI9Fnw) |  | Gjør dere kjent med Python |
| 🐍 2. Python Basics | [Variabler/datatyper](https://youtu.be/rctSMn1f1jM) · [Operatorer](https://youtu.be/qilshscGVy8) · [Kode-session](https://youtu.be/UyOo273-3p8) | ▶️ [Før forelesning](https://youtu.be/P7DCjp5QJCk) | <a href="oppgaver/PythonBasicsRepetisjon.pdf" target="_blank">Oppgaver</a> |
| 🔢 3. Funksjoner | [Hva er en funksjon?](https://youtu.be/WxZAB8j8epA) · [Koding i Python](https://youtu.be/xw3ZyC0pe-0) | ▶️ [Før forelesning](https://youtu.be/u1FSeJdB3LU) | <a href="oppgaver/FunksjonerRepetisjon.pdf" target="_blank">Oppgaver</a> |
| 🗒 4. Lister, dictionaries og NumPy | [Intro til Lister, tuples og dictionaries](https://youtu.be/lcf9KVkeYQU) · [Koding/datastrukturer](https://youtu.be/3AT-GRcsoUo) · [Intro til Numpy](https://youtu.be/hpGI4vDcaLU) · [Koding NumPy](link) | ▶️ [Før forelesning](https://youtu.be/kgcOG7q2dq4) | <a href="oppgaver/ListerNumpyRepetisjon.pdf" target="_blank">Oppgaver</a> |
| 💻 5. Pandas og databehandling | [Pandas](link) · [Koding](link) | ▶️ [Før forelesning](https://youtu.be/kPINFf-sdaI) | <a href="oppgaver/PandasRepetisjon.pdf" target="_blank">Oppgaver</a> |
| 🧠 6. Logikk og løkker | [If, elif og else](link) · [For-løkker](link) · [While-løkker](link) · [Koding](link) | ▶️ [Før forelesning](https://youtu.be/YbAtgj7epfY) | <a href="oppgaver/LogikkRepetisjon.pdf" target="_blank">Oppgaver</a> |
| 📊 7. Matplotlib | [Visualisering](link) · [Koding](link) · [Visualisering i 3D](link) | ▶️ [Før forelesning](https://youtu.be/ALb-Ie-pAx4) | <a href="oppgaver/MatplotlibRepetisjon.pdf" target="_blank">Oppgaver</a> |
| 🧮 8. SymPy | [SymPy](link) · [Tilbud- og etterspørsel](link) · [Koding](link) | ▶️ [Før forelesning](https://youtu.be/XAUuQ5sVijE) | <a href="oppgaver/SympyRepetisjon.pdf" target="_blank">Oppgaver</a> |
| 🔬 9. Simulering | [Simulering](link) · [Koding](link) | ▶️ [Før forelesning](https://youtu.be/Vae0YXmOF8M) | <a href="oppgaver/SimuleringRepetisjon.pdf" target="_blank">Oppgaver</a> |

---
## 🧭 Hvordan bruke siden
- Start med *video i detalj*-videoene  
- Se gjennom *introduksjonsvideo*, disse er ment og forberede deg til forelesning.  
- Jobb med oppgaver. Her finner dere en rekke pdf’er for de ulike forelesningene. Disse gir dere litt repetisjon, og oppgaver/løsningsforslag knyttet til forelesningene. Totalt sett, vil dette gå igjennom en god del av pensum i faget. Likevel, anbefaler jeg å møte i forelesning/seminar for å få presentert stoffet og bruke ressursene her som repetisjon for å terpe på fagstoffet.
- **Husk:** Dere er ansvalig for **egen læring**! Gå i gjennom forelesningsnotatene grundig, for å dekke hele pensum. Seminar-filene har også masse oppgaver. Videoene er også pensum.
- Øvelse gjør mester!
---

### Case oppgaver
For å bli gode i programmering, kan man ikke bare lese pensum, man må kode, få feilmeldinger, rive seg litt i håret og plutselig få det til. Da vil man stille seg spørsmålet, *hvorfor funka dette?* eller *hvorfor funka det ikke?*, begge er gode spørsmål - og nyttige å reflektere over i læringsprosessen.

Under her vil jeg publisere en rekke case-oppgaver, som krever at dere anvender programmering-skillsa deres!

Du skal lage et lite Python-program som analyserer en liste med tall. Programmet skal bygges opp steg for steg ved hjelp av funksjoner.

---

### ➕➖ The basics ➗✖️

**Del 1 – Kom i gang**  
Lag en liste med minst 10 tall (heltall eller desimaltall).

```python
tall = [3, 7, 2, 9, 4, 5, 8, 1, 6, 10]  # dette er et eksempel
```

Du kan endre verdiene selv, men behold minst 10 elementer i listen.

---

**Del 2 – Funksjoner**

Lag følgende funksjoner:

1. En funksjon som returnerer summen av alle tallene i listen  
2. En funksjon som returnerer gjennomsnittet  
3. En funksjon som finner det største tallet  

**Krav:**
- Funksjonene skal ta inn en liste som parameter  
- De skal returnere (ikke printe) resultatet  

**Eksempel på bruk:**
```python
print(sum_liste(tall))
print(gjennomsnitt(tall))
print(maks_verdi(tall))
```

---

**Del 3 – Filtrering**

Lag en funksjon som:

- tar inn en liste og en grenseverdi  
- returnerer en ny liste med alle tall som er større enn grenseverdien  

**Eksempel:**
```python
print(filtrer_storre_enn(tall, 5))
```

---

**Del 4 – Kombiner alt**

Lag et hovedprogram som:

- skriver ut listen
- skriver ut summen
- skriver ut gjennomsnittet
- skriver ut største verdi
- skriver ut resultatet av filtreringen (velg en grenseverdi selv)

**Eksempel på utskrift:**
```
Liste: [3, 7, 2, 9, ...]
Sum: 55
Gjennomsnitt: 5.5
Største verdi: 10
Tall større enn 5: [7, 9, 8, 6, 10]
```

---

**Del 5 – Hva med AI?**

Nå skal du bruke et AI-verktøy (for eksempel ChatGPT) til å løse oppgave 1–4.

**Oppgave:**
1. Be AI om å lage hele programmet for deg  
2. Kopier koden du får  
3. Gå nøye gjennom koden linje for linje  

**Refleksjon:**

Skriv kort om følgende:

- Hva i koden forstår du godt?  
- Er det noe AI har gjort som du ikke selv ville gjort?  
- Bruker AI andre løsninger enn dine (for eksempel innebygde funksjoner)?  
- Hva lærte du av å sammenligne din løsning med AI sin?  

**Viktig:**
Målet er ikke bare å få riktig svar, men å forstå hvordan koden fungerer. Hvis du bruker AI uten å forstå koden, har du i praksis ikke løst oppgaven.

### 👩‍💻 Programmering og AI 👨‍💻

Vi lever i en tid der generativ AI blir en del av hverdagen vår. Søker vi på *Google* får vi opp AI-genererte forslag til svar, leser vi nyheter på NRK finnes det AI-oppsummeringer, og teksten her er korrekturlest ved hjelp av AI – uansett!

Programmering har vært viktig i mange år, og vil fortsatt være det. Mange kan stille seg spørsmålet: *Trenger jeg å kunne kode, eller kan jeg bare spørre AI?* Dette er et legitimt spørsmål, men det fanger ikke hele bildet. Ja, vi har generativ AI som kan hjelpe oss å skrive kode – men vi trenger fortsatt mennesker som **forstår** koden som blir produsert.

Vi trenger fortsatt økonomer som kan analysere tall, forstå sammenhenger og ta beslutninger – enten det gjelder bedrifter, samfunn eller pensjonssystemer. Eksemplene er mange.

Derfor er oppgavesettet under en øving i nettopp dette:
- å bruke AI som verktøy  
- men samtidig forstå hva som kommer ut i andre enden  

Eksamen i dette kurset vil også teste deres evne til å tolke og forstå kode. Dette er altså en ferdighet dere trenger både til eksamen – og sannsynligvis i arbeidslivet.

----
### 🎓 Prøve-eksamen
Her vil det legges ut en ekstra prøve-eksamen, som er ment for repetisjon av Python lab. Les beskrivelsen i dokuementet.

<p><a href="oppgaver/BED1304___Prøveeksamen__øvelse_.pdf" target="_blank">Åpne prøveeksamen i ny fane</a></p>

**Obs:** Eksamen vil nok være vanskeligere enn denne prøve-eksamen. 

--- 
