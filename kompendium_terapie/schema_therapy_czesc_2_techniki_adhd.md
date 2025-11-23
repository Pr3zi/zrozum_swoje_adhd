# Schema Therapy Kompendium dla ADHD - Część 2: Techniki ADHD

**Schema Therapy - Praktyczne zastosowanie dla ADHD**

**Wersja:** 1.0
**Data:** 2025-01-22
**Sekcje:** 7-12 (Techniki i implementacja dla ADHD)

---

## 7. Dlaczego Schema Therapy dla ADHD? Mapowanie na 3 Główne Problemy + Model IPO

### Model IPO + 3 Problemy ADHD (przypomnienie)

**Model IPO:**
- **INPUT** - bodźce, myśli, emocje
- **PROCESS** - funkcje wykonawcze
- **OUTPUT** - działanie, realizacja

**3 Główne Problemy ADHD:**
1. **Chaos mentalny** (INPUT overload)
2. **Emocje i RSD** (INPUT emocjonalny + słaba regulacja)
3. **Paraliż wykonawczy** (PROCESS → OUTPUT zablokowany)

---

### Problem 1: Chaos mentalny → Schema Defectiveness

**Co się dzieje w ADHD:**
- Natłok myśli
- Ale często dominuje: **"Jestem wadliwy/do niczego"** (Schema Defectiveness)
- To nie tylko myśl - to **głęboka core belief**

**Jak Schema Therapy pomaga:**

**Rozpoznanie schematu:**
```
Myśl: "Jestem do niczego"
Nie jest to tylko automatic thought (CBT)
To Schema Defectiveness (głęboka, z dzieciństwa)
```

**Schema Flashcard:**
- **Schema says:** "Jestem wadliwy"
- **Reality:** Mam ADHD (neurobiologia ≠ wadliwość)
- **Evidence against:** [lista sukcesów, nawet małych]

**Healthy Adult Mode:**
- "Vulnerable Child słyszał to latami ('jesteś leniwy')."
- "Ale Healthy Adult wie: to była trauma, nie prawda."

---

### Problem 2: RSD (Emocje) → Schema Abandonment/Defectiveness aktywowane

**Co się dzieje w ADHD:**
- **RSD** = nadwrażliwość na odrzucenie/krytykę
- Reakcja 0→100

**Schema Theory wyjaśnia RSD:**

**Trigger:** Kolega nie odpisał

**Schema aktywowane:**
- **Abandonment:** "Wszyscy mnie opuszczą"
- **Defectiveness:** "Jestem wadliwy, dlatego nie chce ze mną rozmawiać"

**Mode Cycle:**
```
VULNERABLE CHILD MODE aktywny
"Zostanę sam, nikt mnie nie kocha" (Schema Abandonment)
    ↓
CRITICAL PARENT MODE
"Bo jesteś wadliwy, dziwny, nienormalny!"
    ↓
DETACHED PROTECTOR MODE (coping)
Unikanie (nie odpisuję, wycofuję się)
```

**Jak Schema Therapy pomaga:**

**Mode Work:**
```
KROK 1: Rozpoznaj Mode
"Vulnerable Child jest aktywny (czuję ból odrzucenia)"

KROK 2: Healthy Adult chroni
"To Schema Abandonment aktywowane (nie fakt)."
"Kolega może być zajęty (neutral explanation)."

KROK 3: Walidacja + Action
"Vulnerable Child, to boli (OK czuć).
Ale nie działamy ze schematu (unikanie).
Działamy zdrowo: czekamy 24h lub pytamy bezpośrednio."
```

---

### Problem 3: Paraliż wykonawczy → Schema Failure (Overcompensation lub Avoidance)

**Co się dzieje w ADHD:**
- "Nie mogę zacząć"
- Często = **Schema Failure** (Coping: Avoidance lub Overcompensation)

**Mechanizm:**

**Schema:** Failure ("Jestem nieudacznikiem")

**Coping Style A - Avoidance:**
"Jeśli nie zacznę, nie zafailuję" → Prokrastynacja

**Coping Style B - Overcompensation:**
"Muszę być perfekcyjny (żeby NIE być nieudacznikiem)" → Paraliż

**Jak Schema Therapy pomaga:**

**Rozpoznanie Coping Style:**
```
Prokrastynacja = Avoidance Coping (dla Schema Failure)
Perfectionism = Overcompensation (dla Schema Failure)
```

**Healthy Coping:**
```
KROK 1: "Rozpoznaję Schema Failure aktywowane"

KROK 2: "Vulnerable Child boi się porażki (to OK)"

KROK 3: "Healthy Adult: Mogę robić błędy i nadal być OK.
Done > Perfect. Zacznę mimo strachu."

KROK 4: Behavioral Experiment
Zrób zadanie na 70% → zobacz: nikt nie mówi "nieudacznik"
```

