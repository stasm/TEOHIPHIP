# Bohaterowie niezależni

Ten rozdział zawiera profile statystyk i algorytmy zachowań dla postaci i istot, które bandy graczy mogą napotkać (lub którymi mogą być) podczas swoich misji.

## Tworzenie statystyk BN dla skirmisha

Profil BN-a powinien zawierać:

* **Nazwa/Typ:** (np. Agent MOIRY, Technik INT, Legionista Rzymski, Raptor Temporalny)
* **Punkty życia (PŻ):** Określają wytrzymałość. Zwykli przeciwnicy mają ich mało (np. 3-5), "elity" lub bossowie więcej (6-8+).
* **Ruch (SPD):** Standardowo 6", modyfikowany dla szybkich/wolnych istot.
* **Kluczowe cechy:** Wybierz 1-3 cechy (pozytywne lub negatywne), które definiują rolę i możliwości BN-a (np. Strażnik może mieć *Zimną krew*, Bestia *Nadwrażliwość* na jakiś bodziec). Nie twórz pełnej karty postaci, wybierz tylko te cechy, które mają znaczenie w walce/scenariuszu.
* **Podstawowy Atak:** Opis głównego ataku (dystansowy/wręcz), ewentualny zasięg i specjalne właściwości (np. ignoruje osłonę, zadaje dodatkowe obrażenia przy sukcesie krytycznym?). Test ataku to zwykle 2k6, chyba że cecha daje przewagę/utrudnienie.
* **Algorytm Zachowania:** Przypisany algorytm (patrz niżej).

## Przykładowe profile BN

*(Tutaj należy stworzyć kilka-kilkanaście gotowych profili dla najczęściej występujących typów BN)*

