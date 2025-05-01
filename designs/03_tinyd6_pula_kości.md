## Modyfikacja tinyd6 - Pula kości inicjatywy

### 1. Kontekst i cel

**Kontekst:** Standardowa mechanika tinyd6 opiera się na rzutach 1-3k6 w momencie wykonywania testu, gdzie wynik 5 lub 6 oznacza sukces. System jest prosty i szybki, ale czasem może prowadzić do frustracji wynikającej z losowości (ciągłe niepowodzenia pomimo dobrych założeń postaci lub odwrotnie). Gry takie jak *Warhammer Warcry* czy *Citizen Sleeper* wykorzystują mechanikę puli kości rzucanych na początku tury/cyklu, które następnie są przypisywane do akcji, co daje graczom większą kontrolę i informację zwrotną na temat ich potencjalnych możliwości w danej turze.

**Cel:** Wprowadzenie modyfikacji do systemu tinyd6 (używanego w projektach TEOHIPHIP RPG / Narrenturm RPG), która:
* Zredukuje poczucie całkowitej zależności od losowości (RNG) w kluczowych momentach.
* Wprowadzi element taktycznego zarządzania zasobami (kośćmi).
* Da graczom informację zwrotną na początku "tury", pozwalającą lepiej planować swoje działania (np. grać ostrożniej przy słabych rzutach w puli).
* Powiąże mechanicznie stan postaci (Punkty Życia) z jej możliwościami/szczęściem/energią w danej turze.
* Zachowa prostotę rdzenia tinyd6.

### 2. Wymagania

* Nowa mechanika powinna integrować się z istniejącymi zasadami tinyd6 (Test Standardowy 2k6, Przewaga 3k6, Utrudnienie 1k6, sukcesy na 5-6).
* Mechanika powinna być stosunkowo prosta do zrozumienia i zastosowania przy stole.
* Mechanika powinna dawać graczom poczucie większej kontroli nad wynikiem testów.
* Powiązanie z Punktami Życia (PŻ) powinno być znaczące, ale potencjalnie zbalansowane, aby nie deprecjonować innych aspektów postaci.

### 3. Proponowane rozwiązanie

1.  **Pula Inicjatywy:** Na początku "tury" (np. sceny, rundy walki, dnia w grze - do ustalenia) gracz rzuca pulą kości k6. Liczba kości w puli jest równa **aktualnej liczbie Punktów Życia (PŻ)** postaci.

2.  **Przechowywanie Puli:** Wyniki tych kości są odkładane na bok i pozostają dostępne dla gracza przez całą "turę".

3.  **Mechanika Wymiany:** Za każdym razem, gdy gracz wykonuje Test (rzucając 1, 2 lub 3 kośćmi zgodnie z zasadami tinyd6), może zdecydować o wymianie **jednej** z kości, którymi właśnie rzucił, na **jedną** kość ze swojej Puli Inicjatywy. 

    * **Koszt wymiany:** Każda wymiana kości kosztuje 1 PŻ. Jest to kluczowe powiązanie mechaniczne pomiędzy zdolnością postaci do wpływania na swój los a jej stanem zdrowia/energii.
    * **Ograniczenie:** Nie można wymienić kości, jeśli miałoby to zredukować PŻ do 0.

4.  **Wykorzystanie Kości z Puli:** Kość z Puli Inicjatywy użyta do wymiany jest odrzucana i nie można jej ponownie użyć w tej samej "turze". Niewykorzystane kości z Puli przepadają na koniec "tury".

### 4. Przykłady użycia

* **Przykład 1 (Standardowy test):** Zenon ma 4 PŻ. Pula inicjatywy: `[6, 4, 3, 1]`. Próbuje otworzyć zamek (Test 2k6), rzut: `[4, 2]` (porażka). Gracz decyduje, że sukces jest wart ryzyka. Deklaruje wymianę i **płaci 1 PŻ** (zostaje 3 PŻ). Wymienia `[2]` na `[6]` z puli. Wynik testu to `[6, 4]` (1 sukces). Pozostają mu w puli `[4, 3, 1]`. Na początku następnej tury rzuci już tylko 3k6 do puli.