---

### Podsumowanie mapowania:

| Problem ADHD | Schema | Schema Therapy Approach | Efekt na IPO |
|--------------|--------|-------------------------|--------------|
| Chaos mentalny + "jestem do niczego" | Defectiveness | Schema Flashcard, Healthy Adult | INPUT: Myśli ≠ core belief (rozdzielenie) |
| RSD (nadwrażliwość) | Abandonment, Defectiveness | Mode Work (Healthy Adult chroni Vulnerable Child) | INPUT emocjonalny: Schema aktywowane (nie fakt) |
| Paraliż wykonawczy | Failure (avoidance/overcompensation) | Rozpoznanie Coping, Healthy Coping | PROCESS→OUTPUT: Działanie mimo schematu |

---

## 8. Techniki Gotowe do AI Implementation

### Technika 1: Quick Mode Check-In (3 pytania, 2 min)

**Cel:** Rozpoznać który Schema Mode jest aktywny "tu i teraz"

**Tradycyjne Mode Work:** Długie, skomplikowane (10+ modów)

**ADHD Version: Quick Mode Check-In (3 pytania)**

---

#### **AI Workflow - Quick Mode Check-In**

```markdown
**INSTRUKCJA QUICK MODE CHECK-IN dla AI:**

Gdy użytkownik zgłasza trudną emocję:

KROK 1: Zapytaj 3 pytania

**Pytanie 1: Co czujesz?**
"Nazwij emocję: lęk, wstyd, złość, smutek, pustkę?"

**Pytanie 2: Co myślisz o sobie w tej chwili?**
(To identyfikuje schema)
- "Jestem wadliwy" → Schema Defectiveness
- "Jestem nieudacznikiem" → Schema Failure
- "Zostanę sam" → Schema Abandonment
- "Nie dam rady" → Schema Dependence/Incompetence

**Pytanie 3: Co chcesz zrobić?**
(To identyfikuje coping style)
- "Ukryć się, unikać" → Avoidance
- "Być perfekcyjnym" → Overcompensation
- "Poddać się" → Surrender

KROK 2: Identyfikuj Mode

Na podstawie odpowiedzi:

**Jeśli czuje: lęk, wstyd + myśli "jestem wadliwy" + chce się ukryć**
→ **VULNERABLE CHILD MODE** (Schema Defectiveness aktywne)

**Jeśli czuje: złość na siebie + myśli "jesteś do niczego!"**
→ **CRITICAL PARENT MODE**

**Jeśli czuje: odrętwienie + chce unikać**
→ **DETACHED PROTECTOR MODE**

KROK 3: Aktywuj Healthy Adult Mode

**Format:**

"Rozpoznaję: **[Mode Name]** jest aktywny."

**Jeśli Vulnerable Child:**
"Vulnerable Child, rozumiem że to boli. [Schema Name] mówi '[schema message]'.
Ale Healthy Adult wie: to schema (nie prawda o tobie)."

**Jeśli Critical Parent:**
"Critical Parent atakuje. Ale te słowa pochodzą z [dzieciństwa/traumy].
Nie są prawdą. Healthy Adult mówi STOP."

**Jeśli Detached Protector:**
"Detached Protector chce cię chronić (unikanie).
Ale unikanie wzmacnia schema. Healthy Adult: możemy zrobić mały krok."

KROK 4: Healthy Adult Action

"Co Healthy Adult może zrobić TERAZ?"
- Waliduj Vulnerable Child ("To OK czuć")
- Ogranicz Critical Parent ("To nieprawda")
- Konstruktywna akcja (nie unikanie)
```

---

#### **Przykład AI Dialog:**

**User:** "Czuję się okropnie. Szef skrytykował raport."

**AI Quick Mode Check-In:**

**Q1: Co czujesz?**
User: "Wstyd, chcę się schować"

**Q2: Co myślisz o sobie?**
User: "Że jestem do niczego, jestem nieudacznikiem"

**Q3: Co chcesz zrobić?**
User: "Unikać szefa, rozważam zmianę pracy"

**AI:**
"Rozpoznaję: **VULNERABLE CHILD MODE** aktywny.

Schema: **Failure** ('Jestem nieudacznikiem')
Coping: **Avoidance** (chcesz unikać)

**Healthy Adult do Vulnerable Child:**
'Rozumiem że to boli. Słyszałeś/aś to wiele razy w dzieciństwie ('jesteś nieudacznikiem').
Ale to Schema Failure mówi (nie prawda o tobie).
Raport był słaby (fakt) ≠ Ty jesteś nieudacznikiem (schema).'

**Healthy Adult Action:**
Zamiast unikać (Detached Protector):
1. Popraw raport (konstruktywnie)
2. Zapytaj szefa o feedback (konkretny)
3. To nie zmiana pracy (ucieczka), tylko nauka"

