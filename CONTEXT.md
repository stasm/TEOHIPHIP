Oto skondensowane podsumowanie dotychczasowej pracy nad TEOHIPHIP, które posłuży jako punkt wyjścia do dalszych dyskusji z AI lub innymi współpracownikami. Chodzi o uchwycenie kluczowych decyzji projektowych i aktualnego stanu systemu, bez wchodzenia w pełne szczegóły zawarte w podręcznikach czy liście cech.

---

**Braindump Kontekstowy: Projekt TEOHIPHIP (Stan na 02.05.2025)**

**1. Wizja Projektu:**

* **Główny Fokus:** TEOHIPHIP jest **taktyczną grą skirmishową z elementami RPG**.
* **Setting:** Osadzony w absurdalnym, pełnym czarnego humoru i biurokracji świecie podróży w czasie inspirowanym "Podróżą dwudziestą" Stanisława Lema (Instytut Temporystyki - INT, projekt TEOHIPHIP).
* **Rdzeń Rozgrywki:** Gracze kontrolują **bandy (1-3 agentów INT)** w krótkich (5-6 rund), **celowych scenariuszach skirmishowych** (potyczkach) rozgrywanych na mapie z figurkami/znacznikami.
* **Kluczowe Elementy:** Połączenie taktycznej walki, realizacji celów misji, zarządzania ryzykiem (Pula Inicjatywy), unikalnych postaci (system Cech) i klimatu Lema (absurd, chaos, technologia, paradoksy).

**2. Podstawowa Mechanika:**

* **System:** Zmodyfikowany **tinyd6**.
* **Testy:** 2k6 (standard), 3k6 (Przewaga - wybierz 2), 1k6 (Utrudnienie). Sukces na 5 lub 6.
* **Punkty Akcji (AP):** Każda postać ma **2 AP** na aktywację do wydania na akcje (Ruch, Atak, Celowanie, Krycie się, Interakcja itp.).
* **Skirmishowe Zasady Terenu:** Proste zasady dla Ruchu (SPD, Trudny Teren), Linii Wzroku (True LoS, Ukrycie = Utrudnienie), Osłony (ignorowanie 1 sukcesu).

**3. Kluczowe Podsystemy:**

* **System Band:** Gracze tworzą i kontrolują bandy 1-3 postaci, wykorzystując **12 Punktów Kreacji (PK)** na start (1 PK = 1 PŻ lub 3 PC). Rozmiar bandy wpływa na liczbę aktywacji i indywidualną siłę postaci.
* **System Cech:** Rozbudowana lista Cech Pozytywnych (koszt w PC) i Negatywnych (dają PC) pozwala tworzyć unikalne postacie. Cechy mają bezpośredni wpływ mechaniczny (Przewaga/Utrudnienie, modyfikacje statystyk, specjalne zdolności).
* **Pula Inicjatywy:** Centralna mechanika taktyczna służąca zarządzaniu ryzykiem. Na początku rundy postać rzuca k6 równymi jej **aktualnym PŻ**. Gracz może **wydać 1 PŻ**, aby po wykonaniu Testu podmienić 1 kość z rzutu na 1 kość z puli.
* **Automatyzacja BN:** Przeciwnicy (BN) działają według **predefiniowanych algorytmów** (list priorytetów), aby odciążyć MG/Arbitra i przyspieszyć grę. Istnieje opcjonalna zasada pozwalająca graczom aktywować BN-y według algorytmów.

**4. Kampania i Progresja:**

* **Struktura:** Seria połączonych potyczek skirmishowych.
* **Faza "Pomiędzy Misjami":**
    * PŻ postaci **resetują się do maksimum**.
    * Ekwipunek **resetuje się** do standardu misyjnego (nie jest śledzony).
    * Bandy zdobywają **Punkty Kreacji (PK): 3 PK za wygraną, 1 PK za przegraną/remis** (jeśli banda przetrwała), 0 PK za całkowitą eliminację.
    * PK można wydać **tylko** na **nowe Cechy Pozytywne** (1 PK = 3 PC) lub **nowe postacie** (1 PK = 1 PŻ, min 4 PK). **Nie można kupować PŻ bezpośrednio.**
    * Niewykorzystane PK kumulują się.
    * **Całkowita Eliminacja Bandy:** Gracz otrzymuje **12 PK** na stworzenie nowej bandy od zera (traci poprzedni postęp).
    * (Opcjonalnie) Możliwość wykupienia Cech Negatywnych za wysoki koszt PK.

