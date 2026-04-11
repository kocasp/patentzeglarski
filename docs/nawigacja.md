# Podstawy nawigacji

Nawigacja to sztuka bezpiecznego prowadzenia jachtu od punktu wyjścia do celu. Na śródlądziu korzystamy głównie z map, GPS i obserwacji brzegu, ale znajomość zasad nawigacji jest niezbędna do bezpiecznej żeglugi.

---

## Jednostki i miary

### Odległość

- **Mila morska (Mm, NM)** = 1852 m (odpowiada jednej minucie łuku na południku)
- **Kabel** = 1/10 mili morskiej = 185,2 m
- **Stopa (ft)** = 30,48 cm (stosowana do głębokości na mapach anglosaskich)
- **Sążeń (fathom)** = 1,83 m = 6 stóp (historyczna jednostka głębokości)

### Prędkość

- **Węzeł (kn, kt)** = 1 mila morska na godzinę = 1,852 km/h
- Na śródlądziu często podaje się prędkość w km/h

### Kierunek

- Kierunki mierzy się w stopniach od 000° do 360° (północ = 000° lub 360°)
- Oznaczenia literowe: N (Północ), S (Południe), E (Wschód), W (Zachód) i ich kombinacje (NE, SW, NNE itp.)

---

## Kompas

### Budowa kompasu

Kompas magnetyczny wskazuje kierunek **bieguna magnetycznego Ziemi** (nie geograficznego). Zbudowany z:
- Igły magnetycznej lub karty kompasowej (pływającej w cieczy)
- Skali 0–360° lub 0–32 rumb
- Noniusza/linii kursowej (lubberline) wskazującej kurs
- Wypełnienia cieczą (gliceryna) redukującej drgania

### Typy kompasów

- **Kompas rufowy** – montowany za sternikiem, kompensowany pod jacht
- **Kompas busolowy (handheld)** – przenośny, używany do pomiarów namiarów
- **Kompas z pelengiem** – dodatkowa obrotowa skala do mierzenia namiarów

### Zrozumienie odchyleń kompasu

Kompas wskazuje **Północ Magnetyczną (Nm)**, która różni się od **Północy Geograficznej (Ng)**.

#### Deklinacja magnetyczna (D)

Kąt między Północą Geograficzną a Magnetyczną. Zależy od miejsca na Ziemi i zmienia się z czasem (ok. 0,1–0,2°/rok).

- Na mapach podaje się deklinację i jej roczną zmianę
- W Polsce (2024): ok. 4–6° E (wschodnia = igła wskazuje nieco na wschód od Ng)
- Wschodnia deklinacja: Nm jest na **prawo** od Ng

#### Dewiacja kompasu (d)

Odchylenie kompasu od Nm spowodowane przez metalowe elementy jachtu (maszt, silnik, elektronika).

- Mierzy się ją dla każdego kursu jachtu osobno
- Zapisuje w tabeli dewiacji lub na krzywej dewiacji
- Eliminuje się ją przez kompensację magnesami w kompasie

#### Przeliczenia między kursami

```
Kurs Kompasowy (KK)
    + Dewiacja (d) = Kurs Magnetyczny (KM)
    + Deklinacja (D) = Kurs Geograficzny (KG)
```

**Zapamiętaj skrót:** KK → (+dewiacja) → KM → (+deklinacja) → KG

Lub odwrotnie: KG → (-deklinacja) → KM → (-dewiacja) → KK

**Zasada znaków:**
- Wschodnia dewiacja/deklinacja: **dodajemy** (gdy idziemy KK → KG)
- Zachodnia: **odejmujemy**
- Lub: **CADET** – Compass Add East = True (KK + wsch. = KG)

---

## Mapy i plany portów

### Mapa morska i śródlądowa

**Mapa morska** (sea chart) – sporządzona w skali Mercatora; linie długości i szerokości są prostymi. Skala może być jednakowa tylko wzdłuż równolegników.

**Mapa śródlądowa** – często w skali topograficznej, z zaznaczonymi głębokościami, torami i oznakowaniem.

### Elementy mapy

| Element | Opis |
|---------|------|
| **Izobaty (izobatymetry)** | Linie jednakowej głębokości |
| **Suche skały** | Zaznaczone „+", trójkątem lub gwiazdką |
| **Mielizny** | Zaznaczone kropkami lub cieniowaniem |
| **Latarnie morskie** | Symbol "wieży" z sektorem światła |
| **Boje i pławy** | Symbole wg systemu IALA |
| **Prądy** | Strzałki kierunku i liczby prędkości |
| **Oznakowanie i tory** | Linie toru (leading lines) |

### Skala mapy