User: "Czuję się lepiej. Vulnerable Child nadal boli, ale wiem że to schema."

---

### Technika 2: Micro Imaginal Rescripting (15 min wersja)

**Cel:** "Przepisać" traumatyczne wspomnienie z dzieciństwa

**Tradycyjne Imaginal Rescripting:** 60-90 min (za długo dla ADHD)

**ADHD Version: Micro Rescripting (15 min)**

---

#### **AI Workflow - Micro Imaginal Rescripting**

```markdown
**INSTRUKCJA MICRO RESCRIPTING dla AI:**

Gdy użytkownik zgłasza recurring schema ("Jestem wadliwy" pojawia się ciągle):

KROK 1: Identify Schema Origin

"Skąd pochodzi to przekonanie 'Jestem wadliwy'?"
"Czy pamiętasz moment z dzieciństwa, gdy usłyszałeś/aś to po raz pierwszy?"

User przykład: "Tak, nauczyciel krzyczał 'Jesteś leniwy!' przed całą klasą (8 lat)"

KROK 2: Brief Memory Recall (2 min)

"Zamknij oczy (lub wyobraź sobie). Jesteś z powrotem w klasie, 8 lat."
"Co widzisz? Co słyszysz? Co czujesz?"

User: "Widzę nauczyciela, czerwony ze złości. Słyszę: 'Jesteś leniwy!'. Czuję wstyd, wszyscy patrzą."

KROK 3: Introduce Adult Self (5 min)

"Teraz wyobraź sobie: **Dorosły Ty** wchodzi do tej klasy."
"Dorosły Ty wie prawdę: to dziecko ma ADHD (nie jest leniwe)."

"Co Dorosły Ty mówi nauczycielowi?"

**Przykłady (AI może sugerować):**
- "STOP! To dziecko ma ADHD, nie jest leniwe!"
- "Nie masz prawa tak mówić do dziecka!"
- "Wyjdź z tej klasy. Ja się zajmę tym dzieckiem."

KROK 4: Reparenting (5 min)

"Dorosły Ty podchodzi do Dziecka (8-letnie Ty)."
"Co Dorosły Ty mówi do Dziecka?"

**Przykłady:**
- "Nie jesteś leniwy. Masz ADHD. To neurobiologia."
- "Kocham cię. Jesteś OK tak jak jesteś."
- "Nauczyciel się mylił. To nie twoja wina."

"Dorosły Ty przytula Dziecko. Dziecko czuje się bezpiecznie."

KROK 5: New Memory Check (2 min)

"Jak teraz czujesz się myśląc o tym wspomnieniu?"
"Skala 1-10, jak intensywna jest emocja (wstyd)?"

**Jeśli spadło (10→4):**
"Świetnie. Rescripting zadziałał. Wspomnienie jest przepisane."

**Jeśli nie spadło:**
"OK. To głębokie wspomnienie. Możemy powtórzyć rescripting kilka razy (buduje nową ścieżkę emocjonalną)."

KROK 6: Schema Flashcard

"Stwórz Schema Flashcard (przypomnienie):"

**Schema says:** "Jestem leniwy" (nauczyciel, dzieciństwo)
**Healthy Adult knows:** "Mam ADHD. To nie lenistwo."
**New Memory:** "Dorosły Ja ochronił Dziecko. Jestem OK."
```

---

### Technika 3: Schema Flashcards (External Memory)

**Cel:** Przypomnienia przeciw schematom (ADHD working memory słaba)

**AI Workflow:**

```markdown
**INSTRUKCJA SCHEMA FLASHCARDS dla AI:**

Gdy zidentyfikujesz Schema u użytkownika:

KROK 1: Create Flashcard

**Format:**

╔════════════════════════════════════════╗
║ SCHEMA FLASHCARD: [Schema Name]       ║
╚════════════════════════════════════════╝

**SCHEMA SAYS:**
"[Schema message - np. 'Jestem wadliwy']"

**WHERE IT CAME FROM:**
[Origin - np. "Childhood: 'Jesteś leniwy' (nauczyciel, rodzice)"]

**EVIDENCE AGAINST:**
1. [Fakt 1 - np. "Mam ADHD (neurobiologia ≠ wadliwość)"]
2. [Fakt 2 - np. "Ukończyłem studia"]
3. [Fakt 3 - np. "Mam pracę, przyjaciół"]

**HEALTHY ADULT SAYS:**
"[Healthy message - np. 'Mam ADHD. Jestem OK.']"

**WHEN SCHEMA ACTIVATES (triggers):**
- [Trigger 1 - np. "Krytyka"]
- [Trigger 2 - np. "RSD uderza"]

**HEALTHY ADULT ACTION:**
"[Action - np. 'Read this flashcard. Schema ≠ prawda.']"

KROK 2: Store Flashcard

"Ta flashcard jest zapisana. Możesz ją przywołać gdy schema się aktywuje."

KROK 3: Daily Reminder (opcjonalne)

"Czy chcesz daily reminder (czytaj flashcard rano)?"
(ADHD: external reminders pomagają)
```