* **Przykład 2 (Krytyczna sytuacja):** Zenon ma 2 PŻ. Pula: `[5, 1]`. Wykonuje test obrony przed śmiertelnym ciosem (Test 2k6), rzut: `[3, 1]` (porażka). Gracz decyduje się wydać ostatni możliwy PŻ (zostaje 1 PŻ), by przeżyć. **Płaci 1 PŻ**. Wymienia `[3]` na `[5]` z puli. Wynik to `[5, 1]` (1 sukces). Postać przeżyła, ale jest na skraju wyczerpania. W puli zostaje `[1]`. W następnej turze rzuci tylko 1k6 do puli.

### 5. Przykładowe zdolności

#### Cechy Pozytywne

##### Zwiększenie Puli i Punktów Życia
- **Hartowany:** +2 do maksymalnych PŻ (koszt: 4 punkty)
- **Witalność:** Gdy twoje PŻ spadają poniżej połowy maksimum, rzuć dodatkową k6 do puli (koszt: 3 punkty)
- **Wytrzymały:** Zaczynasz każdą przygodę z +1 tymczasowym PŻ, który znika po pierwszym teście (koszt: 2 punkty)
- **Uważność:** Na początku każdej nowej sceny, jeśli nie wykorzystałeś żadnej kości z puli w poprzedniej scenie, rzuć dodatkową kość do puli (koszt: 2 punkty)

##### Leczenie i Regeneracja
- **Regeneracja:** Na początku każdej tury odzyskujesz 1 PŻ, jeśli masz mniej niż połowę maksymalnych PŻ (koszt: 4 punkty) 
- **Drugi oddech:** Gdy twoje PŻ spadną do 1, natychmiast odzyskujesz 1k3 PŻ. Można użyć raz na dzień przygody (koszt: 3 punkty)
- **Medytacja:** Raz na scenę możesz poświęcić akcję, aby odzyskać 1 PŻ (koszt: 2 punkty)

##### Manipulacja Kośćmi w Puli
- **Strateg:** Raz na turę możesz przerzucić jedną kość w Puli (koszt: 3 punkty)
- **Mistyk:** Raz na turę możesz zwiększyć lub zmniejszyć wartość jednej kości w puli o 1 (koszt: 3 punkty)
- **Szczęściarz:** Na początku tury, jeśli masz w puli kość o wartości 1, możesz ją przerzucić (koszt: 2 punkty)
- **Hazardzista:** Raz na turę możesz przerzucić wszystkie kości w puli, ale musisz zaakceptować nowy wynik (koszt: 3 punkty)
- **Precyzja:** Raz na sesję możesz ustawić jedną kość w puli na dowolną wartość (koszt: 3 punkty)

##### Dzielenie się Zasobami
- **Przywódca:** Raz na turę możesz przekazać jedną kość ze swojej Puli sojusznikowi (koszt: 3 punkty)
- **Ofiara:** Możesz oddać 1 PŻ, aby przywrócić 1 PŻ sojusznikowi (koszt: 2 punkty)
- **Drużynowy:** Jeśli wszyscy w drużynie mają przynajmniej 1 sukces w testach w tej turze, odzyskujesz 1 PŻ (koszt: 2 punkty)

##### Mechaniki Specjalne
- **Przezorny:** Na początku tury możesz zachować jedną kość z poprzedniej tury (koszt: 3 punkty)
- **Nieustępliwy:** Kiedy twoje PŻ spadną do 1, rzuć dodatkową kością do Puli (koszt: 2 punkty)
- **Ekonomiczny:** Raz na turę możesz wymienić kość z puli bez płacenia PŻ (koszt: 3 punkty)
- **Wytrwały:** Gdy masz 2 lub mniej PŻ, koszt wymiany kości z puli spada do 0 (koszt: 3 punkty)
- **Opanowany:** Możesz wydać kość z puli o wartości 6, aby automatycznie przejść test bez rzucania (koszt: 4 punkty)
- **Adrenalina:** Gdy otrzymujesz obrażenia, rzuć dodatkową k6 i dodaj ją do puli (koszt: 3 punkty)
- **Oszust:** Raz na scenę możesz odwrócić kość w puli na przeciwną stronę (np. 1 na 6, 2 na 5, 3 na 4) (koszt: 3 punkty)
- **Z Nawiązką:** Gdy uzyskasz sukces krytyczny (dwie szóstki), odzyskujesz 1 PŻ (koszt: 3 punkty)
- **Nocny Łowca:** Podczas scen rozgrywających się w nocy lub ciemności, dodaj +1 do wartości każdej kości w puli (koszt: 3 punkty)
- **Obrońca:** Gdy sojusznik w zasięgu otrzymuje obrażenia, możesz wydać kość o wartości 5+ z puli, aby zredukować te obrażenia o 1 (koszt: 3 punkty)
- **Rytualista:** Możesz poświęcić przedmiot magiczny, aby natychmiast przerzucić całą pulę kości (koszt: 2 punkty)