* **Przykład: Szeregowy Agent INT (np. Czasownik/Technik w Terenie)**
    * PŻ: 4, SPD: 6"
    * Cechy: Np. *Technofobia* (+2 PC), *Spanikowany* (utrudnienie na testy woli w stresie - nowa, prosta cecha negatywna)
    * Atak: Pistolet energetyczny (Zasięg 18", test 2k6, 1 sukces=1 PŻ)
    * Algorytm: "Wsparcie z Tyłu" (patrz 4.3)

* **Przykład: Agent MOIRY (Standardowy)**
    * PŻ: 5, SPD: 6"
    * Cechy: Np. *Zimna krew* (-3 PC), *Taktyk* (Raz na turę może dać przewagę sojusznikowi w LoS - nowa cecha)
    * Atak: Karabin energetyczny (Zasięg 24", test 2k6, 1 sukces=1 PŻ) lub Pałka ogłuszająca (Wręcz, test 2k6, Sukces: Cel musi zdać test odporności lub traci 1 AP w nast. turze)
    * Algorytm: "Agresywny Szturmowiec" lub "Ochrona Celu" (patrz 4.3)

* **Przykład: Wojownik Historyczny (np. Legionista Rzymski)**
    * PŻ: 4, SPD: 5"
    * Cechy: Np. *Formacja* (Gdy w kontakcie bazowym z innym Legionistą, obaj ignorują 1 sukces przy atakach wręcz - nowa cecha)
    * Atak: Gladius (Wręcz, test 2k6, 1 sukces=1 PŻ), Pilum (Rzut, Zasięg 6", Jednorazowy, test 2k6, 1 sukces=1 PŻ)
    * Algorytm: "Utrzymanie Linii" (patrz 4.3)

* **Przykład: Bestia Temporalna (np. Raptor)**
    * PŻ: 6, SPD: 8"
    * Cechy: Np. *Szybki*, *Drapieżnik* (przewaga na atak wręcz przeciwko celowi z PŻ poniżej połowy)
    * Atak: Pazury/Zęby (Wręcz, test 2k6, 2 sukcesy=2 PŻ)
    * Algorytm: "Drapieżnik" (patrz 4.3)

## Biblioteka algorytmów BN

Algorytm to lista priorytetów. Podczas aktywacji BN-a, wykonaj pierwszą akcję z listy, której warunki są spełnione. Jeśli akcja kosztuje 1 AP i BN ma jeszcze 1 AP, sprawdź listę ponownie dla drugiego AP.

* **Algorytm: "Agresywny Szturmowiec"**
    1.  Jeśli wróg w zasięgu ataku (preferowany wręcz, jeśli możliwe) -> **Atakuj** (1 AP). Użyj drugiego AP, by **Kryć się** lub **Celować** (jeśli planujesz strzelać w nast. turze).
    2.  Jeśli wróg widoczny, ale poza zasięgiem -> **Rusz** (1 lub 2 AP) w kierunku najbliższego wroga, starając się zakończyć ruch za osłoną.
    3.  Jeśli brak widocznych wrogów -> **Rusz** (1 lub 2 AP) w kierunku najbliższego celu misji graczy lub ostatniej znanej pozycji wroga.

* **Algorytm: "Ochrona Celu/Pozycji"**
    1.  Jeśli wróg w zasięgu ataku z obecnej pozycji I atakuje chroniony cel/znajduje się w chronionej strefie -> **Atakuj** (1 AP). Drugi AP: **Kryj się** lub **Celuj**.
    2.  Jeśli wróg widoczny, ale nie zagraża bezpośrednio celowi/strefie LUB jest poza zasięgiem -> **Kryj się** (1 AP), ewentualnie **Celuj** (1 AP) w najbliższego wroga.
    3.  Jeśli wróg wchodzi do chronionej strefy -> **Rusz** (1 lub 2 AP), by go przechwycić/zaatakować.
    4.  Jeśli brak wrogów -> Pozostań na pozycji lub wykonaj krótki ruch patrolowy wokół celu/strefy, kończąc za osłoną.

* **Algorytm: "Wsparcie z Tyłu"**
    1.  Jeśli wróg w zasięgu ataku dystansowego I ma czysty strzał (bez ukrycia) -> **Atakuj** (1 AP). Drugi AP: **Kryj się**.
    2.  Jeśli wróg w zasięgu, ale w ukryciu/osłonie LUB jeśli sam BN jest na otwartym terenie -> **Rusz** (1 AP), by znaleźć lepszą pozycję strzelecką z osłoną. Drugi AP: **Kryj się** lub **Celuj**.
    3.  Jeśli wróg poza zasięgiem -> **Rusz** (1 lub 2 AP) ostrożnie w stronę walki, pozostając z tyłu za bardziej agresywnymi sojusznikami, kończąc ruch za osłoną.
    4.  Jeśli brak wrogów/sojuszników w walce -> **Kryj się** i czekaj.

* **Algorytm: "Drapieżnik"**
    1.  Jeśli wróg w zasięgu ataku wręcz -> **Atakuj** (1 AP). Jeśli cel ma mało PŻ, użyj cechy *Drapieżnik*. Drugi AP: **Atakuj** ponownie (jeśli zasady pozwalają BN-om na 2 ataki) lub **Rusz**, by związać walką kolejnego wroga.
    2.  Jeśli brak wroga w zasięgu wręcz -> **Rusz** (1 lub 2 AP) najkrótszą drogą w kierunku najbliższej postaci (preferując rannych). Ignoruj osłony i trudny teren, jeśli to możliwe (przeskakuj, wspinaj się - może wymagać testu dla BN).
    3.  Jeśli ostrzeliwany -> Zwykle ignoruj i kontynuuj szarżę (chyba że test woli wskaże inaczej).

* **Algorytm: "Utrzymanie Linii" (dla historycznych)**
    1.  Jeśli wróg w zasięgu ataku wręcz LUB w zasięgu szarży (ruch) -> **Atakuj** wręcz (1 AP) lub **Rusz** (1 AP), by zaatakować wręcz. Drugi AP: Użyj cechy *Formacja* (jeśli dotyczy) lub spróbuj utrzymać pozycję.
    2.  Jeśli wróg w zasięgu broni miotanej (np. Pilum) -> **Atakuj** bronią miotaną (1 AP). Drugi AP: **Rusz** w stronę wroga lub przygotuj się do walki wręcz.
    3.  Jeśli brak bezpośredniego zagrożenia -> **Rusz** (1 AP) powoli w formacji z innymi sojusznikami w kierunku celu/wroga. Drugi AP: **Kryj się** (za tarczą) lub utrzymaj pozycję.

* **Algorytm: "Unikanie Walki / Chowanie Się"** (Dla NPC typu Cel/Cywil)
    1.  Jeśli w zasięgu ruchu (SPD) znajduje się osłona (Cover) poza LoS od najbliższego wroga -> **Rusz** (1 lub 2 AP), by się za nią schować.
    2.  Jeśli brak takiej osłony, ale jest osłona w LoS wroga -> **Rusz** (1 AP), by się za nią schować, a drugi AP użyj na **Krycie się (Hunker Down)**.
    3.  Jeśli brak osłon lub jest otoczony -> **Kryj się (Hunker Down)** (1 AP) i/lub **Rusz** (1 AP) jak najdalej od najbliższego wroga.
    4.  *Nigdy nie wykonuje akcji Ataku, chyba że zasady specjalne scenariusza stanowią inaczej.*

* **Algorytm: "Realizacja Celu (Specyficzny)"** (Np. podłożenie ładunku, hakowanie)
    1.  Jeśli w kontakcie bazowym z celem misji (np. punktem do sabotowania) -> Wykonaj akcję **Interakcji** wymaganą przez scenariusz (np. test techniczny, by podłożyć ładunek) (1 lub 2 AP).
    2.  Jeśli cel misji jest w zasięgu ruchu (SPD lub 2xSPD) -> **Rusz** (1 lub 2 AP) najkrótszą drogą do celu misji.
    3.  Jeśli na drodze do celu misji stoi wróg -> Spróbuj go ominąć LUB (jeśli niemożliwe) **Atakuj** (1 AP), by utorować sobie drogę. Drugi AP wykorzystaj na **Ruch** w stronę celu.
    4.  Jeśli cel misji nieosiągalny (np. zablokowany) -> Działaj jak "Agresywny Szturmowiec" przeciwko najbliższemu wrogowi blokującemu dostęp.

* **Algorytm: "Neutralizacja Wszystkich"** (Np. dla MOIRY interweniującej w chaosie)
    1.  Jeśli jakakolwiek postać (gracza LUB inny BN niebędący sojusznikiem) jest w zasięgu ataku -> **Atakuj** najbliższą postać (1 AP). Drugi AP: **Celuj** w kolejny cel lub **Kryj się**.
    2.  Jeśli widoczne są postacie, ale poza zasięgiem -> **Rusz** (1 lub 2 AP) w kierunku najbliższej grupy postaci, starając się zakończyć ruch za osłoną z dobrym polem ostrzału.
    3.  Jeśli brak widocznych postaci -> **Rusz** (1 lub 2 AP) w kierunku centrum walki lub ostatniej znanej pozycji jakiejkolwiek postaci.

* **Algorytm: "Największy Głodomór"** (Np. dla T-Rexa, wielkiej bestii)
    1.  Jeśli jakakolwiek postać (gracza lub BN) jest w zasięgu ataku wręcz -> **Atakuj** najbliższą (1 AP). Drugi AP: **Atakuj** ponownie (jeśli możliwe) lub **Rusz** w stronę kolejnej najbliższej postaci.
    2.  Jeśli brak postaci w zasięgu wręcz -> **Rusz** (1 lub 2 AP) najkrótszą drogą w kierunku **najbliższej** postaci na mapie, ignorując przynależność frakcyjną.
    3.  *Zazwyczaj ignoruje ataki dystansowe i osłony, chyba że otrzyma bardzo dużo obrażeń w jednej rundzie (test woli MG?).*

* **Algorytm: "Obrona Pozycji / Przetrwanie"** (Dla 'Bossa' lub ważnego BN)
    1.  Jeśli wróg w zasięgu ataku z obecnej pozycji -> **Atakuj** najgroźniejszego wroga (np. tego, który zadał najwięcej obrażeń lub jest najbliżej) (1 AP). Drugi AP: **Kryj się** lub użyj zdolności specjalnej (jeśli dostępna i możliwa).
    2.  Jeśli wróg widoczny, ale poza zasięgiem LUB BN jest na otwartym terenie -> **Rusz** (1 AP) do najbliższej dobrej osłony. Drugi AP: **Kryj się** lub **Celuj**.
    3.  Jeśli brak widocznych wrogów -> **Kryj się** (1 AP) i **Celuj** (1 AP) w kierunku, z którego spodziewa się ataku lub **użyj zdolności specjalnej** (np. leczenie, wezwanie pomocy, jeśli ma taką opcję).
    4.  *Unika niepotrzebnego ryzyka, preferuje walkę zza osłony.*

* **Algorytm: "Zniszczyć Cel (Obiekt)"** (Np. dla hordy atakującej generator)
    1.  Jeśli w zasięgu ruchu (SPD lub 2xSPD) znajduje się cel misji (obiekt) -> **Rusz** (1 lub 2 AP) najkrótszą drogą w kierunku celu.
    2.  Jeśli w kontakcie bazowym z celem misji -> **Atakuj** cel (1 AP). Drugi AP: **Atakuj** cel ponownie.
    3.  Jeśli na drodze do celu stoi postać gracza -> Spróbuj ją ominąć LUB (jeśli niemożliwe) **Atakuj** ją (1 AP), by przejść dalej. Drugi AP: Kontynuuj **Ruch** w stronę celu.
    4.  *Ignoruje inne zagrożenia, chyba że bezpośrednio uniemożliwiają dotarcie do celu.*

* **Algorytm: "Atak na Najbliższego Gracza"** (Prostszy agresywny algorytm)
    1.  Jeśli postać gracza w zasięgu ataku -> **Atakuj** najbliższą postać gracza (1 AP). Drugi AP: **Rusz** w stronę kolejnej postaci gracza lub **Kryj się**.
    2.  Jeśli postać gracza widoczna, ale poza zasięgiem -> **Rusz** (1 lub 2 AP) w kierunku najbliższej postaci gracza.
    3.  Jeśli brak widocznych postaci graczy -> **Rusz** (1 lub 2 AP) w kierunku ostatniej znanej pozycji gracza lub najbliższego celu misji graczy.

* **Algorytm: "Przejąć Artefakt / Cel"** (Dla rywalizujących zespołów)
    1.  Jeśli Artefakt/Cel (znacznik) jest w zasięgu ruchu (SPD lub 2xSPD) i nie jest kontrolowany przez wroga -> **Rusz** (1 lub 2 AP), by wejść w kontakt bazowy z Artefaktem. Jeśli to możliwe, wykonaj akcję **Interakcji** (1 AP), by go podnieść/zabezpieczyć.
    2.  Jeśli Artefakt jest kontrolowany przez wroga LUB wróg blokuje drogę do Artefaktu -> **Atakuj** tego wroga (1 AP). Drugi AP: **Rusz** w stronę Artefaktu lub **Kryj się/Celuj**.
    3.  Jeśli Artefakt jest daleko -> **Rusz** (1 lub 2 AP) najszybszą drogą w kierunku Artefaktu.
    4.  Jeśli BN kontroluje Artefakt -> **Rusz** (1 lub 2 AP) w kierunku swojej strefy startowej lub punktu ewakuacji, atakując wrogów na drodze.

* **Algorytm: "Obrabować Wszystkich"** (Np. dla bandytów)
    1.  Jeśli postać (gracza lub BN) posiadająca Artefakt/cenny przedmiot (jeśli dotyczy) jest w zasięgu ataku -> **Atakuj** tę postać (1 AP). Drugi AP: Spróbuj **Interakcji**, by zabrać przedmiot (jeśli cel wyeliminowany) lub **Atakuj** ponownie.
    2.  Jeśli brak celu z pkt 1, ale wróg w zasięgu ataku -> **Atakuj** najbliższego wroga (1 AP). Drugi AP: **Rusz** w stronę kolejnego wroga lub **Kryj się**.
    3.  Jeśli brak wrogów w zasięgu -> **Rusz** (1 lub 2 AP) w kierunku najbliższej postaci (gracza lub BN), preferując te, które wyglądają na "bogatsze" lub słabsze.

* **Algorytm: "Patrol / Reakcja na Alarm"** (Dla standardowej ochrony)
    1.  **Stan spokoju (Brak alarmu, brak widocznych wrogów):** **Rusz** (1 AP) wzdłuż ustalonej trasy patrolu. Drugi AP: **Obserwuj** (brak efektu mechanicznego, chyba że MG przyzna przewagę na percepcję).
    2.  **Wykryto wroga / alarm:**
        * Jeśli wróg w zasięgu ataku -> **Atakuj** (1 AP). Drugi AP: **Kryj się** lub **Rusz** w stronę osłony.
        * Jeśli wróg widoczny, ale poza zasięgiem -> **Rusz** (1 lub 2 AP) w kierunku wroga, szukając osłony.
        * Jeśli słychać alarm/walkę, ale wróg niewidoczny -> **Rusz** (1 lub 2 AP) ostrożnie w kierunku źródła hałasu/alarmu.

Pamiętaj, że te algorytmy to szablony. Możesz je modyfikować lub tworzyć własne, aby lepiej pasowały do konkretnych BN-ów i scenariuszy. Kluczem jest prostota i przewidywalność, która odciąży Cię podczas prowadzenia potyczki.