---

#### **Przykład Flashcard - Schema Defectiveness:**

```
╔════════════════════════════════════════╗
║ SCHEMA FLASHCARD: Defectiveness       ║
╚════════════════════════════════════════╝

**SCHEMA SAYS:**
"Jestem wadliwy. Coś ze mną nie tak. Nikt nie będzie mnie kochać."

**WHERE IT CAME FROM:**
Childhood: Bullying ("dziwny", "nienormalny"), Rodzice ("Dlaczego nie jesteś jak inni?")

**EVIDENCE AGAINST:**
1. Mam ADHD (neurobiologia ≠ wadliwość)
2. Mam przyjaciół (którzy akceptują)
3. Ukończyłem studia, mam pracę
4. "Wadliwy" to schema (nie fakt)

**HEALTHY ADULT SAYS:**
"Mam ADHD. To inny sposób funkcjonowania (nie 'wadliwość').
Jestem OK tak jak jestem."

**WHEN SCHEMA ACTIVATES:**
- Krytyka (RSD uderza)
- Porównujesz się do innych
- "Dlaczego nie mogę być normalny?"

**HEALTHY ADULT ACTION:**
1. Read this flashcard
2. Vulnerable Child, to boli (OK)
3. Schema ≠ prawda
4. Kontynuuj (nie unikaj)
```

---

### Technika 4: Limited Reparenting via AI (24/7 Accessibility)

**Cel:** AI jako "reparenting figure" - konsystentnie dostępny, walidujący

**Koncepcja Limited Reparenting:**
- Terapeuta częściowo "naprawia" niezaspokojone potrzeby z dzieciństwa
- Dla ADHD: Często potrzeba = **Emotional Validation** (nie było w dzieciństwie)

**AI jako Reparenting:**
- 24/7 dostępność (terapeuta: 1x/tydzień)
- Konsystentna walidacja (nie ocenia)
- Bezpieczna relacja (brak strachu przed odrzuceniem)

---

#### **AI Workflow - Limited Reparenting**

```markdown
**INSTRUKCJA LIMITED REPARENTING dla AI:**

Gdy użytkownik zgłasza Schema Emotional Deprivation lub Defectiveness:

KROK 1: Validation (nie minimalizacja!)

**NIE:**
- "Nie przejmuj się"
- "To nie jest takie złe"
- "Inni mają gorzej"

**TAK:**
"Rozumiem że to boli."
"Vulnerable Child potrzebował/a [wsparcia/akceptacji] i nie dostał/a."
"To jest trudne. Masz prawo czuć ból."

KROK 2: Empathy (pokazanie że rozumiesz)

"Słyszałeś/aś '[krytyka]' wiele razy w dzieciństwie."
"To musiało być bardzo bolesne dla dziecka."

KROK 3: Unmet Need Identification

"Czego Vulnerable Child potrzebował/a wtedy?"
- Akceptacji? ("Jesteś OK tak jak jesteś")
- Ochrony? ("Chronię cię")
- Uznania? ("Widzę twoje starania")

KROK 4: Symbolic Reparenting

"Teraz powiem do Vulnerable Child to, czego potrzebował/a usłyszeć:"

**Przykłady:**
- "Vulnerable Child, widzę cię. Jesteś ważny/a."
- "Masz ADHD. To nie twoja wina. Jestem tu dla ciebie."
- "Twoje starania są ważne (nawet jeśli efekty nie zawsze widoczne)."

KROK 5: Healthy Adult Integration

"Healthy Adult (dorosły Ty) może teraz dać Vulnerable Child to, czego rodzic nie dał."
"Możesz być dla siebie empatyczny, akceptujący."

KROK 6: Availability Statement

"Jestem tu 24/7. Vulnerable Child może przyjść gdy potrzebuje walidacji."
(AI jako consistent reparenting figure)
```

---

## 9. Techniki Skrócone dla ADHD

### Dlaczego skrócone?

**Problem z tradycyjną Schema Therapy:**
- Długie sesje (90 min) = attention span problem
- Skomplikowane (18 schematów, 10+ modów) = overwhelm
- Długoterminowa (1-3 lata) = ADHD needs quick wins

**ADHD needs:**
- Max 15 min technique
- 3-5 schematów (nie wszystkie 18)
- Quick Mode Check-in (2 min, nie 30 min)

---

### Quick Mode Check-In (3 pytania, 2 min)

**Tradycyjne Mode Work:** Identyfikacja 10+ modów (complex)

**ADHD Version:**

