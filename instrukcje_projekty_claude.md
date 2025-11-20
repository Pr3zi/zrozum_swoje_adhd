# Instrukcje: Projekty w Claude dla ADHD AI

**Wersja:** V0
**Data:** 2025-01-20
**Dla:** Użytkownicy pakietu "Zrozum Swoje ADHD z AI"

---

## 🎯 Czym są projekty w Claude i dlaczego są lepsze?

**Projekty w Claude** to prywatna przestrzeń robocza, która:

✅ **Pamięta kontekst** - każda rozmowa w projekcie ma dostęp do Twojego profilu
✅ **Pozwala dodawać pliki** - profil kontekstowy, testy osobowości, notatki
✅ **Ma własne instrukcje** - możesz dostosować AI pod siebie
✅ **Działa offline** - nie potrzebujesz linków do Custom GPT
✅ **Pełna prywatność** - wszystko zostaje u Ciebie

### **Porównanie:**

| Feature | Custom GPT | Projekty Claude |
|---------|------------|-----------------|
| Dodawanie plików | ❌ | ✅ |
| Pamięć kontekstu | Ograniczona | Pełna |
| Własne instrukcje | ❌ | ✅ |
| Wymaga Plus | ✅ ($20/msc) | ✅ ($20/msc) lub darmowe (limit) |
| Aktualizacja profilu | Ręczne wklejanie | Automatyczna (edytujesz plik) |

**Rekomendacja:** Jeśli masz Claude Pro - używaj projektów. Jeśli nie - Custom GPT są ok na start.

---

## 📋 KROK 1: Stwórz projekt w Claude

### **1.1. Wejdź na claude.ai**

Zaloguj się na swoje konto (darmowe lub Claude Pro).

### **1.2. Przejdź do zakładki "Projects"**

- Lewa strona ekranu
- Kliknij "Projects"
- Jeśli nie widzisz: kliknij swoje zdjęcie/inicjały → "Feature Preview" → włącz "Projects"

### **1.3. Stwórz nowy projekt**

- Kliknij **"Create Project"**
- **Nazwa:** "ADHD AI - Mój Asystent"
- **Opis (opcjonalnie):** "Narzędzia AI do zarządzania ADHD - Klarowność, Decyzje, Plan Dnia, Emocje, Micro-Start"
- Kliknij **"Create"**

---

## 📄 KROK 2: Dodaj Profil Kontekstowy

### **2.1. Stwórz swój profil (jeśli jeszcze nie masz)**

Opcja A: **Custom GPT "Profil Kontekstowy ADHD"**
1. Wejdź do GPT (link w pakiecie)
2. Wybierz: "Szybki profil" (5 min) lub "Pełny profil" (15 min)
3. Odpowiedz na pytania
4. Skopiuj wygenerowany profil (markdown)

Opcja B: **Użyj szablonu** (wypełnij ręcznie)
- Pobierz szablon `szablon_profil_kontekstowy.md` (w pakiecie)
- Wypełnij sekcje
- Zapisz jako plik `.md` lub `.txt`

### **2.2. Dodaj profil do projektu**

**Opcja A: Wklej jako tekst**
1. W projekcie kliknij **"Add content"**
2. Wybierz **"Paste text"**
3. Wklej swój profil
4. **Nazwa:** "Mój Profil Kontekstowy"
5. Kliknij **"Add"**

**Opcja B: Dodaj jako plik**
1. Zapisz profil jako plik `.md` lub `.txt` na komputerze
2. W projekcie kliknij **"Add content"** → **"Upload file"**
3. Wybierz plik
4. Kliknij **"Add"**

---

## 🛠️ KROK 3: Dodaj instrukcje systemowe

### **3.1. Skopiuj szablon instrukcji**

W pakiecie znajdziesz plik: **`szablon_instrukcje_claude_projekt.md`**

Ten plik zawiera:
- Instrukcje dla Claude, jak działać
- 5 trybów/narzędzi (Klarowność, Decyzje, Plan Dnia, Emocje, Micro-Start)
- Integrację z profilem kontekstowym
- Mapowanie na IPO
- Język z kursu

### **3.2. Dodaj do projektu**

1. Otwórz plik `szablon_instrukcje_claude_projekt.md`
2. Skopiuj **CAŁĄ zawartość**
3. W projekcie kliknij **"Project instructions"** (prawy górny róg)
4. Wklej szablon
5. Kliknij **"Save"**

