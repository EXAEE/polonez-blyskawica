# 18. Auto-Transform & Zmienna Sylwetka – jak to mogłoby faktycznie działać

Dokument eksploracyjny. Cel: znaleźć rozwiązania, które mają szansę działać w realnym świecie, a nie tylko wyglądać jak Transformers.

---

## Część A: System zmiennej sylwetki (Body Themes)

### Idea
Jeden bazowy samochód + zestawy paneli, które zmieniają charakter wizualny i częściowo funkcjonalny.

### Jak zaprojektować, żeby działało

**1. Standaryzowany interfejs mocowania**
- Na bazowej karoserii (lub na spaceframe) stałe punkty mocowania: kołki pozycjonujące + gniazda śrub / szybkozłączy.
- Każdy panel (dach, klapa, błotnik, zderzak, listwa) ma kompatybilne otwory/uchwyty.
- Cel: wymiana kompletu paneli w 30–90 minut przez 1–2 osoby.

**2. Materiały paneli**
- Druk 3D dużych segmentów (dzielone, skręcane)
- Laminat / kompozyt na formie
- Blacha aluminiowa + wzmocnienia
- Sklejka + laminat (najtańsza ścieżka prototypowa)

**3. Przykładowe motywy**
- **Borewicz Theme** – okrągłe reflektory (nakładki lub wymienne pasy przednie), inne zderzaki, detale
- **Cargo Theme** – podwyższony dach (sztywny lub częściowo składany)
- **Truck Theme** – zdemontowana klapa + dach tylny → otwarta skrzynia lub nadstawka
- **Modern / Cyber Theme** – ostre linie, inne światła, panele z innym charakterem

**4. Co jest realne już teraz**
Pełny system wymiennych paneli jest całkowicie wykonalny w duchu Circular DIY. Nie wymaga siłowników ani skomplikowanej automatyki. To najlepszy punkt startowy.

---

## Część B: Auto-Transform (Caro Plus ↔ Karetka ↔ Truck)

### Cel wizji
Samochód, który w kilka–kilkanaście minut zmienia konfigurację nadwozia między hatchbackiem, podwyższoną wersją użytkową a pick-upem.

### Twarda ocena rzeczywistości

Pełna, automatyczna, „transformerowa” zmiana całego nadwozia na oryginalnej karoserii Poloneza jest ekstremalnie trudna z powodów:
- sztywności i nośności struktury
- uszczelnienia i hałasu
- bezpieczeństwa w każdej pozycji
- masy ruchomych elementów
- homologacji

Dlatego dzielimy problem na warstwy, od najbardziej realnej do najbardziej ambitnej.

---

### Warstwa 1 – Najbardziej realna: Modułowa tylna sekcja + podnoszony dach

**Mechanizm:**

1. **Dach segmentowy (2–3 segmenty)**  
   - Segmenty dachu od słupka B do tyłu są zawieszone na prowadnicach / zawiasach.  
   - Siłowniki elektryczne lub hydrauliczne unoszą je do pozycji „Cargo” (podwyższenie o 30–50 cm).  
   - W pozycji dolnej dach tworzy klasyczną linię Caro Plus.  
   - Inspiracja: kampery z podnoszonym dachem + uproszczony C70.

2. **Tylna klapa + panel**  
   - Klapa bagażnika i dolny panel tylny mogą być odchylane lub zdejmowane.  
   - Po uniesieniu dachu i złożeniu/odjęciu klapy powstaje otwarta przestrzeń ładunkowa (Truck-like) lub zamknięta wysoka (Karetka).

3. **Blokady**  
   - Mechaniczne blokady w każdej pozycji (dolna i górna).  
   - Czujniki położenia + zakaz jazdy przy niepełnym zablokowaniu.

**Napęd transformacji:**
- Siłowniki liniowe 12/24 V (z systemu EV) lub mała hydraulika.
- Czas transformacji: 1–4 minuty.

**Zalety:**  
Da się to zbudować. Masa ruchoma jest ograniczona. Bazowa struktura auta pozostaje nośna.

---

### Warstwa 2 – Ambitniejsza: Składana „skrzynia” Truck

Dodatkowy mechanizm:
- Boki tylnej części nadwozia (za słupkiem C) składają się na zewnątrz lub do wewnątrz jak burty.
- Podłoga bagażnika wysuwa się / przedłuża.
- Wymaga wzmocnionych zawiasów i blokad obciążeniowych.

To już mocno komplikuje uszczelnienie i sztywność.

---

### Warstwa 3 – Pełny Auto-Transform (wizja)

Aby zbliżyć się do Transformers:
- Całe nadwozie projektowane od początku jako system ruchomych modułów na spaceframe.
- Oryginalna karoseria Poloneza przestaje być nośnikiem – staje się tylko „skórą” lub punktem wyjścia stylistycznym.
- Wymaga dedykowanego podwozia, zaawansowanych siłowników, komputerowego sterowania sekwencją i bardzo poważnych testów bezpieczeństwa.

Na obecnym etapie projektu traktujemy to jako **kierunek badawczy**, nie jako najbliższy milestone.

---

## Propozycja sekwencji transformacji (Warstwa 1)

**Caro Plus → Karetka/Cargo:**
1. Odblokowanie dachu
2. Uniesienie segmentów dachu siłownikami
3. Zablokowanie w pozycji górnej
4. Ewentualne rozłożenie bocznych ścianek/plandeści

**Caro Plus → Truck:**
1. Uniesienie lub demontaż tylnego segmentu dachu
2. Odchylenie / zdjęcie klapy
3. Odblokowanie i złożenie bocznych paneli (jeśli są)
4. Zablokowanie konfiguracji otwartej

**Powrót** – sekwencja odwrotna + obowiązkowe sprawdzenie uszczelnień i blokad.

---

## Kluczowe problemy do rozwiązania (żeby działało)

1. **Sztywność w każdej pozycji** – auto nie może „pływać” gdy dach jest uniesiony.
2. **Uszczelnienie** – woda i hałas.
3. **Blokady awaryjne** – na wypadek awarii siłowników.
4. **Środek ciężkości** – uniesiony dach zmienia zachowanie.
5. **Masa i zużycie energii** – siłowniki nie mogą zjadać zbyt dużo zasięgu.
6. **Homologacja** – zmiana sylwetki w ruchu lub nawet na postoju może być problematyczna prawnie.

---

## Rekomendowana ścieżka rozwoju

1. Najpierw **system wymiennych paneli** (Body Themes) – szybki, tani, zgodny z DIY.
2. Równolegle prototyp **jednego segmentu podnoszonego dachu** na makiecie lub na jednym aucie testowym.
3. Dopiero po opanowaniu mechaniki i blokad – próba pełniejszej sekwencji.
4. Pełny Auto-Transform zostaje wizją, która nabierze sensu przy ewentualnym przejściu na własne podwozie.

---

To podejście zachowuje ducha Transformers, ale opiera się na mechanice, którą da się realnie zaprojektować, zbudować i utrzymać.