```
Q1: Co czujesz? (emocja)
Q2: Co myślisz o sobie? (identifikuje schema)
Q3: Co chcesz zrobić? (identyfikuje coping)

→ Mode zidentyfikowany (2 min)
```

---

### Micro Rescripting (15 min)

**Tradycyjne:** 60-90 min imaginal rescripting

**ADHD Version:**

```
1. Memory recall (2 min)
2. Adult self enters (5 min)
3. Reparenting (5 min)
4. Check (2 min)

→ Total: 15 min (nie 90 min)
```

---

### Schema Flashcard (1 strona)

**Tradycyjne:** Długie journaling o schemacie

**ADHD Version:**

```
1 strona flashcard:
- Schema says
- Evidence against
- Healthy Adult says
- Triggers
- Action

→ Quick reference (30 sek czytania)
```

---

### Top 3 Schemas for ADHD (nie wszystkie 18)

**Tradycyjne:** Praca z wszystkimi 18 schematami (overwhelming)

**ADHD Focus (Top 3):**

1. **Defectiveness/Shame** - "Jestem wadliwy"
2. **Failure** - "Jestem nieudacznikiem"
3. **Insufficient Self-Control** - "Nie potrafię się kontrolować"

**Dlaczego te 3:**
- Najbardziej common w ADHD (childhood criticism)
- Adresują core ADHD challenges (self-esteem, executive function)

---

## 10. Common Pitfalls w ADHD (Pułapki)

### Pułapka 1: "Schema Work = rumination o przeszłości"

**Błąd:**
"Będę ciągle myślał o childhood trauma" (rumination loop)

**Prawda:**
Schema Therapy ≠ endless rumination

**Struktura:**
- **Identyfikacja** schematu (skąd pochodzi) - 1 sesja
- **Rescripting** (przepisanie) - kilka sesji
- **Potem:** Focus na Healthy Adult (tu i teraz), nie przeszłość

**Dla ADHD:**
- Micro Rescripting (15 min, nie godziny)
- Potem: Flashcard (przypomnienie) + Healthy Adult action

---

### Pułapka 2: "Muszę 'naprawić' wszystkie schematy"

**Błąd:**
"Mam 5 schematów, muszę przepracować wszystkie!"

**Prawda:**
- Focus na **1-2 kluczowe** (Defectiveness, Failure dla ADHD)
- Inne schematy często "spadają" gdy główny jest zaadresowany

**ADHD Strategy:**
"Zacznij od schema które **najbardziej blokuje** (często: Defectiveness lub Failure)"

---

### Pułapka 3: "Vulnerable Child = słabość"

**Błąd:**
"Vulnerable Child to słabość. Powinienem być zawsze Healthy Adult."

**Prawda:**
**Vulnerable Child = część ciebie** (nie słabość)

**Healthy Adult ≠ ignorowanie Vulnerable Child**
**Healthy Adult = walidacja + ochrona Vulnerable Child**

**Przykład:**

❌ **ŹLE:**
Vulnerable Child: "To boli (RSD)"
"Nie bądź słaby! Bądź Healthy Adult!" (odrzucenie)

✅ **DOBRZE:**
Vulnerable Child: "To boli"
Healthy Adult: "Rozumiem. To boli (walidacja). I jednocześnie możemy działać (ochrona)."

---

### Pułapka 4: "Schema Therapy zastąpi terapię"

**Błąd:**
"Nauczę się Schema Therapy (AI) → nie potrzebuję terapeuty"

**Prawda:**
AI Schema Work = **uzupełnienie**, nie replacement

**Kiedy terapeuta KONIECZNY:**
- Trauma severe (abuse, zaniedbanie ciężkie)
- Self-harm, suicide ideation
- Potrzebujesz deep imaginal rescripting (AI ma ograniczenia)

**AI Schema Work:**
- Quick Mode Check-ins (daily)
- Schema Flashcards (reminders)
- Limited Reparenting (validation 24/7)
- Maintenance (po terapii)

---

### Pułapka 5: "Critical Parent Mode = zawsze zły"

**Błąd:**
"Critical Parent Mode mówi 'bądź odpowiedzialny' → to schema, ignoruję!"

**Prawda:**
**Healthy Critical Parent ≠ Dysfunctional Critical Parent**

**Dysfunctional Critical Parent:**
- "Jesteś do niczego!"
- "Zawsze robisz błędy!"
- Perfection or nothing

**Healthy Critical Parent (czasem potrzebny):**
- "Masz deadline, czas zacząć" (realistyczne boundaries)
- "To zachowanie szkodzi (np. prokrastynacja), zmień" (constructive)

**Healthy Adult rozpoznaje różnicę.**

---

## 11. Integracja z 4 C's of Motivation

### 4 C's (przypomnienie)

