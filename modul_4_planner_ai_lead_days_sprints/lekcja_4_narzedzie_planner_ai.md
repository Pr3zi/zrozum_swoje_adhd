# Lekcja 4: Narzędzie - Planner AI (System Odliczania Dni + Sprinty + Energia)

**Moduł:** 4 - Planner AI - System Odliczania Dni + Sprinty
**Czas:** 10-12 minut
**Poziom:** Praktyczny

---

## 🎯 Cel lekcji

Po tej lekcji będziesz wiedział/a:
- **Jak używać** Planner AI (Custom GPT vs Projekty Claude - DARMOWY)
- **Jakie funkcje** ma Planner AI (System Odliczania Dni, Sprinty, śledzenie energii / energy tracking)
- **Jak wygląda** typowy przepływ pracy (workflow) - dzień z Planner AI
- **Przykłady użycia** (rzeczywiste scenariusze / real scenarios)
- **FAQ** (najczęstsze pytania)

---

## 🤖 Czym jest Planner AI?

### **Definicja:**

> Planner AI = narzędzie AI do planowania zadań dla mózgu z ADHD, oparte na **System Odliczania Dni (Lead Days)** - pilność (urgency) + **Sprinty** (typy zadań) + **Zarządzanie Energią (Energy Management)**.

**Co robi:**
- ✅ Liczy **Dni Odliczania (Lead Days)** automatycznie (ile dni do deadline)
- ✅ Przypisuje **poziomy pilności (urgency levels)** - CZERWONY/ŻÓŁTY/ZIELONY (RED/YELLOW/GREEN)
- ✅ Określa **typ Sprintu** (Pilny / Urgent, Deadlines, Administracyjny / Admin, Kreatywny / Creative)
- ✅ Sortuje po **priorytecie** (najpilniejsze pierwsze)
- ✅ Dopasowuje do **wzorca energii (energy pattern)** - Early Bird, Night Owl, etc.
- ✅ Dodaje **czas odpoczynku (recovery time)** - przerwy między Sprintami
- ✅ Śledzi **czas i energię** (porównuje oszacowanie vs realne)

**Czas:** 30 sekund (vs 10+ minut ręcznego planowania)

---

## 🔧 Jak używać Planner AI? (2 opcje)

### **Opcja 1: Custom GPT (gotowe, szybkie)**

**Co to:**
- **Gotowy Custom GPT** od Przemka (link w materiale kursu)
- Klikasz link → używasz od razu (zero konfiguracji / setup)

**Zalety:**
- ✅ **Szybkie** (zero konfiguracji)
- ✅ **Gotowe** (wszystkie funkcje działają od razu)
- ✅ **Aktualizacje (Updates)** - Przemek aktualizuje prompt, Ty masz zawsze najnowszy

**Wady:**
- ⚠️ **Brak pamięci** (nie zapamięta Twojego wzorca energii / energy pattern - musisz wklejać za każdym razem)
- ⚠️ **Wymaga ChatGPT Plus** ($20/miesiąc)

**Kiedy wybrać:**
- Jeśli masz ChatGPT Plus
- Jeśli chcesz szybki start (bez konfiguracji)
- Jeśli nie potrzebujesz pamięci (ok z wklejaniem wzorca energii za każdym razem)

---

### **Opcja 2: Projekt ChatGPT/Claude (DARMOWY, z pamięcią)**

**Co to:**
- **Tworzysz swój własny projekt** (ChatGPT lub Claude)
- Wklejasz prompt od Przemka (instrukcje w materiale kursu)
- AI **zapamięta** Twój wzorzec energii (energy pattern), preferencje, historię

**Zalety:**
- ✅ **DARMOWE** (ChatGPT Free lub Claude Free wystarczy)
- ✅ **Pamięć** (nie wklejasz wzorca energii za każdym razem - AI pamięta)
- ✅ **Personalizacja** (możesz modyfikować prompt dla siebie)
- ✅ **Historia** (AI widzi poprzednie Sprinty, uczy się Ciebie)

