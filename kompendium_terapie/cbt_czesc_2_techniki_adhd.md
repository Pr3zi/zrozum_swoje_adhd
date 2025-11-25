# CBT Kompendium dla ADHD - Część 2: Techniki ADHD

**Cognitive Behavioral Therapy - Praktyczne zastosowanie dla ADHD**

**Wersja:** 1.0
**Data:** 2025-01-22
**Sekcje:** 7-12 (Techniki i implementacja dla ADHD)

---

## 7. Dlaczego CBT dla ADHD? Mapowanie na 3 Główne Problemy

### Model IPO + 3 Problemy ADHD (przypomnienie)

**Model IPO:**
- **INPUT** - bodźce, myśli, emocje trafiające do mózgu
- **PROCESS** - funkcje wykonawcze (priorytety, decyzje)
- **OUTPUT** - działanie, realizacja

**3 Główne Problemy ADHD:**
1. **Chaos mentalny i natłok myśli** (INPUT overload)
2. **Emocje i RSD** (INPUT emocjonalny + słaba regulacja)
3. **Paraliż wykonawczy** (PROCESS → OUTPUT zablokowany)

---

### Problem 1: Chaos mentalny (INPUT Overload)

**Co się dzieje w ADHD:**
- 50 myśli jednocześnie
- Katastroficzne myśli dominują (negative bias)
- Working memory przeciążona
- "Nie mogę przestać myśleć o X"

**Jak CBT pomaga:**

#### **Thought Records - External Memory**

```
KROK 1: Wyrzuć myśli na papier/AI
"Mam 20 myśli. Wypisuję wszystkie."

KROK 2: Kategoryzuj
- Fakty vs Interpretacje
- Pilne vs Ważne vs Noise

KROK 3: Kwestionuj interpretacje
"Ta myśl to fakt czy katastrofa?"

KROK 4: Letting go
"Pozostałe myśli mogą poczekać/odpłynąć"
```

**Efekt:**
- INPUT overload → external memory (AI/papier)
- Chaos → struktura
- Working memory odciążona

---

### Problem 2: Emocje i RSD (INPUT Emocjonalny)

**Co się dzieje w ADHD:**
- **RSD** - nadwrażliwość na krytykę/odrzucenie
- **Mind reading** - "On myśli że jestem głupi"
- **Catastrophizing** - "To katastrofa, wszyscy mnie odrzucą"
- Emocjonalna reakcja 0→100 (brak gradacji)

**Jak CBT pomaga:**

#### **Reframing - 3 Neutralne Perspektywy**

**Sytuacja:** Kolega nie odpisał na wiadomość (3 godziny)

**Automatyczna myśl (RSD):**
"Jest na mnie zły. Już mnie nie lubi. Zrobiłem coś źle."

**CBT Reframing (3 neutralne):**
1. Jest zajęty (praca, spotkanie)
2. Nie widział wiadomości (notifications off)
3. Potrzebuje czasu na odpowiedź (myśli nad tym)

**Kluczowe:**
- **NIE pozytywne** ("na pewno cię kocha!") - ADHD brain nie uwierzy
- **Neutralne** ("mogło być X, Y lub Z") - realistyczne

---

#### **Check the Facts (Evidence-Based)**

```
KROK 1: Jaka jest myśl?
"Szef myśli że jestem niekompetentny"

KROK 2: Evidence FOR (dowody za)
- Raz skrytykował raport (ale potem pochwalił inny)
- Poprosił o rozmowę (ale to może być update)

KROK 3: Evidence AGAINST (dowody przeciw)
- Awansował mnie 6 miesięcy temu
- Powierzył mi ważny projekt
- Nigdy nie powiedział "jesteś niekompetentny"

KROK 4: Wniosek
"Brak dowodów na myśl. To RSD (mind reading), nie fakt."
```

---

### Problem 3: Paraliż wykonawczy (PROCESS → OUTPUT)

**Co się dzieje w ADHD:**
- "Nie mogę zacząć" (overwhelm)
- Perfectionism - "Musi być idealnie"
- All-or-nothing - "Albo wszystko, albo nic"
- Prokrastynacja → deadline panic

**Jak CBT pomaga:**

#### **Behavioral Activation - Action Before Motivation**

```
Tradycyjne myślenie:
Motywacja → Działanie → Rezultat

CBT dla ADHD:
Działanie → Dopamina → Motywacja → Więcej działania
```

**Protocol:**

**KROK 1: Kwestionuj myśl "Nie mam motywacji"**
- Myśl: "Nie mam motywacji do X"
- Fakt: "Motivation follows action" (nie odwrotnie)

**KROK 2: Micro-commitment**
- Nie: "Sprzątam całą kuchnię" (overwhelm)
- Tak: "Myję 2 naczynia" (2 minuty)