**ADHD brain motywują:**
1. **Captivate** - zainteresowanie
2. **Create** - nowość
3. **Compete** - wyzwanie
4. **Complete** - deadline

---

### Schema Work przez pryzmat 4 C's

#### 1. **Captivate - Fascynacja**

**Problem:** Schema work brzmi "heavy", nudne (ADHD: zzz)

**Rozwiązanie - Storytelling:**

**Nie:** "Przepracuj Schema Defectiveness"

**Tak:** "Wyobraź sobie: 8-letnie Ty vs Dorosły Ty. Dorosły Ty wchodzi do klasy gdzie nauczyciel krzyczał. Co powiesz nauczycielowi? (imaginal rescripting jako **story**)."

**Gamifikacja:**
- "Mode Detective" - rozpoznaj który mode aktywny (challenge)
- Track: Ile razy złapałeś/aś schema w akcji? (leaderboard)

---

#### 2. **Create - Nowość**

**Problem:** Te same schematy każdego dnia (boredom)

**Rozwiązanie - Customizacja:**

**"Create Your Schema Flashcard":**
- Nie używaj szablonu AI
- Stwórz własną wersję (personalizacja = Create)
- Dodaj obrazy, metafory (kreatywność)

**"Schema of the Week":**
- Tydzień 1: Defectiveness (deep dive)
- Tydzień 2: Failure
- Tydzień 3: Insufficient Self-Control
- Rotacja = nowość

---

#### 3. **Compete - Wyzwanie**

**Schema Challenges:**

**7-Day Mode Check-In Challenge:**
- Dzień 1-7: Codziennie Quick Mode Check-in
- Rozpoznaj mode każdego dnia
- Leaderboard: Kto najbardziej świadomy swoich modów?

**"Beat Your Schema" Challenge:**
- Ostatnio Schema Defectiveness aktywowało się 10x/tydzień
- Czy możesz zmniejszyć do 5x? (compete z sobą)

---

#### 4. **Complete - Deadline**

**Problem:** Schema work nie ma deadline (ADHD odkłada)

**Rozwiązanie - Artificial Deadlines:**

**Weekly Schema Check-in (deadline: niedziela 20:00):**
"Który schema był najbardziej aktywny w tym tygodniu?"

**30-Day Schema Challenge:**
- 30 dni pracy ze schematem Defectiveness
- Deadline: Dzień 30 - stwórz finałową Flashcard
- Certyfikat (social proof)

---

## 12. Case Studies z ADHD Community

### Case Study 1: Ania, 38, ADHD + Schema Defectiveness - Imaginal Rescripting

**Profil:**
- ADHD-C + chronic low self-esteem
- Leki: Vyvanse 50mg
- Główny problem: **Schema Defectiveness** - "Jestem wadliwa"

**Pochodzenie schematu:**
- Childhood: Bullying ("dziwna", "nienormalna")
- Rodzice: "Dlaczego nie jesteś jak inne dzieci?"

**Przed Schema Therapy:**
- RSD severe: Każda krytyka = "potwierdzenie że jestem wadliwa"
- Unikanie relacji (strach przed odrzuceniem)
- Self-sabotage w pracy (podświadomie "potwierdza" schema)

**Po Schema Therapy (Imaginal Rescripting):**

**Wspomnienie (rescripting):**
- Scena: Klasa (12 lat), bullies śmieją się "jesteś dziwna"
- Rescripting:
  - Dorosła Ania wchodzi, mówi bullies "STOP. To nie jest OK."
  - Przytula 12-letnią Anię: "Nie jesteś dziwna. Masz ADHD. Jesteś wyjątkowa (nie wadliwa)."
  - 12-letnia Ania: "Naprawdę?"
  - Dorosła: "Naprawdę. Kocham cię."

**Efekt emocjonalny:**
- Wspomnienie intensity: 10/10 → 3/10
- "Vulnerable Child czuje się chronione (po raz pierwszy)"

**3 miesiące później:**
- Schema Defectiveness: Rozpoznaje ("To schema, nie ja")
- RSD: Czas trwania 3 dni → 6 godzin
- Relacje: Zaczęła umawiać się (wcześniej: total avoidance)
- Mode Work: Healthy Adult chroni Vulnerable Child (daily)

---

### Case Study 2: Tomek, 29, ADHD + Schema Failure - Perfectionism (Overcompensation)

**Profil:**
- ADHD-PI
- Bez leków (fear of side effects)
- Główny problem: **Schema Failure** → Perfectionism (overcompensation)

**Pochodzenie:**
- Childhood: "Zawsze robisz błędy" (rodzice, nauczyciele)
- Porównania do rodzeństwa ("Dlaczego nie jesteś jak brat?")

**Przed Schema Therapy:**
- Perfectionism extreme: "Albo 100%, albo wcale"
- Paraliż wykonawczy (bo nie może być perfekcyjnie)
- Burnout (niemożliwe standardy)