**Wady:**
- ⚠️ **Konfiguracja (Setup)** - musisz utworzyć projekt + wkleić prompt (5 minut)
- ⚠️ **Aktualizacje (Updates)** - musisz ręcznie aktualizować prompt, jeśli Przemek zmieni

**Kiedy wybrać:**
- Jeśli nie masz ChatGPT Plus (plan Free)
- Jeśli chcesz pamięć (AI zapamięta Ciebie)
- Jeśli chcesz personalizację (swoje modyfikacje)

---

### **Która opcja dla mnie?**

| **Aspekt** | **Custom GPT** | **Projekt (ChatGPT/Claude)** |
|------------|----------------|------------------------------|
| **Koszt** | ChatGPT Plus ($20/miesiąc) | **DARMOWE** |
| **Konfiguracja (Setup)** | Zero (klik link) | 5 minut (utwórz + wklej prompt) |
| **Pamięć** | ❌ Nie (wklejasz za każdym razem) | ✅ Tak (AI zapamięta Ciebie) |
| **Aktualizacje (Updates)** | ✅ Automatyczne (od Przemka) | ⚠️ Ręczne (aktualizuj prompt sam) |
| **Personalizacja** | ❌ Nie (gotowy prompt) | ✅ Tak (możesz modyfikować) |

**Rekomendacja:**
- Masz Plus? → **Custom GPT** (szybkie, zero konfiguracji)
- Nie masz Plus? → **Projekt** (darmowy, z pamięcią)

---

## 📋 Funkcje Planner AI

### **1. Kalkulator Dni Odliczania (Lead Days Calculator)**

**Wklejasz:**
```
Zadania:
1. Raport - deadline: 12 stycznia
2. Prezentacja - deadline: 18 stycznia
```

**AI zwraca:**
```
Dzisiaj: 10 stycznia

| Zadanie     | Deadline   | Dni Odliczania (Lead Days) | Pilność (Urgency) |
|-------------|------------|----------------------------|-------------------|
| Raport      | 12 stycznia| 2                          | 🟡 ŻÓŁTY (YELLOW) |
| Prezentacja | 18 stycznia| 8                          | 🟢 ZIELONY (GREEN)|
```

**Co robi:**
- Oblicza Dni Odliczania (Lead Days) - deadline minus dzisiaj
- Przypisuje kolor (CZERWONY/ŻÓŁTY/ZIELONY - RED/YELLOW/GREEN)

---

### **2. Planer Sprintów (Sprint Planner)**

**Wklejasz:**
```
Zadania dzisiaj:
1. Raport (Dzień Odliczania 2 - ŻÓŁTY / Lead Day 2 - YELLOW)
2. E-mail (Dzień Odliczania 4 - ŻÓŁTY / Lead Day 4 - YELLOW)
3. Faktury (brak deadline)
```

**AI zwraca:**
```
**Plan Sprintów na dzisiaj:**

1. 🟡 Sprint Deadlines: Raport (Dzień Odliczania 2)
2. 🟡 Sprint Deadlines: E-mail (Dzień Odliczania 4)
3. 🟢 Sprint Administracyjny (Admin Sprint): Faktury

**Priorytet:** Raport → E-mail → Faktury
```

**Co robi:**
- Określa typ Sprintu (Pilny/Deadlines/Administracyjny/Kreatywny - Urgent/Deadlines/Admin/Creative)
- Sortuje po priorytecie (Dni Odliczania rosnąco / Lead Days ascending)

---

### **3. Dopasowanie Energii (Energy Matching)**

**Wklejasz:**
```
Mój wzorzec energii (energy pattern): Early Bird (wysoka energia rano / high energy AM)
Zadania dzisiaj:
1. Raport (Sprint Deadlines)
2. Faktury (Sprint Administracyjny / Admin Sprint)
```

**AI zwraca:**
```
**Plan dopasowany do energii:**

**9:00-11:00** (WYSOKA energia / HIGH energy) → 🟡 Sprint Deadlines: Raport
**11:00-11:20** → Odpoczynek (Recovery)
**14:00-14:30** (ŚREDNIA energia / MEDIUM energy) → 🟢 Sprint Administracyjny: Faktury

**Dlaczego:**
- Raport (zadanie fokusowe / focus task) → Twoja szczytowa energia (peak energy) - rano
- Faktury (rutynowe) → Średnia energia (Medium energy) - popołudnie wystarczy
```