- **Duża skala** (np. 1:10 000) = plan portu – duże szczegóły, małe obszary
- **Mała skala** (np. 1:500 000) = mapa oceanu – małe szczegóły, wielki obszar

Uwaga: „duża skala" = duże liczby na mapie (szczegółowość), nie duży obszar!

### Mierzenie odległości na mapie

Na mapach morskich (Mercatora):
- Odległość mierzy się na skali długości geograficznej (boczne krawędzie mapy)
- 1 minuta łuku = 1 mila morska
- Cyrkiel porównujemy z boczną skalą minutową

---

## Wyznaczanie pozycji

### Pozycja obserwowana (fix)

Pozycja wyznaczona przez bezpośredni pomiar – namiar (kompasowy lub z GPS), obserwacja.

### Namiar na obiekt

**Namiar (bearing)** – kierunek kompasowy z jachtu do obiektu na lądzie (lub odwrotnie).

Aby wyznaczyć pozycję, potrzebujemy min. **dwóch namiarów** na różne obiekty (najlepiej pod kątem 60–90°):
1. Zmierz namiar na obiekt A
2. Zmierz namiar na obiekt B
3. Przelicz namiery z kursów kompasowych na geograficzne
4. Naryśuj linie pozycji na mapie (linia radialna przez każdy obiekt)
5. Przecięcie linii = Twoja pozycja

**Trójkąt błędu** – przy trzech namiarach często linie nie przecinają się w jednym punkcie; tworzą trójkąt. Pozycja jest wewnątrz trójkąta.

### Namiar wsteczny i przedni

- **Namiar przedni** – mierzony z jachtu na obiekt
- **Namiar wsteczny (back bearing)** – od obiektu do jachtu; = namiar przedni ± 180°

### Metoda trawersowania

Gdy płyniesz wzdłuż brzegu:
1. Zmierz namiar na obiekt gdy jest na trawersie (= 90° do Twojego kursu)
2. Odnotuj log (przebytą odległość)
3. Zmierz namiar ponownie po przejściu odcinka
4. Pozycję wyznacza skrzyżowanie namiarów na mapie

### Metoda czterokwadranta (quarterings)

Pozycja wyznaczona przez namiar 045° lub 315° na obiekt, następnie po przejściu do namiaru 090° lub 270° – odległość od obiektu = przebyta droga.

---

## Nawigacja GPS

### Jak działa GPS

System GPS (Global Positioning System) – konstelacja satelitów US DOD. Odbiornik oblicza pozycję przez:
1. Odbiór sygnałów z ≥3 satelitów (pozycja 2D) lub ≥4 (pozycja 3D z wysokością)
2. Mierzenie czasu dotarcia sygnałów
3. Obliczenie odległości od każdego satelity
4. Trilateria = punkty przecięcia sfer

**Dokładność:** typowo 3–10 m (odbiorniki cywilne); DGPS/WAAS = 1–3 m.

### Chartplotter

Chartplotter to połączenie GPS z mapą elektroniczną. Wyświetla:
- Pozycję jachtu na mapie w czasie rzeczywistym
- Kurs (COG – Course Over Ground) i prędkość (SOG)
- Waypoints i trasy
- Odległość do następnego punktu (DTW – Distance to Waypoint)
- Szacowany czas przybycia (ETA – Estimated Time of Arrival)

### Ograniczenia GPS

- Nie działa bez prądu
- Zależy od aktualizacji map (nieaktualne wersje mogą nie zawierać nowych pław lub zmian toru)
- Błąd pomiarowy może wynosić kilkadziesiąt metrów przy złej widoczności satelitów
- **Zawsze weryfikuj GPS obserwacją brzegu i mapą papierową**

---

## Kurs i odległość – obliczenia

### Trójkąt prędkości

Prędkość jachtu przez wodę (STW), prąd i wynikowy kurs nad dnem (COG) tworzą trójkąt wektorów:

```
Vektor STW (kurs i prędkość przez wodę)
    + Vektor prądu (kierunek i prędkość prądu)
    = Vektor SOG (kurs i prędkość nad dnem)
```

Jeśli znamy STW i prąd, możemy obliczyć kurs do zadania na kompasie aby osiągnąć żądany kurs nad dnem (COG).

### Wzór na czas, prędkość i odległość

```
D = V × T
V = D / T
T = D / V
```

Gdzie: D = dystans (Mm), V = prędkość (węzły), T = czas (godziny)

**Przykład:** Odległość 12 Mm przy prędkości 4 kn:
- T = 12 / 4 = 3 godziny

### Przeliczenie minut na godziny i odwrotnie

