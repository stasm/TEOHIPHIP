# Prowadzenie potyczki skirmishowej

Ten rozdział skupia się na praktycznych aspektach prowadzenia potyczki skirmishowej w TEOHIPHIP, od zarządzania turą po rozstrzyganie zasad i automatyzację przeciwników.

## Przebieg rundy i aktywacja

* **Limit czasu:** Standardowa potyczka trwa **5-6 rund**. Śledzenie upływających rund jest kluczowe dla realizacji celów scenariusza.
* **Kolejność aktywacji:** Na początku każdej rundy ustalana jest kolejność aktywacji band (np. rzut k6, stała kolejność, losowanie żetonów).
* **Aktywacja naprzemienna:** Gracze (i MG/Algorytmy BN) aktywują swoje postacie (lub całe bandy BN, jeśli tak ustalono) po kolei, zgodnie z ustaloną inicjatywą.
* **Aktywacja bandy gracza:** Gracz kontrolujący bandę aktywuje **jedną** ze swoich postaci w swojej kolejce. Po wykonaniu akcji przez tę postać, kolejka przechodzi dalej. Gracz nie może aktywować kolejnej postaci ze swojej bandy, dopóki wszystkie inne jednostki na stole nie miały swojej aktywacji w tej rundzie.
* **Punkty akcji (AP):** Każda aktywowana postać dysponuje **2 AP** do wydania na akcje.

## Adjudykacja zasad skirmishowych

Twoją rolą jako Arbitra jest sprawne i spójne rozstrzyganie sytuacji na stole. Pamiętaj o zasadach opisanych w Podręczniku gracza (Rozdział 3):

* **Ruch:** Pilnuj kosztów w trudnym terenie, rozsądnie oceniaj próby wspinaczki/skoków (testy!).
* **Linia wzroku (LoS):** Stosuj zasadę "True LoS". W razie wątpliwości, podejdź do stołu i spójrz z perspektywy figurki. Bądź konsekwentny w kwestii blokowania LoS przez teren i inne postacie. Pamiętaj o **utrudnieniu** przy strzale do celu w **ukryciu**.
* **Osłona:** Sprawdzaj, czy cel spełnia warunki osłony (zasłonięty przez solidny teren, blisko niego). Przypominaj graczom o korzyści (**ignorowanie 1 sukcesu**).
* **Akcje:** Upewnij się, że gracze poprawnie deklarują i opłacają akcje (1 lub 2 AP). Testy przy interakcji powinny być szybkie i adekwatne do sytuacji.

## Prowadzenie testów i puli inicjatywy

* **Kiedy test?** W sytuacjach ryzykownych lub wymagających umiejętności (atak, interakcja, wspinaczka, użycie niektórych cech). Unikaj testów na trywialne czynności.
* **Przewaga/utrudnienie:** Przyznawaj je śmiało w oparciu o cechy, sytuację taktyczną (celowanie, ukrycie, flankowanie?), stan sprzętu (często daje utrudnienie!) i kreatywność graczy. Pamiętaj, że się nie kumulują.
* **Interpretacja wyników:** Skupiaj się na **konkretnych efektach w potyczce**:
    * **0 sukcesów:** Akcja nieudana, często z dodatkową negatywną konsekwencją (broń się zacięła, postać potknęła się i straciła resztę ruchu, cel interakcji uruchomił alarm, przeciwnik wykorzystał okazję).
    * **1 sukces:** Sukces z kosztem. Cel osiągnięty częściowo (1 obrażenie zamiast potencjalnych 2, drzwi otwarte, ale hałaśliwie, cel unieruchomiony tylko na chwilę) lub z negatywnym skutkiem ubocznym (sukces w ataku, ale broń się przegrzała i nie można jej użyć w następnej turze).
    * **2+ sukcesy:** Pełny, czysty sukces zgodnie z intencją gracza.
* **Pula inicjatywy:**
    * **Przypominaj:** O rzucie puli na początku rundy (kości = aktualne PŻ) i o możliwości wymiany kości.
    * **Egzekwuj koszt:** Upewnij się, że gracz odejmuje 1 PŻ za *każdą* wymianę, zanim zastosuje jej efekt.
    * **Obserwuj:** PŻ graczy to wskaźnik ich elastyczności taktycznej. Niskie PŻ oznaczają mniejszą pulę i większe ryzyko.

## Zarządzanie komplikacjami

Świat TEOHIPHIP jest niestabilny. Wykorzystuj to!
* **Planowane komplikacje:** Scenariusz może zakładać konkretne wydarzenia (np. przybycie posiłków w rundzie 3, awaria generatora w rundzie 4).
* **Losowe komplikacje:** Używaj tabel losowych lub własnej inwencji, by wprowadzać nieoczekiwane zdarzenia: chwilowa anomalia temporalna (np. spowolnienie/przyspieszenie czasu w sektorze mapy), awaria sprzętu losowej postaci (test techniczny, by naprawić?), pojawienie się lokalnej fauny, absurdalna dyrektywa z centrali zmieniająca cele misji w jej trakcie. Wprowadzaj je np. na początku rundy na rzut k6 (np. na 1).

## Automatyzacja przeciwników (BN)

Aby odciążyć MG i przyspieszyć grę, BN-y w TEOHIPHIP działają według prostych algorytmów.

* **Filozofia:** Algorytmy mają zapewnić spójne i przewidywalne (choć niekoniecznie inteligentne) zachowanie BN-ów, odzwierciedlające ich typ i rolę (np. bezmyślna bestia, zdyscyplinowany strażnik, spanikowany cywil).
* **Stosowanie algorytmu:** Podczas aktywacji BN-a, wykonaj kroki opisane w jego algorytmie (patrz Rozdział 4) w podanej kolejności priorytetów. Wykonaj pierwszą akcję, której warunki są spełnione. Jeśli BN ma 2 AP, a pierwsza akcja kosztowała 1 AP, sprawdź algorytm ponownie dla drugiego AP.
* **Sytuacje nieprzewidziane:** Jeśli algorytm nie obejmuje danej sytuacji (rzadkie przy dobrym algorytmie), jako MG podejmij decyzję zgodną z "osobowością" i celem BN-a (np. strażnik będzie dążył do ochrony celu lub eliminacji intruzów, bestia zaatakuje najbliższy ruchomy cel).
* **Kto kontroluje BN?**
    * **Standardowo:** MG wykonuje akcje BN-ów zgodnie z ich algorytmami.
    * **Opcjonalnie (Aktywacja przez graczy):** Aby jeszcze bardziej przyspieszyć grę (szczególnie w trybie kooperacyjnym), gracze mogą aktywować BN-ów. Proponowany mechanizm: po aktywacji swojej postaci, gracz aktywuje również najbliższego BN-a, który jeszcze nie działał w tej rundzie, ściśle stosując jego algorytm. Wymaga to uczciwości i zrozumienia algorytmów przez graczy.