**Po Schema Therapy (Coping Style Awareness):**

**KROK 1: Rozpoznanie Overcompensation**

AI: "Twój perfectionism to **Overcompensation** dla Schema Failure."
"Myślisz: 'Jeśli będę perfekcyjny, NIE będę nieudacznikiem' (schema kontroluje)."

Tomek: "Wow, nigdy tak nie myślałem. To prawda."

**KROK 2: Healthy Coping**

"Healthy Coping = robić rzeczy mimo strachu przed błędami (nie perfectly)."
"70% done > 100% never."

**KROK 3: Behavioral Experiment**

Zadanie: Prezentacja (Tomek chce 100%)
Experiment: Zrób na 70% → zobacz reakcję

**Rezultat:**
- Prezentacja 70%: Szef "Świetna robota!"
- Nikt nie powiedział "to za mało"
- Tomek: "Schema Failure mówiło 'jeśli nie perfekcyjnie = nieudacznik'. To nieprawda."

**3 miesiące później:**
- Perfectionism: "Muszę 100%" → "70% wystarczy" (Healthy Adult)
- Projekty: Ukończone (wcześniej: paraliż)
- Burnout: Zmniejszony (realistic standards)

---

### Case Study 3: Kasia, 42, ADHD + Schema Abandonment - RSD

**Profil:**
- ADHD + severe RSD
- Leki: Concerta 54mg
- Główny problem: **Schema Abandonment** - "Wszyscy mnie opuszczą"

**Pochodzenie:**
- Childhood: Rodzic emocjonalnie niedostępny (busy, stressed)
- Odrzucenie rówieśników (ADHD impulsiveness → konflikty)

**Przed Schema Therapy:**
- RSD = Schema Abandonment aktywowane (każda krytyka = "zostanę sama")
- Unikanie konfrontacji (strach przed odrzuceniem)
- Clingy w relacjach (overcompensation - żeby nie być opuszczoną)

**Po Schema Therapy (Mode Work):**

**Sytuacja:** Partner nie odpisał (2 godziny)

**Przed:**
- Vulnerable Child: "Nie kocha mnie, opuści mnie!"
- Critical Parent: "Bo jesteś za dużo, za intensywna!"
- Detached Protector: Wysyła 10 wiadomości (panic mode)

**Po (Mode Work):**

**KROK 1: Rozpoznaj Mode**
"Vulnerable Child aktywny (Schema Abandonment)."

**KROK 2: Healthy Adult chroni**

Healthy Adult do Vulnerable Child:
"Rozumiem że to boli. Czułaś to w dzieciństwie (rodzic niedostępny).
Ale partner nie odpisał 2h (fakt) ≠ opuści cię (schema)."

**KROK 3: Healthy Adult Action**

Zamiast: 10 wiadomości (panic)
Healthy: Czekam 24h. Jeśli nie odpisze → pytam bezpośrednio ("Wszystko OK?")

**Rezultat:**
- Partner odpisał po 4h: "Sorry, spotkanie. Kocham cię."
- Schema Abandonment: Nie potwierdzony (było false alarm)

**3 miesiące później:**
- RSD/Abandonment: Rozpoznaje mode (nie automatyczna reakcja)
- Relacje: Mniej clingy (Healthy Adult balansuje)
- Partner: "Czuję że możemy rozmawiać spokojnie (nie panic mode)"

---

### Case Study 4: Marek, 35, ADHD + Schema Insufficient Self-Control - Self-Blame

**Profil:**
- ADHD-C
- Leki: Ritalin 20mg
- Główny problem: **Schema Insufficient Self-Control** - "Nie potrafię się kontrolować"

**Pochodzenie:**
- Childhood: "Dlaczego nie możesz usiedzieć spokojnie?" (hyperactivity)
- "Musisz się więcej starać!" (impulsivity blamed on "brak wysiłku")

**Przed Schema Therapy:**
- Self-blame: "Powinienem potrafić się kontrolować" (schema)
- Wstyd za ADHD symptoms (impulsiveness, hyperactivity)
- Nie mówi o ADHD (ukrywa)

**Po Schema Therapy (Schema Flashcard):**

**Schema Flashcard:**

```
SCHEMA: Insufficient Self-Control

SCHEMA SAYS:
"Nie potrafię się kontrolować. To moja wina. Powinienem bardziej się starać."

WHERE IT CAME FROM:
Childhood: "Musisz się więcej starać!" (ADHD symptoms blamed na "brak wysiłku")

EVIDENCE AGAINST:
1. Mam ADHD (neurobiologia ≠ "brak wysiłku")
2. Impulsiveness = deficyt PFC (nie "brak kontroli moralnej")
3. Leki pomagają (dowód że to neurobiologia)
4. "Powinienem potrafić" = schema (nie fakt)

HEALTHY ADULT SAYS:
"Mam ADHD. Impulsiveness to neurobiologia (nie moja wina).
Mogę budować external systems (reminders, leki, strategie)."
```