**Co robi:**
- Dopasowuje Sprinty do wzorca energii (energy pattern)
- Dodaje czas odpoczynku (recovery time) - przerwy

---

### **4. Śledzenie Czasu (Time Tracking)**

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

**Spostrzeżenie (Insight):** Raporty zajmują Ci ~2 godziny. Następnym razem zaplanuj więcej czasu.
```

**Co robi:**
- Oblicza czas rzeczywisty
- Porównuje z oszacowaniem
- Daje spostrzeżenie (insight) - nauka dla przyszłości

---

### **5. Śledzenie Energii (Energy Tracking)**

**Wklejasz (przez tydzień):**
```
Pon: Rano 8/10, Popołudnie 5/10, Wieczór 3/10
Wt: Rano 9/10, Popołudnie 4/10, Wieczór 2/10
...
```

**AI zwraca (po tygodniu):**
```
**Twój wzorzec energii (energy pattern): Early Bird (poranna osoba) 🌅**
- Wysoka energia (High energy): Rano (9:00-12:00) - średnia 8.5/10
- Średnia energia (Medium energy): Popołudnie (14:00-17:00) - średnia 5/10
- Niska energia (Low energy): Wieczór (19:00+) - średnia 3/10

**Rekomendacje:**
Planuj zadania fokusowe (focus tasks) - Pilny/Deadlines (Urgent/Deadlines) - RANO (9:00-12:00).
```

**Co robi:**
- Analizuje energię przez tydzień
- Określa wzorzec (pattern) - Early Bird/Night Owl/Sinusoidal
- Daje rekomendacje (kiedy planować zadania fokusowe / focus tasks)

---

## 🔄 Typowy workflow z Planner AI

### **Poranek (Planowanie / Planning) - 5 minut**

**KROK 1: Przegląd zadań**

**Ty wklejasz:**
```
Dzisiaj: Czwartek, 10 stycznia
Mój wzorzec energii (energy pattern): Early Bird

Zadania:
1. Raport - deadline: Piątek (jutro)
2. E-mail - deadline: Poniedziałek (za 4 dni)
3. Prezentacja - deadline: Wtorek (za 5 dni)
4. Faktury - brak deadline
```

---

**AI zwraca:**
```
**Dni Odliczania (Lead Days) + Sprinty na dzisiaj:**

| Zadanie     | Dni Odliczania (Lead Days) | Sprint                               | Priorytet |
|-------------|----------------------------|--------------------------------------|-----------|
| Raport      | 1 🔴                       | Sprint Pilny (Urgent Sprint)         | 1         |
| E-mail      | 4 🟡                       | Sprint Deadlines (Deadlines Sprint)  | 2         |
| Prezentacja | 5 🟢                       | Sprint Kreatywny (Creative Sprint)   | 4         |
| Faktury     | - 🟢                       | Sprint Administracyjny (Admin Sprint)| 3         |

**Plan na dzisiaj (dopasowany do energii / energy-matched):**

**9:00-11:00** (WYSOKA energia / HIGH energy) → 🔴 Sprint Pilny (Urgent Sprint): Raport
  - Dzień Odliczania 1 (Lead Day 1) - CZERWONY (RED) - deadline JUTRO
  - Dokończ DZISIAJ (priorytet absolutny)

**11:00-11:20** → Odpoczynek (Recovery) - spacer, woda

**11:20-12:20** (WYSOKA energia / HIGH energy) → 🟡 Sprint Deadlines: E-mail
  - Dzień Odliczania 4 (Lead Day 4) - ŻÓŁTY (YELLOW) - zacznij lub zaplanuj

**12:20-13:00** → Odpoczynek (Recovery) - obiad

**14:00-14:30** (ŚREDNIA energia / MEDIUM energy) → 🟢 Sprint Administracyjny (Admin Sprint): Faktury
  - Rutynowe (średnia energia wystarczy)

**Prezentacja:** Dzień Odliczania 5 (Lead Day 5) - ZIELONY (GREEN) - przejrzyj za 2-3 dni (dzisiaj nie musisz)

