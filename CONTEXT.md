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
* **System Cech:** Rozbudowana lista Cech Pozytywnych (koszt w PC) i Negatywnych (dają PC) pozwala tworzyć unikalne postacie. Cechy mają bezpośredni wpływ mechaniczny (Przewaga/Utrudnienie, modyfikacje statystyk, specjalne zdolności). Lista cech została podzielona na **Zestaw Podstawowy** i **Dodatki Tematyczne** (np. "Mistrzowie Puli Inicjatywy", "Weterani Czasu", "Praca Zespołowa"). (*Uwaga: Istnieje potrzeba rewizji/modyfikacji niektórych cech odziedziczonych po fazie RPG*).
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

**5. Istniejące Dokumenty Główne (Stan na 02.05.2025):**

* `Pierwsze_kroki.md`: Wprowadzenie do gry i zasady podstawowe.
* `Podręcznik_czasownika.md`: Zaktualizowany podręcznik gracza, opisujący tworzenie band, zasady potyczek skirmishowych i kampanii.
* `Podręcznik_mistrza_gry.md`: Zaktualizowany podręcznik mistrza gry, zawierający szczegóły świata, zasady prowadzenia potyczek, projektowania scenariuszy, profile BN z algorytmami, zasady kampanii i narzędzia.
* `Cechy_postaci.md`: Aktualna, podzielona na Zestaw Podstawowy i Dodatki, lista Cech.
* `Scenariusze.md`: Opis misji i scenariuszy, w tym przykłady i pomysły na misje.
* `Słowniczek.md`: Słownik terminów i pojęć używanych w grze.
* `README.md`: Zaktualizowany opis projektu.
* *Inne pliki projektowe (`designs`)*: Wcześniejsze notatki i wersje rozwojowe mechanik.

**6. Kluczowe Decyzje Projektowe Podjęte w Trakcie Rozmowy:**

* Ostateczne przejście z modelu RPG na **skirmish z elementami RPG**.
* Wprowadzenie **Systemu Band** jako podstawy (1-3 postacie na gracza, 12 PK na start).
* Zaimplementowanie mechaniki **Puli Inicjatywy** (kości=PŻ, koszt 1 PŻ za wymianę).
* Opracowanie **zasad skirmishowych** (2 AP, akcje, LoS, Osłona itp.).
* Wprowadzenie **Automatyzacji BN** za pomocą algorytmów (z opcją kontroli przez graczy).
* Zdefiniowanie **zasad kampanii** (reset PŻ/ekwipunku, zdobywanie i wydawanie PK, konsekwencje eliminacji).
* Podział obszernej **listy Cech** na Zestaw Podstawowy i Dodatki Tematyczne.

**7. Potencjalne Dalsze Kroki / Obszary do Dopracowania:**

* Rewizja i modyfikacja listy Cech pod kątem skirmisha (usunięcie/zmiana tych zbyt RPG-owych).
* Stworzenie większej liczby gotowych scenariuszy skirmishowych.
* Rozbudowa biblioteki profili BN i ich algorytmów.
* Testowanie balansu (scenariuszy, cech, progresji PK).
* Dopracowanie zasad opcjonalnych (np. wykupienie Cech Negatywnych, "odzyskanie" postaci).
* Finalna redakcja i formatowanie podręczników.

---

Ten dokument powinien zapewnić wystarczający kontekst do kontynuowania pracy nad systemem TEOHIPHIP, przypominając główne założenia i podjęte decyzje projektowe.