- 1,5 godziny = 1 h 30 min = 90 minut
- 45 minut = 0,75 godziny

---

## Planowanie trasy

### Etapy planowania

1. **Wyznaczenie trasy** – zaznacz waypoints na mapie lub chartplotterze
2. **Sprawdzenie głębokości** – izobaty na mapie; uwzględnij zanurzenie jachtu + bezpieczny zapas (0,5–1 m)
3. **Sprawdzenie przeszkód** – mielizny, pławy, mosty (prześwit)
4. **Obliczenie odległości i czasu** – realistyczna prędkość, uwzględnij postoje na śluzach
5. **Prognoza pogody** – sprawdź przed wyjściem i w trakcie trasy
6. **Plan awaryjny** – alternatywne schronienie jeśli warunki się pogorszą
7. **Powiadomienie rodziny** – zostaw plan trasy z kontaktem

### Waypoints i kursy

Trasę dzielimy na odcinki między waypointami. Dla każdego odcinka:
- Kurs (bearing) w stopniach
- Odległość w milach lub km
- Szacowany czas przejścia

---

## Wysokość słońca i czas

### Czas w nawigacji

- **UTC (Coordinated Universal Time)** – czas uniwersalny; Polska zimą = UTC+1, latem = UTC+2
- Na mapach morskich podaje się czas UTC
- Sytuacje awaryjne i łączność – zawsze podawaj czas UTC

### Wschód i zachód słońca

Ważne dla planowania żeglugi nocnej i doboru świateł:
- Oświetlenie nawigacyjne od zachodu do wschodu słońca
- Oświetlenie również przy każdej ograniczonej widoczności

---

## Orientacja bez przyrządów

### Orientacja przez Słońce

- Południek lokalny (południe słoneczne) – Słońce na południku, najwyżej nad horyzontem
- Wschód: Słońce od strony wschodniej
- Zachód: Słońce od strony zachodniej

### Gwiazda Polarna (Polaris)

Wskazuje Północ z dokładnością ok. 1°. Znajdź ją przez wydłużenie linii łączącej dwie ostatnie gwiazdy Wielkiego Wozu (Dubhe i Merak) × 5.

### Orientacja przez zegarek

Połóż zegarek (analogowy) poziomo. Skieruj wskazówkę godzinową na Słońce. Bisektrysa kąta między wskazówką i godziną 12 wyznacza południe (w strefie umiarkowanej półkuli północnej).

---

## Nawigacja śródlądowa – Mazury

### Specyfika jezior mazurskich

- Wody stosunkowo płytkie (średnio 5–10 m), liczne mielizny przy brzegach
- Szlaki wyznaczone tyczkami i tablicami
- GPS bardzo przydatny; mapy Babbela i Delius Klasing dla Mazur
- Widoczność terenu często ograniczona przez trzciny i wyspy – trudna orientacja w mgle

### Aplikacje i mapy elektroniczne dla Mazur

- Navionics (z mapą mazurską)
- Garmin BlueChart z Mazurami
- OpenCPN z bezpłatną mapą OSM
- Aplikacje mobilne: iSailor, NV Charts

### Numer identyfikacyjny jachtu

Każdy zarejestrowany jacht ma numer rejestracyjny widoczny na burcie (w Polsce: PZŻ/PZMWiNW + numer). Podaj go przy kontakcie z mariną lub WOPR-em.

---

## Prądy wodne

### Prądy na jeziorach

Na jeziorach mazurskich prądy są minimalne (zjawisko wiatrospadowe i termiczne). Wpływ na nawigację jest znikomy, ale przez połączone jeziora mogą przepływać prądy wywołane różnicą poziomów wody.

### Prądy na rzekach

Prąd rzeczny znacząco wpływa na nawigację:
- **Pod prąd** (w górę rzeki) – wolniejsza prędkość nad dnem; jacht dryfuje
- **Z prądem** (w dół rzeki) – większa prędkość; manewrowanie trudniejsze ze względu na większą SOG

Prędkość prądu rzecznego: 0,5–3 węzłów; uwzględniaj przy planowaniu kursu.

---

## Pomiar głębokości

### Echosonda

Pomiar ultradźwiękowy głębokości. Wyświetla głębokość pod przetwornikiem (transducer). Kalibracja:
- Głębokość pod kilem = wyświetlana − odległość przetwornika od kilu
- Głębokość rzeczywista = wyświetlana + odległość przetwornika od powierzchni wody

### Sondaż liną lub tyczką

Tradycyjna metoda: lina z obciążnikiem (ołów sondowy) lub tyczka z podziałką. Stosowana gdy echosonda nie działa lub przy cumowaniu na płytkiej wodzie.