**Kluczowy wniosek:**
Zacznij od Sprint Pilny (Urgent Sprint) - Raport. To CZERWONY (RED) - najwyższy priorytet.
```

**Czas:** 30 sekund (AI robi całe planowanie)

---

### **W trakcie dnia (Wykonanie / Execution)**

**KROK 2: Wykonujesz Sprinty**

- 9:00: Zaczynam Sprint Pilny (Urgent Sprint) - Raport
- 11:00: Dokończyłem Raport → Odpoczynek (Recovery) - spacer
- 11:20: Zaczynam Sprint Deadlines - E-mail
- 12:20: Dokończyłem E-mail → Odpoczynek (Recovery) - obiad
- 14:00: Zaczynam Sprint Administracyjny (Admin Sprint) - Faktury
- 14:30: Dokończyłem Faktury → Koniec pracy

**Śledzenie (Tracking) - opcjonalnie:**
- Zapisujesz czas każdego Sprintu (start → koniec)

---

### **Wieczór (Przegląd / Review) - 2 minuty**

**KROK 3: Śledzenie + Przegląd (Tracking + Review)**

**Ty wklejasz:**
```
Sprinty dzisiaj:
1. Sprint Pilny (Urgent Sprint): Raport - 9:00-11:00 (2 godz) - Oszacowanie: 1.5 godz
2. Sprint Deadlines: E-mail - 11:20-12:20 (1 godz) - Oszacowanie: 1 godz
3. Sprint Administracyjny (Admin Sprint): Faktury - 14:00-14:30 (30 min) - Oszacowanie: 30 min

Energia dzisiaj:
Rano: 9/10
Popołudnie: 6/10
Wieczór: 3/10
```

**AI zwraca:**
```
**Sprinty - Śledzenie (Tracking):**

**Raport:**
- Czas: 2 godz (Oszacowanie: 1.5 godz)
- Różnica: +30 min (1.33x dłużej)
- Spostrzeżenie (Insight): Raporty zajmują Ci trochę dłużej - zaplanuj 2 godziny następnym razem.

**E-mail:**
- Czas: 1 godz (Oszacowanie: 1 godz)
- ✅ Zgodne z oszacowaniem

**Faktury:**
- Czas: 30 min (Oszacowanie: 30 min)
- ✅ Zgodne z oszacowaniem

**Energia:**
Dzisiaj: Wzorzec Early Bird (pattern) - rano 9, popołudnie 6, wieczór 3 - zgodne z Twoim standardem.

**Podsumowanie:**
✅ Dokończone: 3/3 Sprinty (100%)
✅ Sprint Pilny (Urgent Sprint) - Raport - zrobione (done) - deadline jutro, bez stresu!
✅ Dopasowanie energii (Energy matching) - Sprinty dopasowane do energii (dobry plan)
```

**Czas:** 1 minuta (AI robi summary)

---

## 🧩 Przykłady użycia (real scenarios)

### **Scenariusz 1: "Chaos - za dużo zadań"**

**Sytuacja:**
- Masz 10 zadań
- Nie wiesz, od czego zacząć
- Przytłoczenie (overwhelm) - paraliż

**Rozwiązanie z Planner AI:**

**Ty wklejasz:**
```
Zadania (chaos!):
1. Raport - deadline jutro
2. E-mail szef - deadline dzisiaj
3. Prezentacja - deadline za tydzień
4. Faktury - brak deadline
5. Przygotowanie do spotkania (Meeting prep) - spotkanie za 2 dni
6. Przegląd kodu (Code review) - deadline za 3 dni
7. Dokumentacja (Documentation) - brak deadline
8. Naprawa błędu (Bug fix) - pilne (urgent) - klient czeka
9. Nauka (kurs) - brak deadline
10. Porządki (Cleanup) - brak deadline
```

**AI zwraca:**
```
**Dni Odliczania (Lead Days) + Priorytety:**