**KROK 3: Zrób najmniejszy krok**
- 2 naczynia → dopamina → momentum → 10 naczyń

**KROK 4: Nie oceniaj progress**
- "Tylko 2 naczynia?" = cognitive distortion (all-or-nothing)
- "2 naczynia = progress" = fakt

---

### Podsumowanie mapowania:

| Problem ADHD | Technika CBT | Efekt na Model IPO |
|--------------|--------------|---------------------|
| Chaos mentalny | Thought Records | INPUT overload → external memory |
| RSD, mind reading | Reframing (3 neutralne) | INPUT emocjonalny → kwestionowanie interpretacji |
| Catastrophizing | Check the Facts | Emocja vs fakt (evidence-based) |
| Paraliż wykonawczy | Behavioral Activation | PROCESS zablokowany → OUTPUT (działanie mimo braku motywacji) |
| Perfectionism | All-or-nothing challenge | "Idealnie vs wcale" → "Done > perfect" |

---

## 8. Techniki Gotowe do AI Implementation

### Technika 1: Thought Record (3-Column ADHD Version)

**Cel:** Wyrzucić myśli z głowy + kwestionować katastroficzne myśli

**Tradycyjny Thought Record:** 7 kolumn (overwhelm dla ADHD)

**ADHD-Adapted:** 3 kolumny

---

#### **AI Workflow - Thought Record**

```markdown
**INSTRUKCJA THOUGHT RECORD dla AI:**

Gdy użytkownik mówi "Myślę X i czuję się źle":

KROK 1: Zbierz dane (3 kolumny)

Zapytaj:
1. **Co się wydarzyło?** (sytuacja, fakty)
2. **Co pomyślałeś/aś?** (automatyczna myśl)
3. **Co czujesz?** (emocja + intensywność 1-10)

KROK 2: Wypełnij tabelę

| Co się stało? | Co pomyślałem? | Co czuję? |
|---------------|----------------|-----------|
| [Sytuacja] | [Automatyczna myśl] | [Emocja] X/10 |

KROK 3: Identyfikuj cognitive distortion

"Twoja myśl '[myśl]' to prawdopodobnie:"
- Catastrophizing? (najgorsze możliwe)
- All-or-nothing? (czarno-białe)
- Mind reading? (zakładasz co inni myślą)
- Overgeneralization? (ZAWSZE, NIGDY)

KROK 4: Check the Facts

"Sprawdźmy dowody:"

**Evidence FOR (za twoją myślą):**
[Lista dowodów]

**Evidence AGAINST (przeciw):**
[Lista dowodów]

**Wniosek:** "Czy myśl jest faktem czy interpretacją?"

KROK 5: Reframing (3 neutralne perspektywy)

"Jakie są inne wyjaśnienia (neutralne, nie pozytywne)?"
1. [Perspektywa 1]
2. [Perspektywa 2]
3. [Perspektywa 3]

KROK 6: Nowa emocja

"Jak teraz czujesz się na skali 1-10?"
```

---

#### **Przykład AI Dialog:**

**User:** "Szef napisał 'musimy porozmawiać' i panikuję."

**AI:**
"Rozumiem. Zróbmy Thought Record (3 kroki)."

**1. Co się stało?**
User: "Szef napisał email 'Musimy porozmawiać jutro o 10'"

**2. Co pomyślałeś?**
User: "Chce mnie zwolnić"

**3. Co czujesz?**
User: "Lęk 9/10, panika"

**AI:**
| Co się stało? | Co pomyślałem? | Co czuję? |
|---------------|----------------|-----------|
| Szef napisał "musimy porozmawiać jutro" | "Chce mnie zwolnić" | Lęk 9/10 |

**Twoja myśl "chce mnie zwolnić" to prawdopodobnie:**
- **Catastrophizing** (najgorszy możliwy scenariusz)
- **Mind reading** (zakładasz co myśli szef)

**Sprawdźmy dowody:**

**Evidence FOR:**
- Poprosił o rozmowę (ale to może być normalny update)

**Evidence AGAINST:**
- Awansował cię 6 miesięcy temu
- Powierzył ci projekt X (ważny)
- Nigdy nie mówił o problemach z twoją pracą
- "Musimy porozmawiać" ≠ "Jesteś zwolniony"

**Wniosek:** Brak dowodów na zwolnienie. To RSD/lęk (nie fakt).

**3 neutralne perspektywy:**
1. Chce omówić postęp projektu X (normalny update)
2. Ma pytania o raport (wyjaśnienie, nie krytyka)
3. Chce dać ci nowe zadanie (może awans?)

**Jak teraz czujesz się na skali 1-10?**
User: "Lęk 4/10"