**GOTOWE!** Teraz Twój projekt ma:
- ✅ Profil kontekstowy (wie, kim jesteś)
- ✅ Instrukcje systemowe (wie, jak Ci pomagać)
- ✅ 5 narzędzi (Klarowność, Decyzje, Plan Dnia, Emocje, Micro-Start)

---

## 🎮 KROK 4: Jak używać narzędzi w projekcie

### **Sposób 1: Wybierz tryb na początku rozmowy**

Gdy wchodzisz do projektu, po prostu powiedz:

```
"Tryb: Klarowność"
```

lub

```
"Tryb: Decyzje"
```

AI automatycznie przełączy się w odpowiedni tryb.

### **Sposób 2: Opisz problem, AI rozpozna tryb**

Jeśli nie wiesz, którego trybu użyć, po prostu opisz problem:

```
"Mam chaos w głowie, za dużo myśli naraz."
```

AI rozpozna, że to **INPUT overload** i przełączy w **Tryb Klarowności**.

---

## 🧰 DOSTĘPNE NARZĘDZIA (tryby w projekcie)

### **1. Tryb: Klarowność** ⭐
**Kiedy używać:** Chaos w głowie, natłok myśli, za dużo naraz
**Co robi:**
- Porządkuje chaos
- Zamyka otwarte pętle
- Tworzy priorytety
- Daje spokój

**Jak aktywować:**
```
"Tryb: Klarowność"
```

---

### **2. Tryb: Decyzje**
**Kiedy używać:** Nie mogę się zdecydować, paraliż decyzyjny
**Co robi:**
- Analizuje opcje
- Daje 3 wybory (najprostsza, najszybsza, najważniejsza)
- Pomaga wybrać jedną rzecz

**Jak aktywować:**
```
"Tryb: Decyzje"
```

---

### **3. Tryb: Plan Dnia**
**Kiedy używać:** Nie wiem, co robić dzisiaj, brak struktury
**Co robi:**
- Tworzy plan dnia dostosowany do Twojego profilu dopaminowego
- Uwzględnia energię (poranna/wieczorna osoba)
- Rozbija zadania na micro-kroki

**Jak aktywować:**
```
"Tryb: Plan Dnia"
```

---

### **4. Tryb: Emocje**
**Kiedy używać:** Silna emocja (złość, lęk, frustracja), RSD
**Co robi:**
- Odbiera emocję
- Daje 3 neutralne perspektywy (reframing)
- Oddziela fakt od interpretacji

**Jak aktywować:**
```
"Tryb: Emocje"
```

---

### **5. Tryb: Micro-Start**
**Kiedy używać:** Wiem, co robić, ale nie mogę zacząć (paraliż wykonawczy)
**Co robi:**
- Generuje pierwszy atomowy krok (30 sekund)
- Prowadzi krok po kroku (body doubling)
- Utrzymuje ruch

**Jak aktywować:**
```
"Tryb: Micro-Start"
```

---

## 💡 PRZYKŁADY UŻYCIA

### **Przykład 1: Klarowność**

```
User: "Tryb: Klarowność"

AI: "Cześć [imię z profilu]! Przełączam w Tryb Klarowności.
Widzę z Twojego profilu, że Twój główny bottleneck to INPUT (za dużo myśli naraz).

Co konkretnie czujesz jako chaotyczne dzisiaj?"

User: "Mam milion rzeczy: pranie, klient, rachunki, mama, prezentacja..."

AI: [porządkuje w strukturę]
✅ PRIORYTETY (dziś):
1. Rachunek za prąd (deadline)
2. Prezentacja (pilne)

⏸️ PARKUJ (ten tydzień):
3. Pranie
4. Odpisać mamie

🗑️ ODPUŚĆ:
5. Klient (dopytaj: kiedy deadline?)

🎯 JEDNA RZECZ TERAZ: Zapłać rachunek (5 min)
```

---

### **Przykład 2: Micro-Start**