#### Cechy Negatywne

- **Wątłe zdrowie:** Maksymalne PŻ zmniejszone o 1 (zysk: +3 punkty)
- **Nieostrożny:** Nie możesz zostawiać kości na kolejną turę (zysk: +2 punkty)
- **Niepewny:** Jeśli w puli masz kość o wartości 1 lub 2, musisz ją wykorzystać przy pierwszej wymianie w turze (zysk: +3 punkty)
- **Roztrzepany:** Raz na sesję MG może zmusić cię do użycia najgorszej kości z Puli (zysk: +1 punkt)
- **Pechowiec:** Zawsze gdy wyrzucisz 1 w puli, nie możesz jej użyć (zysk: +2 punkty)
- **Zmęczliwy:** Za każdym razem, gdy odzyskujesz PŻ, dostajesz o 1 mniej (zysk: +3 punkty)
- **Chaotyczny:** Na początku tury musisz przerzucić jedną losową kość z puli (zysk: +1 punkt)
- **Ostrożny:** Nie możesz korzystać z kości z puli, jeśli masz mniej niż 3 PŻ (zysk: +2 punkty)
- **Chwiejny:** Po każdej wymianie kości z puli, następny test wykonujesz z Utrudnieniem (zysk: +3 punkty)
- **Nadwrażliwy:** Otrzymujesz o 1 więcej obrażeń z każdego źródła (zysk: +4 punkty)
- **Impulsywny:** Przy pierwszym teście w turze musisz wymienić jedną ze swoich kości na kość o najwyższej wartości z puli, nawet jeśli to oznacza stratę 1 PŻ bez gwarancji sukcesu (zysk: +3 punkty)
- **Nerwowy:** Jeśli masz w puli więcej szóstek niż jedynek, jedna szóstka zamienia się w jedynkę (zysk: +3 punkty)
- **Ślepy w ciemności:** Podczas scen w ciemności/nocy odejmij 1 od każdej kości w puli (zysk: +2 punkty)
- **Uzależniony:** Na początku każdego dnia przygody tracisz 1 PŻ, jeśli nie zażyjesz swojej używki (zysk: +3 punkty)
- **Rozrzutny:** Nie możesz zachować niewykorzystanych kości o wartości 6 (zysk: +2 punkty)
- **Przesądny:** Gdy w puli pojawią się dwie kości o tej samej wartości, jedna z nich musi zostać przerzucona (zysk: +2 punkty)
- **Oportunista:** W pierwszym teście w turze musisz wymienić kość o wyższej wartości z testu na kość z puli; ta wymiana jest darmowa, bo kość z testu wędruje do puli (zastępując użytą) (zysk: +2 punkty)
- **Powolny Refleks:** Nie możesz korzystać z puli w swoim pierwszym teście w turze (zysk: +2 punkty)

### 6. Konsekwencje i dyskusja nad balansem