**AI:** "Świetnie. Spadło z 9 do 4. To jest efekt reframingu."

---

### Technika 2: Behavioral Activation Schedule

**Cel:** Przełamać paraliż wykonawczy przez działanie (nie czekaj na motywację)

**AI Workflow:**

```markdown
**INSTRUKCJA BEHAVIORAL ACTIVATION dla AI:**

Gdy użytkownik mówi "Nie mam motywacji do X" / "Nie mogę zacząć":

KROK 1: Kwestionuj myśl "Potrzebuję motywacji"

"W CBT mówimy: **Motivation follows action** (nie odwrotnie)."
"Nie czekaj na motywację → zrób najmniejszy krok → motywacja przyjdzie."

KROK 2: Identify the task

"Co chcesz zrobić (ale nie masz motywacji)?"
User: "Napisać raport"

KROK 3: Break into SMALLEST step (2 min max)

"Jaki jest najmniejszy krok (2 minuty max)?"

**NIE:**
- "Napisać cały raport" (overwhelm)
- "Napisać wstęp" (nadal duże)

**TAK:**
- "Otworzyć dokument + napisać tytuł" (30 sek)
- "Napisać 1 zdanie" (1 min)

KROK 4: Commit to 2 minutes

"Zrób tylko ten krok (2 minuty). Potem możesz przestać."

KROK 5: After action - check

"Wykonałeś? Jak się czujesz?"

**Jeśli użytkownik zrobił:**
"Świetnie! Czy masz motywację zrobić kolejne 2 minuty?"
(Często: TAK - momentum się buduje)

**Jeśli nie:**
"OK. Co cię zablokowało? (Może krok był za duży?)"

KROK 6: Build momentum

2 min → 2 min → 2 min = 30 minut (ale zaczynasz od 2 min!)
```

---

### Technika 3: Reframing Generator (3 Neutralne Perspektywy)

**AI Workflow:**

```markdown
**INSTRUKCJA REFRAMING dla AI:**

Gdy użytkownik przedstawia katastroficzną myśl:

KROK 1: Identyfikuj automatyczną myśl

User: "Kolega nie odpisał, pewnie jest na mnie zły"

KROK 2: Label cognitive distortion

"Twoja myśl to prawdopodobnie:"
- **Mind reading** (zakładasz co myśli)
- **Catastrophizing** (najgorsze możliwe)

KROK 3: Wygeneruj 3 neutralne perspektywy

**WAŻNE:**
- **NIE pozytywne** ("na pewno cię kocha!")
- **Neutralne** ("mogło być X, Y lub Z")
- **Realistyczne** (ADHD brain musi uwierzyć)

**Format:**

"Oto 3 neutralne wyjaśnienia (każde równie prawdopodobne):"

1. **[Perspektywa 1 - zajęty]**
   "Jest zajęty (praca, spotkanie, osobiste sprawy)"

2. **[Perspektywa 2 - nie widział]**
   "Nie widział wiadomości (notifications off, zgubił w chaosie)"

3. **[Perspektywa 3 - potrzebuje czasu]**
   "Potrzebuje czasu na odpowiedź (przemyśla, odpisze później)"

KROK 4: Pytanie kontrolne

"Która perspektywa jest najbardziej prawdopodobna?"
(Często: 1 lub 2, nie katastroficzna myśl!)

KROK 5: Nowa emocja

"Jak teraz czujesz się myśląc o tych 3 perspektywach?"
User: "Mniej lęku, bardziej spokojnie"
```

---

### Technika 4: All-or-Nothing Challenge

**Cel:** Przełamać perfectionism ("idealnie vs wcale")

**AI Workflow:**

```markdown
**INSTRUKCJA ALL-OR-NOTHING CHALLENGE dla AI:**

Gdy użytkownik mówi "Musi być perfekcyjne" / "Albo dobrze, albo wcale":

KROK 1: Identyfikuj all-or-nothing thinking

"Słyszę: 'Musi być [X]'. To brzmi jak **all-or-nothing thinking**."
"W ADHD często: 'Albo perfekcyjnie, albo wcale'."

KROK 2: Challenge the thought

"Czy naprawdę jest tylko 0% lub 100%?"
"Co z 50%? 70%? 'Done' ale nie 'perfect'?"

KROK 3: Континuum (nie dychotomia)

Narysuj kontinuum:

```
0% ---------- 50% ---------- 70% ---------- 100%
Nic      Coś zrobione    Dobrze     Perfekcyjnie
```

"Gdzie jest 'wystarczająco dobre' dla tego zadania?"
(Często: 70%, nie 100%)

KROK 4: Behavioral experiment

"Spróbujmy eksperyment:"
1. Zrób zadanie na 70% (nie 100%)
2. Wyślij/dostarcz
3. Obserwuj reakcję

"Czy ktoś powiedział 'to za mało'?"
(Często: NIE - 70% wystarczy!)

KROK 5: Reframe "Done > Perfect"

"W ADHD: **Done is better than perfect**."
"Perfekcja = prokrastynacja (paraliż)."
"70% dzisiaj > 100% nigdy."
```