| Zadanie               | Dni Odliczania (Lead Days) | Pilność (Urgency) | Priorytet |
|-----------------------|----------------------------|-------------------|-----------|
| E-mail szef           | 0 🔴                       | CZERWONY (RED)    | 1         |
| Naprawa błędu         | 0 🔴                       | CZERWONY (RED)    | 2         |
| Raport                | 1 🔴                       | CZERWONY (RED)    | 3         |
| Przygotowanie spotkań | 2 🟡                       | ŻÓŁTY (YELLOW)    | 4         |
| Przegląd kodu         | 3 🟡                       | ŻÓŁTY (YELLOW)    | 5         |
| Prezentacja           | 7 🟢                       | ZIELONY (GREEN)   | 6         |
| Faktury               | - 🟢                       | ZIELONY (GREEN)   | 7         |
| Dokumentacja          | - 🟢                       | ZIELONY (GREEN)   | 8         |
| Porządki              | - 🟢                       | ZIELONY (GREEN)   | 9         |
| Nauka                 | - 🟢                       | ZIELONY (GREEN)   | 10        |

**DZISIAJ robisz (MAX 3!):**
1. 🔴 E-mail szef (CZERWONY / RED - deadline DZISIAJ)
2. 🔴 Naprawa błędu (Bug fix) - CZERWONY / RED - klient czeka
3. 🔴 Raport (CZERWONY / RED - deadline jutro)

**Resztę:**
- Przygotowanie spotkań (ŻÓŁTY / YELLOW) - zrobisz JUTRO (jeszcze czas)
- Przegląd kodu (ŻÓŁTY / YELLOW) - zrobisz pojutrze
- Prezentacja, Faktury, Dokumentacja, Porządki, Nauka (ZIELONY / GREEN) - zrobisz PÓŹNIEJ (nie dzisiaj!)

**Kluczowy wniosek:**
**Tylko 3 zadania dzisiaj** (CZERWONE / RED). Reszta POCZEKA. Nie próbuj robić wszystkiego.
```

**Rezultat:**
- Chaos → jasność (clarity) - 3 zadania, jasny plan
- Zero przytłoczenia (overwhelm) - wiesz, co ignorować
- Priorytet: zadania CZERWONE (RED tasks) - najpilniejsze

---

### **Scenariusz 2: "Mam czas, ale nie zaczynam"**

**Sytuacja:**
- Prezentacja za 10 dni (dużo czasu)
- Nie zaczynam (brak pilności / urgency)
- Ślepota czasowa (time blindness) - "mam czas" → za 2 dni panika

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
- Dni Odliczania (Lead Days): **10 Dni Odliczania** (🟢 ZIELONY / GREEN)

**Czy zacząć dzisiaj?**
**Nie musisz** (ZIELONY / GREEN - niska pilność / low urgency). ALE:

**Mikro-zobowiązania (Micro-commitments) - jeśli chcesz:**
Jeśli prezentacja jest duża (>2 godziny pracy), rozbij na mikro-zobowiązania (micro-commitments):

1. **Dzisiaj (10 Dni Odliczania - ZIELONY / GREEN):** Zbierz materiały (10 min)
2. **Za 3 dni (7 Dni Odliczania - ZIELONY / GREEN):** Szkic (Outline) - 30 min
3. **Za 5 dni (5 Dni Odliczania - ZIELONY → ŻÓŁTY / GREEN → YELLOW):** Wersja robocza slajdów (Draft) - 1 godz
4. **Za 7 dni (3 Dni Odliczania - ŻÓŁTY / YELLOW):** Dopracowanie (1 godz)
5. **Za 9 dni (1 Dzień Odliczania - CZERWONY / RED):** Finalizacja (30 min)

**Dlaczego rozbić:**
- Prezentacja = duże zadanie (task) → łatwo odkładać (brak pilności / urgency)
- Mikro-zobowiązania (Micro-commitments) = małe kroki → łatwiej zacząć
- Każdy krok ma swój Dzień Odliczania (Lead Day) → pilność (urgency) rośnie stopniowo

**Rekomendacja:**
Dzisiaj zrób **10 min: Zbierz materiały** (absurdalnie małe / ridiculous small). To wystarczy.
```