```
User: "Tryb: Micro-Start. Muszę napisać raport, ale nie mogę zacząć."

AI: "Cześć! Widzę z profilu, że masz problem z OUTPUT (paraliż wykonawczy).
Zróbmy micro-start - pierwszy krok tak mały, że zajmie 30 sekund.

Krok 1 (30 sek): Otwórz pusty dokument i napisz tytuł raportu. Tylko tytuł.

Zrobiłeś?"

User: "Tak."

AI: "Świetnie! To jest micro-win - Twój mózg dostał dopaminę.

Krok 2 (1 min): Napisz jedno zdanie: 'Ten raport dotyczy...'
Nie musi być dobre - po prostu napisz."
```

---

## 🔄 AKTUALIZACJA PROFILU

Twój profil może się zmieniać w czasie. Możesz go aktualizować:

### **Opcja 1: Edytuj plik w projekcie**

1. W projekcie znajdź "Mój Profil Kontekstowy"
2. Kliknij **"Edit"**
3. Zmień sekcje (np. nowy cel, inne środowisko)
4. **"Save"**

### **Opcja 2: Dodaj nowy plik**

1. Stwórz nowy profil (GPT lub ręcznie)
2. Dodaj jako nowy plik: "Profil Kontekstowy - Aktualizacja [data]"
3. Stary profil możesz usunąć lub zostawić (historia)

---

## 📁 DODAWANIE INNYCH PLIKÓW

Możesz dodać do projektu:

- **Testy osobowości** (16 Personalities, DISC, Enneagram)
- **Notatki z terapii** (jeśli chcesz, żeby AI to uwzględniało)
- **Cele i plany** (miesięczne, kwartalne)
- **Lista zadań** (TODO list)
- **Dziennik nastroju** (tracking sinusoid energii)

**Jak dodać:**
1. "Add content" → "Upload file"
2. Wybierz plik (.txt, .md, .pdf, .docx)
3. AI automatycznie przeczyta i użyje w odpowiedziach

---

## 🚀 ZAAWANSOWANE: Własne instrukcje

Jeśli chcesz dostosować instrukcje pod siebie:

1. "Project instructions" → Edit
2. Dodaj swoje zasady, np.:
   ```
   - Zawsze pytaj mnie o przerwę po 25 minutach (Pomodoro)
   - Przypominaj mi o nawodnieniu
   - Nie sugeruj zadań po 20:00 (wieczorna osoba)
   - Używaj prostych, krótkich zdań
   ```
3. Save

AI będzie przestrzegać Twoich zasad.

---

## ❓ FAQ

### **Czy muszę mieć Claude Pro?**

Nie. Projekty działają też na **darmowym planie Claude**, ale masz limit:
- Claude Free: ~5-10 projektów, limit wiadomości (reset co 24h)
- Claude Pro: nielimitowane projekty i wiadomości

### **Czy mogę mieć kilka projektów?**

Tak! Możesz mieć osobne projekty na:
- Pracę (ADHD AI - Praca)
- Życie osobiste (ADHD AI - Dom)
- Naukę (ADHD AI - Studia)

### **Czy mogę udostępnić projekt komuś?**

Nie. Projekty są prywatne. Ale możesz:
- Wyeksportować profil (skopiuj tekst) → wyślij komuś
- Ktoś może stworzyć własny projekt z Twoimi instrukcjami

### **Co jeśli zgubię profil?**

Profil jest zapisany w projekcie. Możesz:
1. Wejść do projektu → "Mój Profil Kontekstowy" → skopiować
2. Zapisać kopię na dysku (backup)

### **Czy mogę używać projektów na telefonie?**

Tak! Aplikacja Claude (iOS/Android) wspiera projekty.

---

## 🎁 BONUS: Gotowe szablony

W pakiecie znajdziesz:

- ✅ `szablon_profil_kontekstowy.md` - do wypełnienia ręcznie
- ✅ `szablon_instrukcje_claude_projekt.md` - instrukcje systemowe (5 trybów)
- ✅ `przykład_profil_przemek.md` - przykład wypełnionego profilu (Przemek)
- ✅ `przykład_rozmowa_klarownosc.md` - przykład użycia trybu Klarowności

---

## 📞 Wsparcie

Masz problem? Pytania?

- Kanał **#pomoc-projekty-claude** w społeczności (Skool)
- DM do @Przemek

---

**Powodzenia!** 🚀

---

**Autor:** Przemek
**Kurs:** Zrozum Swoje ADHD z AI
**Wersja:** V0
**Data:** 2025-01-20