---

## 9. Techniki Skrócone dla ADHD

### Dlaczego skrócone?

**Problem z tradycyjnym CBT:**
- Thought Record (7 kolumn) = overwhelm
- Długie sesje (60 min) = attention span problem
- Skomplikowane protokoły = working memory overload

**ADHD needs:**
- Max 3 kroki
- Quick wins (<5 min)
- Konkretne action items

---

### Thought Record → "FER" (3 kroki)

**Tradycyjny:** 7 kolumn (Sytuacja, Emocja, Auto-myśl, Dowody za, Dowody przeciw, Alternatywna myśl, Nowa emocja)

**ADHD Version: FER**

```
F - Fact (Co się NAPRAWDĘ stało?)
E - Emotion (Co czuję? X/10)
R - Reframe (3 neutralne perspektywy)
```

**Przykład:**

**F:** Szef napisał "musimy porozmawiać"
**E:** Lęk 9/10
**R:** (1) Update projektu, (2) Pytania o raport, (3) Nowe zadanie

**Czas:** 2 minuty (zamiast 15 min z 7 kolumnami)

---

### Behavioral Activation → "2-MIN RULE"

**Tradycyjny:** Activity scheduling (plan całego tygodnia), long-term goals

**ADHD Version: 2-MIN RULE**

```
Nie mam motywacji → Zrób 2 minuty → STOP (lub kontynuuj jeśli chcesz)
```

**Protocol:**

1. "Jaki najmniejszy krok (2 min)?"
2. Zrób
3. Świętuj (dopamina!)
4. "Chcę kolejne 2 min?" (często: TAK - momentum)

**Przykład:**
- Nie: "Posprzątam kuchnię" (45 min, overwhelm)
- Tak: "Myję 2 naczynia" (2 min, achievable)

---

### Reframing → "QUICK 3"

**Tradycyjny:** Evidence for/against (długi proces, wiele kroków)

**ADHD Version: QUICK 3**

```
Katastroficzna myśl → 3 neutralne perspektywy (30 sekund z AI)
```

**Prompt dla AI:**
"Myślę [X]. Daj mi 3 neutralne perspektywy."

**Output (instant):**
1. [Perspektywa 1]
2. [Perspektywa 2]
3. [Perspektywa 3]

**Czas:** 30 sekund (zamiast 10 min thought record)

---

### All-or-Nothing → "70% RULE"

**Tradycyjny:** Długa dyskusja o perfekcjonizmie, kontinuum

**ADHD Version: 70% RULE**

```
"Musi być idealnie" → "70% is enough"
```

**Protocol:**

1. "Czy musi być 100%?" (pytanie)
2. "70% wystarczy" (fakt)
3. Zrób na 70% → dostarcz → obserwuj (nikt nie krytykuje!)

**Mantra:**
> "Done at 70% > Perfect never"

---

## 10. Common Pitfalls w ADHD (Pułapki)

### Pułapka 1: "Myślenie pozytywne" (Toxic Positivity)

**Błędna interpretacja CBT:**
"CBT = myśl pozytywnie!" ("Wszystko będzie dobrze!")

**Prawda:**
CBT = myśl **realistycznie** (nie pozytywnie, nie negatywnie)

**Przykład:**

❌ **ŹLE (toxic positivity):**
Myśl: "Egzamin będzie trudny"
"Pozytywnie": "Na pewno zdasz! Wszystko będzie super!"
→ ADHD brain: "To brednie, nie wierzę"

✅ **DOBRZE (CBT realistycznie):**
Myśl: "Egzamin będzie trudny"
Reframing: "Egzamin będzie trudny. Przygotowałem się. Mogę nie zdać (możliwość), ale mogę też zdać. Zrobię co w mojej mocy."
→ ADHD brain: "To realistyczne, mogę w to uwierzyć"

**Wniosek:** Neutralne > Pozytywne (dla ADHD)

---

### Pułapka 2: "CBT rozwiąże ADHD"

**Błąd:**
"Nauczę się CBT → ADHD zniknie → odstawię leki"

**Prawda:**
CBT ≠ cure dla ADHD. To **narzędzie wsparcia**.

**CBT pomaga:**
- Negative self-talk → reframing
- Prokrastynacja → behavioral activation
- Lęk → check the facts