**Rezultat:**
- Wiesz, kiedy zacząć (nie dzisiaj - ZIELONY / GREEN)
- Masz plan (mikro-zobowiązania / micro-commitments)
- Unikasz pośpiechu w ostatniej chwili (last-minute rush) - rozłożone w czasie

---

### **Scenariusz 3: "Nie mam energii na nic"**

**Sytuacja:**
- Masz zadania (ŻÓŁTY / YELLOW - średnia pilność / medium urgency)
- Zero energii (zmęczenie, niski dzień / low day)
- Czy robić?

**Rozwiązanie z Planner AI:**

**Ty wklejasz:**
```
Zadania dzisiaj:
1. Raport - Dzień Odliczania 3 (Lead Day 3) - ŻÓŁTY (YELLOW)
2. E-mail - Dzień Odliczania 4 (Lead Day 4) - ŻÓŁTY (YELLOW)

Ale: Energia 2/10 (bardzo niska). Co robić?
```

**AI zwraca:**
```
**Energia 2/10 (bardzo niska):**

**Opcja 1: Odpoczynek (Recovery) - REKOMENDOWANE**
- Jeśli energia 2/10 → **odpoczynek priorytetem**
- Nie próbuj robić zadań fokusowych (focus tasks) - Sprint Deadlines - będziesz walczyć
- **Odpoczynek (Recovery):** spacer, natura, krótka drzemka (power nap) - 15-20 min, nawodnienie (hydration)

**Dlaczego:**
- Mózg z ADHD z niską energią (ADHD brain with low energy) = nieskuteczność (walka)
- Lepiej odpocząć DZIŚ + zrobić jutro DOBRZE niż dziś ŹLE

---

**Opcja 2: Sprint Administracyjny (Admin Sprint) - jeśli MUSISZ coś zrobić**
- Jeśli nie możesz odpoczywać → **Sprint Administracyjny (Admin Sprint)** - zadania niskiej energii (low energy tasks)
- Przykłady: faktury, e-maile (nie wymagające myślenia), porządki (cleanup)

**NIE:**
- ❌ Raport (zadanie fokusowe / focus task - potrzebujesz wysokiej energii / high energy)
- ❌ E-mail (jeśli wymaga myślenia)

**TAK:**
- ✅ Faktury (rutynowe)
- ✅ Porządki (Cleanup) - bezmyślne (mindless)

---

**Co z Raportem i E-mailem?**
- Dzień Odliczania 3-4 (Lead Day 3-4) - ŻÓŁTY (YELLOW) - **masz jeszcze czas** (nie CZERWONY / RED!)
- Zrób jutro (gdy energia wróci)
- To nie jest deadline dzisiaj → OK odłożyć

**Kluczowy wniosek:**
**Odpoczynek (Recovery) > produktywność** (jeśli energia 2/10). Odpoczynek = inwestycja w jutrzejszą energię.
```

**Rezultat:**
- Wiesz, że możesz odpocząć (nie wina)
- Nie walczysz z niską energią (low energy) - dajesz sobie przyzwolenie
- Jutro będzie lepiej (po odpoczynku / recovery)

---

## ❓ FAQ (najczęstsze pytania)

### **1. Czy muszę trackować czas/energię codziennie?**

**Odpowiedź:**
**Nie musisz** (to nie obowiązek).

**Kiedy śledzić (trackować):**
- **Czas:** Jeśli chcesz nauczyć się realnych czasów (koniec błędu optymizmu / optimism bias) → śledź przez 1-2 tygodnie, potem możesz przestać
- **Energię:** Jeśli nie znasz swojego wzorca (pattern) → śledź przez 1 tydzień (poznasz swój rytm), potem możesz przestać

**Kiedy nie śledzić (trackować):**
- Jeśli już znasz swój wzorzec (pattern) - np. wiesz, że jesteś Early Bird
- Jeśli już wiesz, ile trwają Twoje zadania (taski) - dobre oszacowanie

**Kluczowe:**
> Śledzenie (Tracking) = **narzędzie do nauki** (nie cel sam w sobie). Uczysz się → przestajesz śledzić.

---

### **2. Co jeśli nie dokończę Sprintu?**

**Odpowiedź:**
**To OK** (nie musisz dokończyć wszystkiego).