* **Zwiększona Kontrola Gracza:** To główna zaleta. Gracze widzą swoje potencjalne "szczęście" na turę i mogą strategicznie używać dobrych wyników z puli na kluczowe testy lub ratować porażki niskimi wynikami z puli (wymieniając np. 1 na 4, by uniknąć katastrofy, jeśli taka mechanika istnieje).
* **Znaczenie PŻ i efekt spirali śmierci:** Aktualna liczba PŻ staje się BARDZO ważna, bo bezpośrednio przekłada się na elastyczność i kontrolę gracza. Każda wymiana kości z puli kosztuje 1 PŻ, więc ranna postać nie tylko ma mniej kości w puli, ale każda wymiana przybliża ją do wyeliminowania z gry. To wzmacnia efekt "spirali śmierci" – ranny ma mniej PŻ, więc mniej kości w puli, więc trudniej mu wyjść z tarapatów, a każda próba ratunku kosztuje kolejne PŻ.
    * **Balans:** Warto rozważyć wsparcie dla postaci na skraju wyczerpania (np. cechy obniżające koszt wymiany przy niskim PŻ, przedmioty leczące, odpoczynek przywracający PŻ). Można też testowo ograniczyć liczbę wymian na turę lub wprowadzić mechanikę, gdzie pierwsza wymiana w turze jest darmowa.
* **Częstotliwość Wymiany:** Możliwość wymiany przy każdym teście jest silna, ale koszt PŻ naturalnie ogranicza nadużywanie tej opcji. Gracze będą ostrożniej gospodarować pulą i zdrowiem.
* **Definicja "Tury":** W narracyjnym RPG "tura" jest płynna. Zaleca się, by pula odświeżała się co scenę lub rundę walki, w zależności od tempa gry.
* **Interakcja z Cechami:** Cechy mogą wpływać na koszt wymiany, liczbę kości w puli, możliwość zachowania kości na kolejną turę itp.
* **Złożoność:** Mechanika dodaje krok zarządzania zasobem i decyzji o poświęceniu PŻ, ale pozostaje stosunkowo prosta.

### 7. Alternatywy

1.  **Pula jako Modyfikator:** Zamiast wymiany, kości z puli mogłyby być wydawane *przed* rzutem na Test, aby dodać +1 do wyniku jednej z kości w Teście (np. wydać [3] z puli, by zmienić [4] w Teście na [5]). Koszt w kościach z puli mógłby zależeć od wartości kości (np. wydanie [6] daje +1, wydanie [4] daje +1?).
2.  **Pula jako Dodatkowe Kości:** Wydanie kości z puli pozwala dodać jedną dodatkową kość do rzutu na Test (zwiększając szansę na sukces). Wartość kości z puli nie ma znaczenia, liczy się tylko jej posiadanie.
3.  **Pula jako "Punkty Fabuły":** Kości z puli reprezentują "punkty szczęścia/fabuły". Wydanie kości o wartości X pozwala np. na przerzucenie X kości w Teście, albo na wprowadzenie drobnego elementu do narracji na korzyść gracza (np. "okazuje się, że mam przy sobie potrzebne narzędzie" - kosztuje np. [5] lub [6]).
4.  **Pula Niezależna od PŻ:** Pula kości jest stała (np. 3k6) lub zależna od innego atrybutu (np. Wola, Spryt), odświeżana co scenę. Oddziela to mechanikę kontroli losu od zdrowia.
5.  **"Zachowaj Kość":** Prostsza wersja: Gracz wykonuje standardowy Test (np. 2k6). Może zdecydować się "zachować" jedną z wyrzuconych kości (zamiast jej wyniku) na później w tej turze/scenie, by użyć jej zamiast jednej kości w przyszłym Teście.

### Podsumowanie

Proponowana mechanika Puli Inicjatywy powiązanej z PŻ oraz koszt wymiany kości z puli (1 PŻ za każdą wymianę) zwiększa kontrolę gracza i dodaje warstwę taktyczną do tinyd6. Jej główną zaletą jest powiązanie stanu postaci z jej możliwościami, a potencjalnym wyzwaniem jest zbalansowanie wpływu PŻ i efektu spirali śmierci. Kluczowe będzie testowanie, czy koszt PŻ za wymianę nie jest zbyt dotkliwy i czy nie wymaga dodatkowych mechanik wsparcia (cechy, przedmioty, odpoczynek). Alternatywy oferują inne sposoby osiągnięcia podobnego celu (redukcji RNG, zarządzania zasobami) przy różnym poziomie złożoności.