**CBT NIE pomaga:**
- Uwaga (attention span) → leki pomagają
- Hyperaktywność → leki + lifestyle
- Working memory → external systems (AI, noty, alarmy)

**Wniosek:** CBT + leki + systemy = comprehensive approach

---

### Pułapka 3: "Thought Records = Journaling"

**Błąd:**
"Będę pisał myśli w dzienniku" (długie wypracowania)

**Prawda:**
Thought Records = **structured** (nie freeform journaling)

**Journaling (freeform):**
"Dzisiaj czułem się źle. Szef był niemiły. Nie wiem co dalej..." (rumination)

**Thought Record (structured):**
| Fakt | Myśl | Reframe |
|------|------|---------|
| Szef skrytykował raport | "Jestem do niczego" | "Raport był słaby, nie ja" |

**Wniosek:** Struktura > Freeform (dla ADHD - mniej rumination)

---

### Pułapka 4: "Muszę robić Thought Records codziennie"

**Błąd:**
"Homework: Thought Record każdego dnia" (konsystencja = ADHD nightmare)

**Prawda:**
Thought Records **when needed** (nie schedule)

**Protocol:**

**UŻYJ Thought Record gdy:**
- Intensywna emocja (7-10/10)
- Katastroficzna myśl blokuje działanie
- Powtarzający się wzorzec myśli

**NIE używaj gdy:**
- "Bo trzeba" (compliance dla compliance)
- Czujesz się OK (niepotrzebne)

**Wniosek:** As-needed > Daily (dla ADHD flexibility)

---

### Pułapka 5: "Evidence against = ignorowanie rzeczywistości"

**Błąd:**
Myśl: "Projekt poszedł źle"
Evidence against: "To nie było aż TAK źle" (minimalizowanie)

**Prawda:**
Evidence against ≠ ignorowanie faktów

**Przykład:**

**Fakt:** Projekt poszedł źle (deadline missed, błędy)

❌ **ŹLE (ignorowanie):**
"To nie było źle, robię sobie z tego sprawę" (denial)

✅ **DOBRZE (CBT):**
Evidence AGAINST myśli "**Jestem do niczego**":
- Projekt poszedł źle (FAKT - akceptuję)
- Ale: ukończyłem 10 innych projektów sukcesem
- 1 fail ≠ "jestem do niczego" (overgeneralization)

**Wniosek:** Akceptuj fakt + kwestionuj interpretację

---

## 11. Integracja z 4 C's of Motivation

### 4 C's (przypomnienie)

**ADHD brain motywują:**
1. **Captivate** - zainteresowanie
2. **Create** - nowość, kreatywność
3. **Compete** - wyzwanie
4. **Complete** - deadline, urgency

---

### CBT Techniques przez pryzmat 4 C's

#### 1. **Captivate - Jak uczynić CBT interesującym?**

**Problem:** Thought Records = nudne (ADHD: zzz)

**Rozwiązanie - Gamifikacja:**

**"Cognitive Distortion Bingo":**
- Track ile razy złapałeś cognitive distortion w tydzień
- Bingo card: Catastrophizing, All-or-nothing, Mind reading, itp.
- Pełna karta = reward (social proof w społeczności)

**Storytelling (Captivate):**
- Nie: "Thought Records pomagają"
- Tak: "Kuba użył Thought Record gdy RSD uderzyło - lęk spadł z 9 do 3 w 5 minut. Chcesz zobaczyć jak?"

---

#### 2. **Create - Nowość w CBT**

**Problem:** Te same techniki każdego dnia (boredom)

**Rozwiązanie - Rotacja:**

**"Technique of the Week":**
- Tydzień 1: Thought Records (FER)
- Tydzień 2: Behavioral Activation (2-min rule)
- Tydzień 3: Reframing (Quick 3)
- Tydzień 4: All-or-nothing challenge (70% rule)

**Custom tworzenie:**
"Stwórz własną wersję Thought Record" (personalizacja = Create)

---

#### 3. **Compete - Wyzwanie**

**CBT Challenges:**

**7-Day Reframing Challenge:**
- Dzień 1-7: Każdego dnia 1 katastroficzna myśl → reframing
- Leaderboard: Kto zrobił najwięcej reframingów?
- Badge: "Reframing Master" (7 dni z rzędu)

**"Beat Your Record":**
"Ostatnio twój Thought Record zajął 10 min. Czy możesz zrobić w 5 min?"

---

#### 4. **Complete - Deadline/Urgency**

**Problem:** CBT practice nie ma deadline (ADHD odkłada)

**Rozwiązanie - Artificial Deadlines:**

**Daily Check-in (deadline: 21:00):**
"Użyłeś dzisiaj Thought Record? Wyślij do społeczności (deadline: dziś 21:00)"