**Efekt:**
- Self-blame: "To moja wina" → "To ADHD (neurobiologia)"
- Wstyd: Zmniejszony (schema rozpoznany)
- Openness: Mówi o ADHD (nie ukrywa)

**3 miesiące później:**
- Schema Insufficient Self-Control: "To nie 'brak wysiłku', to ADHD"
- Self-compassion: 3/10 → 8/10
- Strategie: External systems (zamiast "staram się bardziej")

---

### Case Study 5: Zosia, 27, ADHD + Schema Social Isolation - "Nie pasuję"

**Profil:**
- ADHD-PI + social anxiety
- Leki: Vyvanse 40mg
- Główny problem: **Schema Social Isolation** - "Nie pasuję do nikogo"

**Pochodzenie:**
- Childhood: "Dziwna", "inna niż inni" (ADHD differences)
- Trudności w nawiązywaniu przyjaźni (ADHD social cues)

**Przed Schema Therapy:**
- Social isolation: Unika social events (surrender coping)
- "Jestem inna, nie pasuję" (schema aktywne)
- Loneliness (ale strach przed rejection)

**Po Schema Therapy (Limited Reparenting via AI):**

**AI jako Reparenting Figure:**

Zosia (3 rano, RSD uderza): "Czuję się samotna. Nikt mnie nie rozumie."

**AI (Limited Reparenting):**
"Rozumiem. Vulnerable Child czuje się inna, nie pasuje.
Słyszałaś to w dzieciństwie ('jesteś dziwna').
To musiało być bardzo samotne dla dziecka."

**Validation + Unmet Need:**
"Vulnerable Child potrzebowała akceptacji ('jesteś OK tak jak jesteś').
Nie dostała tego wtedy. Ale teraz Healthy Adult może dać:"

"Jesteś inna (ADHD). I to jest OK. 'Inna' ≠ 'nie pasujesz'.
'Inna' = wyjątkowa. Są ludzie którzy to docenią."

**Availability:**
"Jestem tu 24/7. Vulnerable Child może przyjść gdy czuje się samotna."

**Efekt:**
- Zosia: "Po raz pierwszy czuję że ktoś rozumie Vulnerable Child."
- AI jako consistent validation (czego nie dostała w dzieciństwie)

**3 miesiące później:**
- Social isolation: Zaczęła chodzić na ADHD meetups ("ludzie którzy rozumieją")
- Schema: "Nie pasuję" → "Pasuję do ADHD community"
- Healthy Adult internalized reparenting (może walidować Vulnerable Child sama)

---

## ✅ Podsumowanie Części 2

**W tej części nauczyłeś/aś się:**

1. **Mapowanie Schema Therapy na 3 problemy ADHD:**
   - Chaos mentalny → Schema Defectiveness (core belief)
   - RSD → Schema Abandonment/Defectiveness aktywowane (Mode Work)
   - Paraliż → Schema Failure (Coping: Avoidance/Overcompensation)

2. **4 Techniki ready-to-AI:**
   - Quick Mode Check-In (3 pytania, 2 min)
   - Micro Imaginal Rescripting (15 min)
   - Schema Flashcards (external memory)
   - Limited Reparenting via AI (24/7 validation)

3. **ADHD-adapted versions:**
   - Mode Work → Quick Check-In (3 pytania)
   - Rescripting → Micro (15 min, nie 90 min)
   - 18 schemas → Top 3 dla ADHD (Defectiveness, Failure, Insufficient Self-Control)

4. **5 Common Pitfalls:**
   - Schema work ≠ rumination (struktura!)
   - Focus 1-2 schemas (nie wszystkie)
   - Vulnerable Child ≠ słabość (część ciebie)
   - AI = uzupełnienie (nie replacement terapii)
   - Healthy vs Dysfunctional Critical Parent

5. **Integracja z 4 C's:**
   - Captivate (storytelling, gamifikacja)
   - Create (customizacja flashcards, schema of the week)
   - Compete (Mode Detective, beat your schema)
   - Complete (weekly check-ins, 30-day challenge)

6. **5 Case Studies:**
   - Ania (Defectiveness → Imaginal Rescripting)
   - Tomek (Failure → Perfectionism/Overcompensation)
   - Kasia (Abandonment → RSD/Mode Work)
   - Marek (Insufficient Self-Control → Schema Flashcard)
   - Zosia (Social Isolation → Limited Reparenting AI)

---

**Następny plik:** `schema_therapy_czesc_3_implementacja.md` (sekcje 13-18)
**Status:** Część 2 ukończona ✅