**5. Dokumentacja Projektu:**

* `README.md`: Zaktualizowany opis projektu.
* `CONTEXT.md`: Krótkie podsumowanie projektu, jego celów i aktualnego stanu, na potrzeby rozmów z AI lub współpracownikami.
* Dokumentacja została zorganizowana w katalogi tematyczne w folderze `src` w formacie **mdbook** dla lepszej organizacji i prezentacji treści.
  * `SUMMARY.md` definiuje strukturę spisu treści dla mdbooka.
  * `index.md` - Ogólny wstęp do gry i świata.
  * `start.md` - Pierwsze kroki w grze dla nowych graczy.
  * `gracz/` - Podręcznik Gracza z zasadami tworzenia band i prowadzenia potyczek.
    * `index.md` - Wprowadzenie do podręcznika gracza.
    * `świat.md` - Opis świata gry.
    * `banda.md` - Tworzenie bandy i zasady potyczek.
    * `potyczka.md` - Zasady potyczek skirmishowych.
    * `kampania.md` - Zasady kampanii i progresji.
    * `porady.md` - Porady dla graczy.
  * `mg/` - Podręcznik Mistrza Gry z zasadami prowadzenia gry.
    * `index.md` - Wprowadzenie do podręcznika mistrza gry.
    * `świat.md` - Opis świata gry z perspektywy MG.
    * `potyczka.md` - Zasady prowadzenia potyczek skirmishowych.
    * `bn.md` - Profile BN i zasady ich automatyzacji.
    * `kampania.md` - Zasady kampanii i progresji z perspektywy MG.
    * `scenariusze.md` - Tworzenie scenariuszy i tabele pomocnicze.
    * `tabele.md` - Tabele pomocnicze dla MG.
  * `scenariusze/` - Przykładowe misje do wykorzystania w grze.
  * `cechy.md` - Lista cech postaci, pogrupowanych w kategorie tematyczne.
  * `karta.md` - Karta postaci do wykorzystania w grze.
  * `słowniczek.md` - Słownik terminów i pojęć używanych w grze.
* Plik `book.toml` zawiera konfigurację mdbooka.
* Skonfigurowano GitHub Actions do automatycznego budowania i publikowania mdbooka.
* *Pliki projektowe (`designs`)*: Wcześniejsze notatki i wersje rozwojowe mechanik.

**6. Kluczowe Decyzje Projektowe Podjęte w Trakcie Rozmowy:**

* Ostateczne przejście z modelu RPG na **skirmish z elementami RPG**.
* Wprowadzenie **Systemu Band** jako podstawy (1-3 postacie na gracza, 12 PK na start).
* Zaimplementowanie mechaniki **Puli Inicjatywy** (kości=PŻ, koszt 1 PŻ za wymianę).
* Opracowanie **zasad skirmishowych** (2 AP, akcje, LoS, Osłona itp.).
* Wprowadzenie **Automatyzacji BN** za pomocą algorytmów (z opcją kontroli przez graczy).
* Zdefiniowanie **zasad kampanii** (reset PŻ/ekwipunku, zdobywanie i wydawanie PK, konsekwencje eliminacji).
* Podział obszernej **listy Cech** na kategorie tematyczne, aby ułatwić ich przeglądanie i wybór.

**7. Potencjalne Dalsze Kroki / Obszary do Dopracowania:**

* Rewizja i modyfikacja listy Cech pod kątem skirmisha (usunięcie/zmiana tych zbyt RPG-owych).
* Stworzenie większej liczby gotowych scenariuszy skirmishowych.
* Rozbudowa biblioteki profili BN i ich algorytmów.
* Testowanie balansu (scenariuszy, cech, progresji PK).
* Dopracowanie zasad opcjonalnych (np. wykupienie Cech Negatywnych, "odzyskanie" postaci).
* Finalna redakcja i formatowanie podręczników.
* Tworzenie dodatkowych materiałów pomocniczych (karty odniesienia, generatory BN, etc.).

---

Ten dokument powinien zapewnić wystarczający kontekst do kontynuowania pracy nad systemem TEOHIPHIP, przypominając główne założenia i podjęte decyzje projektowe.