**Weekly Challenge (deadline: niedziela):**
"3 Thought Records w tym tygodniu. Deadline: niedziela 20:00."

**30-Day CBT Challenge:**
Certyfikat completion (social proof + dopamina)

---

## 12. Case Studies z ADHD Community

### Case Study 1: Ania, 35, ADHD + Lęk - Catastrophizing

**Profil:**
- ADHD combined + GAD (generalized anxiety disorder)
- Leki: Vyvanse 40mg
- Główny problem: **Catastrophizing** - każda trudność = koniec świata

**Sytuacja:**

Email od szefa: "Musimy porozmawiać o raporcie."

**Przed CBT:**
- **Myśl:** "Chce mnie zwolnić. Raport był katastrofą. Stracę pracę. Nie znajdę nowej. Będę bezdomna."
- **Emocja:** Panika 10/10
- **Reakcja:** Nie spała całą noc, rozważała zmianę pracy, 3 dni rumination

**Po CBT (Thought Record + Check the Facts):**

**KROK 1: Thought Record (FER)**

**F (Fact):** "Szef napisał 'musimy porozmawiać o raporcie'"
**E (Emotion):** Lęk 9/10
**R (Reframe):** (1) Chce wyjaśnień, (2) Ma pytania, (3) Chce poprawek

**KROK 2: Check the Facts**

**Evidence FOR "zwolni mnie":**
- Poprosił o rozmowę (ale to może być update)

**Evidence AGAINST:**
- Nigdy nie mówił o zwolnieniu
- Awansował mnie rok temu
- Powierzył mi inne projekty (po tym raporcie!)
- "Porozmawiać o raporcie" ≠ "Jesteś zwolniona"

**Wniosek:** Brak dowodów. To catastrophizing (nie fakt).

**KROK 3: Behavioral Experiment**

- Poszła na spotkanie
- Szef: "Mam 3 pytania o dane w raporcie. Możesz wyjaśnić?"
- 15 min rozmowy → wyjaśniła → szef: "Dzięki, teraz rozumiem"

**Rezultat:**
- **Fakt:** To był normalny update (nie zwolnienie!)
- **Lekcja:** Catastrophizing = false alarm (99% przypadków)

**Kluczowy insight:**
"Przez lata każdy email od szefa = panika. CBT pokazało: sprawdzaj fakty PRZED paniką."

**3 miesiące po CBT:**
- Catastrophizing: 10x/tydzień → 2x/tydzień
- Lęk: GAD-7 score 15 → 7 (severe → mild)
- Sen: 5h (rumination) → 7h (spokój)

---

### Case Study 2: Tomek, 28, ADHD-PI - Perfectionism & Prokrastynacja

**Profil:**
- ADHD-PI (primarily inattentive)
- Bez leków (próbował, skutki uboczne)
- Główny problem: **Perfectionism** - "Musi być idealnie" → paraliż

**Sytuacja:**

Prezentacja za tydzień. Tomek nie zaczął (paraliż).

**Przed CBT:**
- **Myśl:** "Prezentacja musi być perfekcyjna. Inaczej wszyscy pomyślą że jestem niekompetentny."
- **Emocja:** Lęk 8/10, overwhelm
- **Reakcja:** Prokrastynacja (scrollowanie social media), prezentacja w last minute (panika, niska jakość)

**Po CBT (All-or-Nothing Challenge + Behavioral Activation):**

**KROK 1: All-or-Nothing Challenge**

AI: "Słyszę 'musi być perfekcyjna'. To all-or-nothing thinking."
"Czy naprawdę 0% lub 100%? Co z 70%?"

Kontinuum:
```
0% -------- 70% -------- 100%
Nic      Wystarczająco  Perfekcyjnie
              dobre
```

"70% wystarczy. Done > Perfect."

**KROK 2: Behavioral Activation (2-min rule)**

Tomek: "Nie mam motywacji"

AI: "Motivation follows action. Jaki najmniejszy krok (2 min)?"

Tomek: "Otworzyć PowerPoint + tytuł slajdu"

**Rezultat:**
- 2 min (tytuł) → 10 min (outline) → 30 min (3 slajdy)
- Momentum zbudowany!

**KROK 3: Behavioral Experiment (70% rule)**

- Tomek przygotował prezentację na 70% (nie 100%)
- Wystarczająco dobra (dane + visualizacje), ale nie "perfekcyjna"
- Prezentacja → reakcja: "Świetna robota!" (nikt nie powiedział "za mało")

**Kluczowy insight:**
"70% wystarczy. Nikt nie wymaga perfekcji. Perfekcjonizm = prokrastynacja."

**2 miesiące po CBT:**
- Prokrastynacja: 80% zadań last-minute → 30%
- Perfectionism: "Musi być idealnie" → "70% is enough"
- Projekty ukończone: +50% (bo zaczyna wcześniej)

