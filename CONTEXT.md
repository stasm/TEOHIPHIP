Oto skondensowane podsumowanie dotychczasowej pracy nad TEOHIPHIP, które posłuży jako punkt wyjścia do dalszych dyskusji z AI lub innymi współpracownikami. Chodzi o uchwycenie kluczowych decyzji projektowych i aktualnego stanu systemu, bez wchodzenia w pełne szczegóły zawarte w podręcznikach czy liście cech.

---

# Braindump kontekstowy: Projekt TEOHIPHIP (stan na 02.05.2025)

## 1. Wizja projektu

* Główny fokus: TEOHIPHIP jest taktyczną grą skirmishową z elementami RPG.
* Setting: Osadzony w absurdalnym, pełnym czarnego humoru i biurokracji świecie podróży w czasie inspirowanym "Podróżą dwudziestą" Stanisława Lema (Instytut Temporystyki - INT, projekt TEOHIPHIP).
* Rdzeń rozgrywki: Gracze kontrolują bandy (1-3 agentów INT) w krótkich (5-6 rund), celowych scenariuszach skirmishowych (potyczkach) rozgrywanych na mapie z figurkami/znacznikami.
* Kluczowe elementy: Połączenie taktycznej walki, realizacji celów misji, zarządzania ryzykiem (pula inicjatywy), unikalnych postaci (system cech) i klimatu Lema (absurd, chaos, technologia, paradoksy).

## 2. Podstawowa mechanika

* System: Zmodyfikowany tinyd6.
* Testy: 2k6 (standard), 3k6 (przewaga - wybierz 2), 1k6 (utrudnienie). Sukces na 5 lub 6.
* Punkty akcji (AP): Każda postać ma 2 AP na aktywację do wydania na akcje (ruch, atak, celowanie, krycie się, interakcja itp.).
* Skirmishowe zasady terenu: Proste zasady dla ruchu (SPD, trudny teren), linii wzroku (true LoS, ukrycie = utrudnienie), osłony (ignorowanie 1 sukcesu).

## 3. Kluczowe podsystemy

* System band: Gracze tworzą i kontrolują bandy 1-3 postaci, wykorzystując 12 punktów kreacji (PK) na start (1 PK = 1 PŻ lub 3 PC). Rozmiar bandy wpływa na liczbę aktywacji i indywidualną siłę postaci.
* System cech: Rozbudowana lista cech pozytywnych (koszt w PC) i negatywnych (dają PC) pozwala tworzyć unikalne postacie. Cechy mają bezpośredni wpływ mechaniczny (przewaga/utrudnienie, modyfikacje statystyk, specjalne zdolności).
* Pula inicjatywy: Centralna mechanika taktyczna służąca zarządzaniu ryzykiem. Na początku rundy postać rzuca k6 równymi jej aktualnym PŻ. Gracz może wydać 1 PŻ, aby po wykonaniu testu podmienić 1 kość z rzutu na 1 kość z puli.
* Automatyzacja BN: Przeciwnicy (BN) działają według predefiniowanych algorytmów (list priorytetów), aby odciążyć MG/Arbitra i przyspieszyć grę. Istnieje opcjonalna zasada pozwalająca graczom aktywować BN-y według algorytmów.

## 4. Kampania i progresja

* Struktura: Seria połączonych potyczek skirmishowych.
* Faza "Pomiędzy misjami":
    * PŻ postaci resetują się do maksimum.
    * Ekwipunek resetuje się do standardu misyjnego (nie jest śledzony).
    * Bandy zdobywają **punkty kreacji (PK): 3 PK za wygraną, 1 PK za przegraną/remis** (jeśli banda przetrwała), 0 PK za całkowitą eliminację.
    * PK można wydać **tylko** na **nowe cechy pozytywne** (1 PK = 3 PC) lub **nowe postacie** (1 PK = 1 PŻ, min 4 PK). **Nie można kupować PŻ bezpośrednio.**
    * Niewykorzystane PK kumulują się.
    * Całkowita eliminacja bandy: Gracz otrzymuje 12 PK na stworzenie nowej bandy od zera (traci poprzedni postęp).
    * (Opcjonalnie) Możliwość wykupienia cech negatywnych za wysoki koszt PK.

## 5. Dokumentacja projektu

* `README.md`: Zaktualizowany opis projektu.
* `CONTEXT.md`: Krótkie podsumowanie projektu, jego celów i aktualnego stanu, na potrzeby rozmów z AI lub współpracownikami.
* Dokumentacja została zorganizowana w katalogi tematyczne w folderze `src` w formacie **mdbook** dla lepszej organizacji i prezentacji treści.
  * `SUMMARY.md` definiuje strukturę spisu treści dla mdbooka.

  * `index.md` - Ogólny wstęp do gry i świata.
  * `start.md` - Pierwsze kroki w grze dla nowych graczy.
  * `gracz/` - Podręcznik gracza z zasadami tworzenia band i prowadzenia potyczek.
    * `index.md` - Wprowadzenie do podręcznika gracza.
    * `świat.md` - Opis świata gry.
    * `banda.md` - Tworzenie bandy i zasady potyczek.
    * `potyczka.md` - Zasady potyczek skirmishowych.
    * `kampania.md` - Zasady kampanii i progresji.
    * `porady.md` - Porady dla graczy.
  * `mg/` - Podręcznik mistrza gry z zasadami prowadzenia gry.
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
* Pliki projektowe (`designs`): Wcześniejsze notatki i wersje rozwojowe mechanik.

Uwaga: Nagłówki w dokumentacji stosują standardową polską pisownię, tj. pierwsze słowo wielką literą, pozostałe małą, chyba że są to nazwy własne. Podobnie nazwy mechanik i pojęć istotnych dla gry piszemy małą literą (chyba, że znajdują się na początku zdania).

## 6. Kluczowe decyzje projektowe podjęte w trakcie rozmowy

* Ostateczne przejście z modelu RPG na **skirmish z elementami RPG**.
* Wprowadzenie **systemu band** jako podstawy (1-3 postacie na gracza, 12 PK na start).
* Zaimplementowanie mechaniki **puli inicjatywy** (kości=PŻ, koszt 1 PŻ za wymianę).
* Opracowanie **zasad skirmishowych** (2 AP, akcje, LoS, osłona itp.).
* Wprowadzenie **automatyzacji BN** za pomocą algorytmów (z opcją kontroli przez graczy).
* Zdefiniowanie **zasad kampanii** (reset PŻ/ekwipunku, zdobywanie i wydawanie PK, konsekwencje eliminacji).
* Podział obszernej **listy cech** na kategorie tematyczne, aby ułatwić ich przeglądanie i wybór.

## 7. Potencjalne dalsze kroki / obszary do dopracowania

* Rewizja i modyfikacja listy cech pod kątem skirmisha (usunięcie/zmiana tych zbyt RPG-owych).
* Stworzenie większej liczby gotowych scenariuszy skirmishowych.
* Rozbudowa biblioteki profili BN i ich algorytmów.
* Testowanie balansu (scenariuszy, cech, progresji PK).
* Dopracowanie zasad opcjonalnych (np. wykupienie cech negatywnych, "odzyskanie" postaci).
* Finalna redakcja i formatowanie podręczników.
* Tworzenie dodatkowych materiałów pomocniczych (karty odniesienia, generatory BN, etc.).

---

Ten dokument powinien zapewnić wystarczający kontekst do kontynuowania pracy nad systemem TEOHIPHIP, przypominając główne założenia i podjęte decyzje projektowe.
