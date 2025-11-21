# Lekcja 4: Narzędzie - Planner AI (Lead Days + Sprints + Energy)

**Moduł:** 4 - Planner AI - Lead Days + Sprints
**Czas:** 10-12 minut
**Poziom:** Praktyczny

---

## 🎯 Cel lekcji

Po tej lekcji będziesz wiedział/a:
- **Jak używać** Planner AI (Custom GPT vs Projekt - DARMOWY)
- **Jakie funkcje** ma Planner AI (Lead Days, Sprinty, Energy tracking)
- **Jak wygląda** typowy workflow (dzień z Planner AI)
- **Przykłady użycia** (real scenarios)
- **FAQ** (najczęstsze pytania)

---

## 🤖 Czym jest Planner AI?

### **Definicja:**

> Planner AI = narzędzie AI do planowania zadań dla ADHD brain, oparte na **Lead Days** (urgency) + **Sprinty** (typy zadań) + **Energy Management**.

**Co robi:**
- ✅ Liczy **Lead Days** automatycznie (ile dni do deadline'u)
- ✅ Przypisuje **urgency levels** (RED/YELLOW/GREEN)
- ✅ Określa **typ Sprintu** (Urgent, Deadlines, Admin, Creative)
- ✅ Sortuje po **priorytecie** (najpilniejsze pierwsze)
- ✅ Dopasowuje do **energy pattern** (Early Bird, Night Owl, etc.)
- ✅ Dodaje **recovery time** (przerwy między Sprintami)
- ✅ Trackuje **czas i energię** (porównuje oszacowanie vs realne)

**Czas:** 30 sekund (vs 10+ minut ręcznego planowania)

---

## 🔧 Jak używać Planner AI? (2 opcje)

### **Opcja 1: Custom GPT (gotowe, szybkie)**

**Co to:**
- **Gotowy Custom GPT** od Przemka (link w materiale kursu)
- Klikasz link → używasz od razu (zero setup)

**Zalety:**
- ✅ **Szybkie** (zero konfiguracji)
- ✅ **Gotowe** (wszystkie funkcje działa od razu)
- ✅ **Updates** (Przemek aktualizuje prompt, Ty masz zawsze najnowszy)

**Wady:**
- ⚠️ **Brak pamięci** (nie zapamięta Twojego energy pattern - musisz wklejać co raz)
- ⚠️ **Wymaga ChatGPT Plus** ($20/msc)

**Kiedy wybrać:**
- Jeśli masz ChatGPT Plus
- Jeśli chcesz szybki start (bez konfiguracji)
- Jeśli nie potrzebujesz pamięci (ok z wklejaniem energy pattern co raz)

---

### **Opcja 2: Projekt ChatGPT/Claude (DARMOWY, z pamięcią)**

**Co to:**
- **Tworzysz swój własny projekt** (ChatGPT lub Claude)
- Wklejasz prompt od Przemka (instrukcje w materiale kursu)
- AI **zapamięta** Twój energy pattern, preferencje, historię

**Zalety:**
- ✅ **DARMOWE** (ChatGPT Free lub Claude Free wystarczy)
- ✅ **Pamięć** (nie wklejasz energy pattern co raz - AI pamięta)
- ✅ **Personalizacja** (możesz modyfikować prompt dla siebie)
- ✅ **Historia** (AI widzi poprzednie Sprinty, uczy się Ciebie)

**Wady:**
- ⚠️ **Setup** (musisz utworzyć projekt + wkleić prompt - 5 minut)
- ⚠️ **Updates** (musisz ręcznie update'ować prompt, jeśli Przemek zmieni)

**Kiedy wybrać:**
- Jeśli nie masz ChatGPT Plus (Free plan)
- Jeśli chcesz pamięć (AI zapamięta Ciebie)
- Jeśli chcesz personalizację (swoje modyfikacje)

---

### **Która opcja dla mnie?**

| **Aspekt** | **Custom GPT** | **Projekt (ChatGPT/Claude)** |
|------------|----------------|------------------------------|
| **Koszt** | ChatGPT Plus ($20/msc) | **DARMOWE** |
| **Setup** | Zero (klik link) | 5 minut (utwórz + wklej prompt) |
| **Pamięć** | ❌ Nie (wklejasz co raz) | ✅ Tak (AI zapamięta Ciebie) |
| **Updates** | ✅ Automatyczne (od Przemka) | ⚠️ Ręczne (update prompt sam) |
| **Personalizacja** | ❌ Nie (gotowy prompt) | ✅ Tak (możesz modyfikować) |

**Rekomendacja:**
- Masz Plus? → **Custom GPT** (szybkie, zero setup)
- Nie masz Plus? → **Projekt** (darmowy, z pamięcią)

---

## 📋 Funkcje Planner AI

### **1. Lead Days Calculator**

**Wklejasz:**
```
Zadania:
1. Raport - deadline: 12 stycznia
2. Prezentacja - deadline: 18 stycznia
```

**AI zwraca:**
```
Dzisiaj: 10 stycznia

| Zadanie     | Deadline   | Lead Days | Urgency |
|-------------|------------|-----------|---------|
| Raport      | 12 stycznia| 2         | 🟡 YELLOW |
| Prezentacja | 18 stycznia| 8         | 🟢 GREEN  |
```

**Co robi:**
- Oblicza Lead Days (deadline - dzisiaj)
- Przypisuje kolor (RED/YELLOW/GREEN)

---

### **2. Sprint Planner**

**Wklejasz:**
```
Zadania dzisiaj:
1. Raport (Lead Day 2 - YELLOW)
2. E-mail (Lead Day 4 - YELLOW)
3. Faktury (brak deadline)
```

**AI zwraca:**
```
**Plan Sprintów na dzisiaj:**

1. 🟡 Deadlines Sprint: Raport (Lead Day 2)
2. 🟡 Deadlines Sprint: E-mail (Lead Day 4)
3. 🟢 Admin Sprint: Faktury

**Priorytet:** Raport → E-mail → Faktury
```

**Co robi:**
- Określa typ Sprintu (Urgent/Deadlines/Admin/Creative)
- Sortuje po priorytecie (Lead Days rosnąco)

---

### **3. Energy Matching**

**Wklejasz:**
```
Mój energy pattern: Early Bird (high energy rano)
Zadania dzisiaj:
1. Raport (Deadlines Sprint)
2. Faktury (Admin Sprint)
```

**AI zwraca:**
```
**Plan dopasowany do energii:**

**9:00-11:00** (HIGH energy) → 🟡 Deadlines Sprint: Raport
**11:00-11:20** → Recovery
**14:00-14:30** (MEDIUM energy) → 🟢 Admin Sprint: Faktury

**Dlaczego:**
- Raport (focus task) → Twoja peak energy (rano)
- Faktury (rutynowe) → Medium energy (popołudnie wystarczy)
```

**Co robi:**
- Dopasowuje Sprinty do energy pattern
- Dodaje recovery time (przerwy)

---

### **4. Time Tracking**

**Wklejasz:**
```
Sprint: Raport
Start: 9:00
Koniec: 11:15
Oszacowanie: 1 godzina
```

**AI zwraca:**
```
**Raport:**
- Czas rzeczywisty: 2 godz 15 min
- Oszacowanie: 1 godzina
- Różnica: +1 godz 15 min (2.25x dłużej)

**Insight:** Raporty zajmują Ci ~2 godziny. Następnym razem zaplanuj więcej czasu.
```

**Co robi:**
- Oblicza czas rzeczywisty
- Porównuje z oszacowaniem
- Daje insight (nauka dla przyszłości)

---

### **5. Energy Tracking**

**Wklejasz (przez tydzień):**
```
Pon: Rano 8/10, Popołudnie 5/10, Wieczór 3/10
Wt: Rano 9/10, Popołudnie 4/10, Wieczór 2/10
...
```

**AI zwraca (po tygodniu):**
```
**Twój energy pattern: Early Bird 🌅**
- High energy: Rano (9:00-12:00) - średnia 8.5/10
- Medium energy: Popołudnie (14:00-17:00) - średnia 5/10
- Low energy: Wieczór (19:00+) - średnia 3/10

**Rekomendacje:**
Planuj focus tasks (Urgent/Deadlines) RANO (9:00-12:00).
```

**Co robi:**
- Analizuje energy przez tydzień
- Określa pattern (Early Bird/Night Owl/Sinusoidal)
- Daje rekomendacje (kiedy planować focus tasks)

---

## 🔄 Typowy workflow z Planner AI

### **Poranek (Planning) - 5 minut**

**KROK 1: Przegląd zadań**

**Ty wklejasz:**
```
Dzisiaj: Czwartek, 10 stycznia
Mój energy pattern: Early Bird

Zadania:
1. Raport - deadline: Piątek (jutro)
2. E-mail - deadline: Poniedziałek (za 4 dni)
3. Prezentacja - deadline: Wtorek (za 5 dni)
4. Faktury - brak deadline
```

---

**AI zwraca:**
```
**Lead Days + Sprinty na dzisiaj:**

| Zadanie     | Lead Days | Sprint          | Priorytet |
|-------------|-----------|-----------------|-----------|
| Raport      | 1 🔴      | Urgent Sprint   | 1         |
| E-mail      | 4 🟡      | Deadlines Sprint| 2         |
| Prezentacja | 5 🟢      | Creative Sprint | 4         |
| Faktury     | - 🟢      | Admin Sprint    | 3         |

**Plan na dzisiaj (energy-matched):**

**9:00-11:00** (HIGH energy) → 🔴 Urgent Sprint: Raport
  - Lead Day 1 (RED) - deadline JUTRO
  - Dokończ DZISIAJ (priorytet absolutny)

**11:00-11:20** → Recovery (spacer, woda)

**11:20-12:20** (HIGH energy) → 🟡 Deadlines Sprint: E-mail
  - Lead Day 4 (YELLOW) - zacznij lub zaplanuj

**12:20-13:00** → Recovery (obiad)

**14:00-14:30** (MEDIUM energy) → 🟢 Admin Sprint: Faktury
  - Rutynowe (medium energy wystarczy)

**Prezentacja:** Lead Day 5 (GREEN) - przejrzyj za 2-3 dni (dzisiaj nie musisz)

**Kluczowy wniosek:**
Zacznij od Urgent Sprint (Raport). To RED - najwyższy priorytet.
```

**Czas:** 30 sekund (AI robi całe planowanie)

---

### **W trakcie dnia (Execution)**

**KROK 2: Wykonujesz Sprinty**

- 9:00: Zaczynam Urgent Sprint (Raport)
- 11:00: Dokończyłem Raport → Recovery (spacer)
- 11:20: Zaczynam Deadlines Sprint (E-mail)
- 12:20: Dokończyłem E-mail → Recovery (obiad)
- 14:00: Zaczynam Admin Sprint (Faktury)
- 14:30: Dokończyłem Faktury → Koniec pracy

**Tracking (opcjonalnie):**
- Zapisujesz czas każdego Sprintu (start → koniec)

---

### **Wieczór (Review) - 2 minuty**

**KROK 3: Tracking + Review**

**Ty wklejasz:**
```
Sprinty dzisiaj:
1. Urgent Sprint: Raport - 9:00-11:00 (2 godz) - Oszacowanie: 1.5 godz
2. Deadlines Sprint: E-mail - 11:20-12:20 (1 godz) - Oszacowanie: 1 godz
3. Admin Sprint: Faktury - 14:00-14:30 (30 min) - Oszacowanie: 30 min

Energia dzisiaj:
Rano: 9/10
Popołudnie: 6/10
Wieczór: 3/10
```

**AI zwraca:**
```
**Sprinty - Tracking:**

**Raport:**
- Czas: 2 godz (Oszacowanie: 1.5 godz)
- Różnica: +30 min (1.33x dłużej)
- Insight: Raporty zajmują Ci trochę dłużej - zaplanuj 2 godziny następnym razem.

**E-mail:**
- Czas: 1 godz (Oszacowanie: 1 godz)
- ✅ Zgodne z oszacowaniem

**Faktury:**
- Czas: 30 min (Oszacowanie: 30 min)
- ✅ Zgodne z oszacowaniem

**Energia:**
Dzisiaj: Early Bird pattern (rano 9, popołudnie 6, wieczór 3) - zgodne z Twoim standardem.

**Podsumowanie:**
✅ Dokończone: 3/3 Sprinty (100%)
✅ Urgent Sprint (Raport) - done (deadline jutro - bez stresu!)
✅ Energy matching - Sprinty dopasowane do energii (dobry plan)
```

**Czas:** 1 minuta (AI robi summary)

---

## 🧩 Przykłady użycia (real scenarios)

### **Scenariusz 1: "Chaos - za dużo zadań"**

**Sytuacja:**
- Masz 10 zadań
- Nie wiesz, od czego zacząć
- Overwhelm (paraliż)

**Rozwiązanie z Planner AI:**

**Ty wklejasz:**
```
Zadania (chaos!):
1. Raport - deadline jutro
2. E-mail szef - deadline dzisiaj
3. Prezentacja - deadline za tydzień
4. Faktury - brak deadline
5. Meeting prep - spotkanie za 2 dni
6. Code review - deadline za 3 dni
7. Documentation - brak deadline
8. Bug fix - urgent (klient czeka)
9. Nauka (kurs) - brak deadline
10. Cleanup (porządki) - brak deadline
```

**AI zwraca:**
```
**Lead Days + Priorytety:**

| Zadanie      | Lead Days | Urgency | Priorytet |
|--------------|-----------|---------|-----------|
| E-mail szef  | 0 🔴      | RED     | 1         |
| Bug fix      | 0 🔴      | RED     | 2         |
| Raport       | 1 🔴      | RED     | 3         |
| Meeting prep | 2 🟡      | YELLOW  | 4         |
| Code review  | 3 🟡      | YELLOW  | 5         |
| Prezentacja  | 7 🟢      | GREEN   | 6         |
| Faktury      | - 🟢      | GREEN   | 7         |
| Documentation| - 🟢      | GREEN   | 8         |
| Cleanup      | - 🟢      | GREEN   | 9         |
| Nauka        | - 🟢      | GREEN   | 10        |

**DZISIAJ robisz (MAX 3!):**
1. 🔴 E-mail szef (RED - deadline DZISIAJ)
2. 🔴 Bug fix (RED - klient czeka)
3. 🔴 Raport (RED - deadline jutro)

**Resztę:**
- Meeting prep (YELLOW) - zrobisz JUTRO (jeszcze czas)
- Code review (YELLOW) - zrobisz pojutrze
- Prezentacja, Faktury, Documentation, Cleanup, Nauka (GREEN) - zrobisz PÓŹNIEJ (nie dzisiaj!)

**Kluczowy wniosek:**
**Tylko 3 zadania dzisiaj** (RED). Reszta POCZEKA. Nie próbuj robić wszystkiego.
```

**Rezultat:**
- Chaos → clarity (3 zadania, jasny plan)
- Zero overwhelm (wiesz, co ignorować)
- Priorytet: RED tasks (najpilniejsze)

---

### **Scenariusz 2: "Mam czas, ale nie zaczynam"**

**Sytuacja:**
- Prezentacja za 10 dni (dużo czasu)
- Nie zaczynam (brak urgency)
- Time blindness ("mam czas" → za 2 dni panika)

**Rozwiązanie z Planner AI:**

**Ty wklejasz:**
```
Zadanie: Prezentacja - deadline: 20 stycznia (za 10 dni)
Dzisiaj: 10 stycznia

Pytanie: Czy mam zacząć dzisiaj?
```

**AI zwraca:**
```
**Prezentacja:**
- Deadline: 20 stycznia (za 10 dni)
- Lead Days: **10 Lead Days** (🟢 GREEN)

**Czy zacząć dzisiaj?**
**Nie musisz** (GREEN - low urgency). ALE:

**Micro-commitment (jeśli chcesz):**
Jeśli prezentacja jest duża (>2 godziny pracy), rozbij na micro-commitments:

1. **Dzisiaj (10 Lead Days - GREEN):** Zbierz materiały (10 min)
2. **Za 3 dni (7 Lead Days - GREEN):** Outline (30 min)
3. **Za 5 dni (5 Lead Days - GREEN → YELLOW):** Draft slajdów (1 godz)
4. **Za 7 dni (3 Lead Days - YELLOW):** Dopracowanie (1 godz)
5. **Za 9 dni (1 Lead Day - RED):** Finalizacja (30 min)

**Dlaczego rozbić:**
- Prezentacja = duży task → łatwo odkładać (brak urgency)
- Micro-commitments = małe kroki → łatwiej zacząć
- Każdy krok ma swój Lead Day → urgency rośnie stopniowo

**Rekomendacja:**
Dzisiaj zrób **10 min: Zbierz materiały** (ridiculous small). To wystarczy.
```

**Rezultat:**
- Wiesz, kiedy zacząć (nie dzisiaj - GREEN)
- Masz plan (micro-commitments)
- Unikasz last-minute rush (rozłożone w czasie)

---

### **Scenariusz 3: "Nie mam energii na nic"**

**Sytuacja:**
- Masz zadania (YELLOW - medium urgency)
- Zero energii (zmęczenie, low day)
- Czy robić?

**Rozwiązanie z Planner AI:**

**Ty wklejasz:**
```
Zadania dzisiaj:
1. Raport - Lead Day 3 (YELLOW)
2. E-mail - Lead Day 4 (YELLOW)

Ale: Energia 2/10 (bardzo niska). Co robić?
```

**AI zwraca:**
```
**Energia 2/10 (bardzo niska):**

**Opcja 1: Recovery (REKOMENDOWANE)**
- Jeśli energia 2/10 → **odpoczynek priorytetem**
- Nie próbuj robić focus tasks (Deadlines Sprint) - będziesz walczyć
- **Recovery:** spacer, natura, power nap (15-20 min), hydration

**Dlaczego:**
- ADHD brain z low energy = nieskuteczność (walka)
- Better to odpocząć DZIŚ + zrobić jutro DOBRZE niż dziś ŹLE

---

**Opcja 2: Admin Sprint (jeśli MUSISZ coś zrobić)**
- Jeśli nie możesz odpoczywać → **Admin Sprint** (low energy tasks)
- Przykłady: faktury, e-maile (nie wymagające myślenia), cleanup

**NIE:**
- ❌ Raport (focus task - potrzebujesz high energy)
- ❌ E-mail (jeśli wymaga myślenia)

**TAK:**
- ✅ Faktury (rutynowe)
- ✅ Cleanup (mindless)

---

**Co z Raportem i E-mailem?**
- Lead Day 3-4 (YELLOW) - **masz jeszcze czas** (nie RED!)
- Zrób jutro (gdy energia wróci)
- To nie jest deadline dzisiaj → OK odłożyć

**Kluczowy wniosek:**
**Recovery > produktywność** (jeśli energia 2/10). Odpoczynek = inwestycja w jutrzejszą energię.
```

**Rezultat:**
- Wiesz, że możesz odpocząć (nie wina)
- Nie walczysz z low energy (dajesz sobie przyzwolenie)
- Jutro będzie lepiej (po recovery)

---

## ❓ FAQ (najczęstsze pytania)

### **1. Czy muszę trackować czas/energię codziennie?**

**Odpowiedź:**
**Nie musisz** (to nie obowiązek).

**Kiedy trackować:**
- **Czas:** Jeśli chcesz nauczyć się realnych czasów (koniec optimism bias) → trackuj przez 1-2 tygodnie, potem możesz przestać
- **Energię:** Jeśli nie znasz swojego pattern → trackuj przez 1 tydzień (poznasz swój rytm), potem możesz przestać

**Kiedy nie trackować:**
- Jeśli już znasz swój pattern (np. wiesz, że jesteś Early Bird)
- Jeśli już wiesz, ile trwają Twoje taski (dobre oszacowanie)

**Kluczowe:**
> Tracking = **narzędzie do nauki** (nie cel sam w sobie). Uczysz się → przestajesz trackować.

---

### **2. Co jeśli nie dokończę Sprintu?**

**Odpowiedź:**
**To OK** (nie musisz dokończyć wszystkiego).

**Co robić:**
1. **Zapisz progress** (gdzie skończyłeś)
2. **Oceń Lead Day** (czy to RED? → musisz kontynuować jutro)
3. **Sprawdź energię** (czy masz? → kontynuuj lub odpoczynek)

**Przykład:**
- Sprint: Raport (Lead Day 1 - RED)
- Zrobiłeś 50% (nie dokończyłeś)
- **Jutro deadline** → musisz kontynuować JUTRO (priorytet)

**Jeśli YELLOW/GREEN:**
- Możesz odłożyć (nie RED) → zrobisz później

**Kluczowe:**
> Nie dokończenie ≠ porażka. ADHD brain ma zmienne energie - **flexibility OK**.

---

### **3. Co jeśli pojawi się urgent task (nie planowane)?**

**Odpowiedź:**
**Oceń Lead Day** (czy to RED?).

**Jeśli RED (deadline dzisiaj/jutro):**
- **Dodaj do Urgent Sprint** (priorytet)
- Przesuń inne zadania (jeśli muszisz)

**Jeśli YELLOW/GREEN:**
- **Zapisz** (nie rób dzisiaj, jeśli masz RED taski)
- Zrobisz, gdy stanie się RED

**Przykład:**
- Planujesz: Raport (RED)
- Pojawia się: Bug fix (klient czeka - RED)
- **Dodaj Bug fix do Urgent Sprint** (najpierw Bug fix, potem Raport)

**Kluczowe:**
> Planner AI = **flexibility** (nie rigid plan). Możesz dodawać/przesuwać zadania (Lead Days określają priorytet).

---

### **4. Co jeśli mam tylko GREEN zadania (brak deadline)?**

**Odpowiedź:**
**Wybierz przez 4 C's** (motywacja ADHD).

**Pytania:**
1. **Captivate:** Co mnie INTERESUJE dzisiaj?
2. **Create:** Co jest NOWE/kreatywne?
3. **Compete:** Co jest WYZWANIEM?
4. **Complete:** Które mogę DOKOŃCZYĆ dzisiaj? (małe zadanie)

**Przykład:**
- Zadania GREEN: Faktury, Dokumentacja, Nauka, Cleanup
- **Captivate:** Nauka (interesuję się tym dzisiaj)
- **Zacznij od Nauka** (dopamina z Captivate)

**Kluczowe:**
> GREEN tasks = brak urgency → użyj **4 C's** (alternatywna motywacja).

---

### **5. Czy Planner AI działa dla każdego?**

**Odpowiedź:**
**Działa dla większości ADHD**, ale:

**Działa najlepiej, jeśli:**
- ✅ Masz zadania z deadlines (Lead Days = urgency)
- ✅ Chcesz struktury (ale flexibility)
- ✅ Motywujesz się przez urgency (Complete - jeden z 4 C's)

**Może nie działać, jeśli:**
- ⚠️ Wszystkie zadania bez deadline (brak urgency → użyj 4 C's zamiast Lead Days)
- ⚠️ Wolisz "idź z flow" (zero planowania - to OK, Planner nie dla Ciebie)
- ⚠️ Przytłacza Cię planowanie (overwhelm - użyj uproszczoną wersję: tylko RED/YELLOW/GREEN, bez trackingu)

**Kluczowe:**
> Planner AI = **narzędzie** (nie must). Testuj, dopasuj do siebie, modyfikuj.

---

## 📋 Podsumowanie

### **Kluczowe wnioski:**

1. **Planner AI = Lead Days + Sprinty + Energy Management**
   - Liczy Lead Days (urgency)
   - Określa Sprinty (typy zadań)
   - Dopasowuje do energii (energy matching)
   - Dodaje recovery (przerwy)

2. **2 opcje:**
   - **Custom GPT:** Szybkie, zero setup (wymaga Plus)
   - **Projekt (ChatGPT/Claude):** DARMOWY, z pamięcią (5 min setup)

3. **Funkcje:**
   - Lead Days Calculator (urgency levels)
   - Sprint Planner (typy zadań + priorytet)
   - Energy Matching (dopasowanie do rytmu)
   - Time Tracking (oszacowanie vs realne)
   - Energy Tracking (pattern przez tydzień)

4. **Typowy workflow:**
   - **Poranek:** Przegląd zadań (5 min) - AI planuje dzień
   - **W trakcie:** Wykonujesz Sprinty (priorytet RED → YELLOW)
   - **Wieczór:** Review (2 min) - AI trackuje + insights

5. **Real scenarios:**
   - Chaos (10 zadań) → AI priorytetyzuje (3 RED dzisiaj, reszta później)
   - "Mam czas" (GREEN) → AI rozbija na micro-commitments
   - Low energy → AI rekomenduje recovery (nie walka)

6. **FAQ:**
   - Nie musisz trackować codziennie (tylko do nauki)
   - Nie dokończenie Sprint = OK (flexibility)
   - Urgent task → dodaj (Lead Days określają priorytet)
   - GREEN tasks → wybierz przez 4 C's
   - Planner nie dla każdego (testuj, dopasuj)

---

## ✅ Zadanie do wykonania

**Jutro rano:**

1. **Wybierz opcję:**
   - Custom GPT (link w materiale) lub Projekt (instrukcje w materiale)

2. **Użyj Planner AI:**
   - Wklej wszystkie zadania (z deadlines)
   - Zobacz Lead Days + Sprinty
   - Zacznij od najwyższego priorytetu (RED/YELLOW)

3. **Wieczorem:**
   - Tracking (ile czasu zajęły Sprinty?)
   - Czy oszacowanie było dobre?

**Testuj przez tydzień** → Sprawdź, czy Planner AI działa dla Ciebie.

---

## ➡️ Co dalej?

**Moduł 5: Micro-Start Coach + Body Doubling AI**
- Jak zacząć, gdy nie możesz zacząć (paraliż wykonawczy)
- Micro-start (ridiculous small first step)
- Body Doubling AI (AI jako companion)
- Jak używać AI do "być z Tobą" podczas pracy

---

**Autor:** Przemek
**Moduł:** 4 - Planner AI - Lead Days + Sprints
**Źródła:** Ruri Ohama (Lead Day System + Sprint Method), praktyczne testy z ADHD community
**Wersja:** V0
**Data:** 2025-01-XX