---

### Case Study 3: Kasia, 42, ADHD + Depresja - Negative Self-Talk

**Profil:**
- ADHD combined + depression (mild)
- Leki: Concerta 54mg + SSRI
- Główny problem: **Negative self-talk** - "Jestem do niczego", "Jestem leniwa"

**Sytuacja:**

Zapomniała o spotkaniu z koleżanką.

**Przed CBT:**
- **Myśl:** "Jestem okropna. ZAWSZE zapominam. Jestem do niczego jako przyjaciel."
- **Emocja:** Wstyd 10/10, depresja
- **Reakcja:** Unikanie koleżanki przez tydzień, rumination, spadek nastroju

**Po CBT (Overgeneralization Challenge + Self-Compassion Reframe):**

**KROK 1: Identyfikuj cognitive distortion**

AI: "Twoja myśl 'ZAWSZE zapominam' to **overgeneralization**."
"Czy to prawda ZAWSZE?"

**KROK 2: Evidence against**

**Evidence FOR "ZAWSZE zapominam":**
- Zapomniałam o tym spotkaniu (1 przypadek)

**Evidence AGAINST:**
- Pamiętałam o 20 innych spotkaniach w tym miesiącu
- Pamiętam urodziny przyjaciół
- Pamiętam o pracy (większość czasu)

**Wniosek:** Nie "ZAWSZE". 1 przypadek ≠ zawsze.

**KROK 3: Self-Compassion Reframe**

Zamiast: "Jestem do niczego"

CBT Reframe:
"Zapomniałam. Mam ADHD (słaba working memory). To nie znaczy że jestem do niczego. Mogę przeprosić + ustawić reminder."

**KROK 4: Behavioral Activation (not avoidance)**

Opposite action: Zamiast unikać → napisać do koleżanki

Wiadomość: "Przepraszam że zapomniałam. Mam ADHD i czasami mi się zdarza. Możemy przełożyć?"

**Rezultat:**
- Koleżanka: "Spoko! Rozumiem. Jutro OK?"
- Brak katastrofy (którą wyobrażała)

**Kluczowy insight:**
"Zapomniałam ≠ jestem do niczego. To ADHD, nie moja wartość jako osoby."

**3 miesiące po CBT:**
- Negative self-talk: 50x/miesiąc → 10x/miesiąc
- Self-compassion: 2/10 → 7/10
- Depresja: BDI-II 16 → 8 (mild → minimal)

---

### Case Study 4: Marek, 31, ADHD + Social Anxiety - Mind Reading

**Profil:**
- ADHD + social anxiety
- Leki: Vyvanse 30mg
- Główny problem: **Mind reading** - "Wszyscy myślą że jestem głupi"

**Sytuacja:**

Na spotkaniu zadał pytanie. Jeden kolega się uśmiechnął.

**Przed CBT:**
- **Myśl:** "Uśmiechnął się bo pytanie było głupie. Wszyscy myślą że jestem głupi."
- **Emocja:** Wstyd 9/10, lęk społeczny
- **Reakcja:** Nie zabierał głosu przez resztę spotkania, unikał kolegów przez 2 dni

**Po CBT (Mind Reading Challenge + Behavioral Experiment):**

**KROK 1: Identyfikuj Mind Reading**

AI: "Twoja myśl 'wszyscy myślą że jestem głupi' to **mind reading**."
"Skąd wiesz co myślą? Czy ktoś to powiedział?"

Marek: "Nie, ale widziałem jak się uśmiechnął"

AI: "Uśmiech = fakt. 'Myśli że jestem głupi' = interpretacja (nie fakt)."

**KROK 2: Reframing (3 neutralne)**

"Jakie są inne wyjaśnienia uśmiechu?"
1. Pomyślał o czymś śmiesznym (nie związanym z tobą)
2. Uśmiechnął się przyjaźnie (nie sarkastycznie)
3. Pytanie było dobre (uśmiech = uznanie)

**KROK 3: Behavioral Experiment**

"Sprawdźmy czy twoja myśl jest prawdą."

**Experiment:** Zapytaj kolegę (bezpośrednio)
Marek (po spotkaniu): "Hej, zauważyłem że się uśmiechnąłeś gdy zadałem pytanie. Wszystko OK?"

Kolega: "Co? Aa, to byłem szczęśliwy że ktoś zadał to pytanie, bo sam się zastanawiałem!"

**Rezultat:**
- **Fakt:** Uśmiech był pozytywny (nie sarkastyczny)
- **Lekcja:** Mind reading = false alarm (99%)

**Kluczowy insight:**
"Nie wiem co ludzie myślą dopóki nie zapytam. Założenia = mind reading (często błędne)."