**Co robić:**
1. **Zapisz postęp (progress)** - gdzie skończyłeś
2. **Oceń Dzień Odliczania (Lead Day)** - czy to CZERWONY (RED)? → musisz kontynuować jutro
3. **Sprawdź energię** - czy masz? → kontynuuj lub odpoczynek

**Przykład:**
- Sprint: Raport (Dzień Odliczania 1 / Lead Day 1 - CZERWONY / RED)
- Zrobiłeś 50% (nie dokończyłeś)
- **Jutro deadline** → musisz kontynuować JUTRO (priorytet)

**Jeśli ŻÓŁTY/ZIELONY (YELLOW/GREEN):**
- Możesz odłożyć (nie CZERWONY / RED) → zrobisz później

**Kluczowe:**
> Nie dokończenie ≠ porażka. Mózg z ADHD (ADHD brain) ma zmienne energie - **elastyczność (flexibility) OK**.

---

### **3. Co jeśli pojawi się pilne zadanie (urgent task) - nie planowane?**

**Odpowiedź:**
**Oceń Dzień Odliczania (Lead Day)** - czy to CZERWONY (RED)?

**Jeśli CZERWONY (RED) - deadline dzisiaj/jutro:**
- **Dodaj do Sprint Pilny (Urgent Sprint)** - priorytet
- Przesuń inne zadania (jeśli muszisz)

**Jeśli ŻÓŁTY/ZIELONY (YELLOW/GREEN):**
- **Zapisz** (nie rób dzisiaj, jeśli masz zadania CZERWONE / RED tasks)
- Zrobisz, gdy stanie się CZERWONY (RED)

**Przykład:**
- Planujesz: Raport (CZERWONY / RED)
- Pojawia się: Naprawa błędu (Bug fix) - klient czeka - CZERWONY (RED)
- **Dodaj Bug fix do Sprint Pilny (Urgent Sprint)** - najpierw Bug fix, potem Raport

**Kluczowe:**
> Planner AI = **elastyczność (flexibility)** - nie sztywny plan (rigid plan). Możesz dodawać/przesuwać zadania (Dni Odliczania / Lead Days określają priorytet).

---

### **4. Co jeśli mam tylko ZIELONE zadania (GREEN tasks) - brak deadline?**

**Odpowiedź:**
**Wybierz przez 4 C's** (motywacja ADHD).

**Pytania:**
1. **Zafascynowanie (Captivate):** Co mnie INTERESUJE dzisiaj?
2. **Tworzenie (Create):** Co jest NOWE/kreatywne?
3. **Rywalizacja (Compete):** Co jest WYZWANIEM?
4. **Zakończenie (Complete):** Które mogę DOKOŃCZYĆ dzisiaj? (małe zadanie)

**Przykład:**
- Zadania ZIELONE (GREEN): Faktury, Dokumentacja, Nauka, Porządki (Cleanup)
- **Zafascynowanie (Captivate):** Nauka (interesuję się tym dzisiaj)
- **Zacznij od Nauka** (dopamina z Zafascynowania / Captivate)

**Kluczowe:**
> Zadania ZIELONE (GREEN tasks) = brak pilności (urgency) → użyj **4 C's** (alternatywna motywacja).

---

### **5. Czy Planner AI działa dla każdego?**

**Odpowiedź:**
**Działa dla większości ADHD**, ale:

**Działa najlepiej, jeśli:**
- ✅ Masz zadania z deadlines (Dni Odliczania / Lead Days = pilność / urgency)
- ✅ Chcesz struktury (ale elastyczność / flexibility)
- ✅ Motywujesz się przez pilność (urgency) - Zakończenie / Complete (jeden z 4 C's)

**Może nie działać, jeśli:**
- ⚠️ Wszystkie zadania bez deadline (brak pilności / urgency → użyj 4 C's zamiast Dni Odliczania / Lead Days)
- ⚠️ Wolisz "idź z flow" (zero planowania - to OK, Planner nie dla Ciebie)
- ⚠️ Przytłacza Cię planowanie (overwhelm) - użyj uproszczoną wersję: tylko CZERWONY/ŻÓŁTY/ZIELONY (RED/YELLOW/GREEN), bez śledzenia (tracking)

**Kluczowe:**
> Planner AI = **narzędzie** (nie konieczność / must). Testuj, dopasuj do siebie, modyfikuj.

---

## 📋 Podsumowanie

### **Kluczowe wnioski:**

1. **Planner AI = System Odliczania Dni (Lead Days) + Sprinty + Zarządzanie Energią (Energy Management)**
   - Liczy Dni Odliczania (Lead Days) - pilność (urgency)
   - Określa Sprinty (typy zadań)
   - Dopasowuje do energii (energy matching)
   - Dodaje odpoczynek (recovery) - przerwy

2. **2 opcje:**
   - **Custom GPT:** Szybkie, zero konfiguracji (setup) - wymaga Plus
   - **Projekt (ChatGPT/Claude):** DARMOWY, z pamięcią (5 min konfiguracji / setup)

3. **Funkcje:**
   - Kalkulator Dni Odliczania (Lead Days Calculator) - poziomy pilności (urgency levels)
   - Planer Sprintów (Sprint Planner) - typy zadań + priorytet
   - Dopasowanie Energii (Energy Matching) - dopasowanie do rytmu
   - Śledzenie Czasu (Time Tracking) - oszacowanie vs realne
   - Śledzenie Energii (Energy Tracking) - wzorzec (pattern) przez tydzień

4. **Typowy przepływ pracy (workflow):**
   - **Poranek:** Przegląd zadań (5 min) - AI planuje dzień
   - **W trakcie:** Wykonujesz Sprinty (priorytet CZERWONY → ŻÓŁTY / RED → YELLOW)
   - **Wieczór:** Przegląd (Review) - 2 min - AI śledzi + spostrzeżenia (insights)

5. **Rzeczywiste scenariusze (Real scenarios):**
   - Chaos (10 zadań) → AI priorytetyzuje (3 CZERWONE / RED dzisiaj, reszta później)
   - "Mam czas" (ZIELONY / GREEN) → AI rozbija na mikro-zobowiązania (micro-commitments)
   - Niska energia (Low energy) → AI rekomenduje odpoczynek (recovery) - nie walka

6. **FAQ:**
   - Nie musisz śledzić (trackować) codziennie (tylko do nauki)
   - Nie dokończenie Sprint = OK (elastyczność / flexibility)
   - Pilne zadanie (Urgent task) → dodaj (Dni Odliczania / Lead Days określają priorytet)
   - Zadania ZIELONE (GREEN tasks) → wybierz przez 4 C's
   - Planner nie dla każdego (testuj, dopasuj)

---

## ✅ Zadanie do wykonania

**Jutro rano:**

1. **Wybierz opcję:**
   - Custom GPT (link w materiale) lub Projekt (instrukcje w materiale)

2. **Użyj Planner AI:**
   - Wklej wszystkie zadania (z deadlines)
   - Zobacz Dni Odliczania (Lead Days) + Sprinty
   - Zacznij od najwyższego priorytetu (CZERWONY/ŻÓŁTY - RED/YELLOW)

3. **Wieczorem:**
   - Tracking (ile czasu zajęły Sprinty?)
   - Czy oszacowanie było dobre?

**Testuj przez tydzień** → Sprawdź, czy Planner AI działa dla Ciebie.

---

## ➡️ Co dalej?

**Moduł 5: Micro-Start Coach + Body Doubling AI**
- Jak zacząć, gdy nie możesz zacząć (paraliż wykonawczy)
- Mikro-start (Micro-start) - absurdalnie mały pierwszy krok (ridiculous small first step)
- Body Doubling AI (AI jako towarzysz / companion)
- Jak używać AI do "bycia z Tobą" podczas pracy

---

**Autor:** Przemek
**Moduł:** 4 - Planner AI - System Odliczania Dni (Lead Days) + Sprinty (Sprints)
**Źródła:** Ruri Ohama (System Odliczania Dni / Lead Day System + Metoda Sprintów / Sprint Method), praktyczne testy z społecznością ADHD (ADHD community)
**Wersja:** V0
**Data:** 2025-01-XX