**2 miesiące po CBT:**
- Mind reading: 20x/tydzień → 5x/tydzień
- Behavioral experiments: 0 → 15 (sprawdzanie założeń)
- Social anxiety: Mówi na spotkaniach (wcześniej: cisza)

---

### Case Study 5: Zosia, 26, ADHD + RSD - Emotional Reasoning

**Profil:**
- ADHD-C + RSD (severe)
- Leki: Concerta 36mg
- Główny problem: **Emotional reasoning** - "Czuję się głupio → jestem głupia"

**Sytuacja:**

Na pierwszym dniu w nowej pracy czuła się przytłoczona.

**Przed CBT:**
- **Myśl:** "Czuję się głupio. To znaczy że jestem głupia. Nie nadaję się do tej pracy."
- **Emocja:** Wstyd 10/10, lęk
- **Reakcja:** Rozważała rezygnację pierwszego dnia

**Po CBT (Emotional Reasoning Challenge + Check the Facts):**

**KROK 1: Identyfikuj Emotional Reasoning**

AI: "Twoja myśl 'czuję się głupio → jestem głupia' to **emotional reasoning**."
"Emocja ≠ fakt. Możesz CZUĆ się X, ale to nie znaczy że JESTEŚ X."

**KROK 2: Separate Emotion from Fact**

**Emocja:** "Czuję się głupio" (prawda - to czujesz)
**Fakt?** "Jestem głupia" (czy to fakt?)

**Evidence:**
- Fakt: Pierwszy dzień (wszystko nowe, overwhelm = normalny)
- Fakt: Ukończyłam studia, dostałam tę pracę (nie byłabym "głupia")
- Emocja: Czuję się głupio (feeling ≠ being)

**KROK 3: Reframing**

Zamiast: "Czuję się głupio → jestem głupia"

CBT: "Czuję się głupio (pierwszy dzień, overwhelm). To nie znaczy że jestem głupia. To normalne czuć się tak w nowej sytuacji."

**KROK 4: Behavioral Experiment**

"Zostań 1 tydzień. Sprawdź: Czy faktycznie jesteś 'głupia' (nie dajesz rady) czy to tylko pierwsze dni?"

**Rezultat (po tygodniu):**
- Zosia: "Nauczyłam się systemu. Teraz jest łatwiej."
- Szef: "Świetnie sobie radzisz!" (pozytywny feedback)
- **Fakt:** Nie była "głupia" - to był tylko overwhelm pierwszego dnia

**Kluczowy insight:**
"Emocja ≠ fakt. Mogę czuć się X, ale to nie znaczy że jestem X."

**1 miesiąc po CBT:**
- Emotional reasoning: Rozpoznaje ("to emocja, nie fakt")
- RSD: Nadal boli, ale używa CBT reframing (spadek intensywności)
- Praca: Nie zrezygnowała, czuje się kompetentna

---

## ✅ Podsumowanie Części 2

**W tej części nauczyłeś/aś się:**

1. **Mapowanie CBT na 3 problemy ADHD:**
   - Chaos mentalny → Thought Records (external memory)
   - RSD/emocje → Reframing (3 neutralne), Check the Facts
   - Paraliż wykonawczy → Behavioral Activation (action before motivation)

2. **4 Techniki ready-to-AI:**
   - Thought Record (3-column ADHD version)
   - Behavioral Activation Schedule
   - Reframing Generator (3 neutralne perspektywy)
   - All-or-Nothing Challenge

3. **ADHD-adapted versions:**
   - Thought Record → FER (Fact, Emotion, Reframe)
   - Behavioral Activation → 2-MIN RULE
   - Reframing → QUICK 3
   - All-or-nothing → 70% RULE

4. **5 Common Pitfalls:**
   - Toxic positivity (neutralne > pozytywne)
   - CBT nie rozwiąże ADHD (to wsparcie, nie cure)
   - Thought Records ≠ journaling (struktura!)
   - As-needed > Daily (flexibility dla ADHD)
   - Evidence against ≠ ignorowanie faktów

5. **Integracja z 4 C's:**
   - Captivate (gamifikacja, storytelling)
   - Create (technique of the week, customizacja)
   - Compete (challenges, beat your record)
   - Complete (daily/weekly deadlines)

6. **5 Case Studies:**
   - Ania (catastrophizing → thought record)
   - Tomek (perfectionism → 70% rule)
   - Kasia (negative self-talk → overgeneralization challenge)
   - Marek (mind reading → behavioral experiments)
   - Zosia (emotional reasoning → separate emotion from fact)

---

**Następny plik:** `cbt_czesc_3_implementacja.md` (sekcje 13-18)
**Status:** Część 2 ukończona ✅
