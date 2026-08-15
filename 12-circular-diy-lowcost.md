# 12. Circular DIY + Low-Cost Redesign

**Nowe baseline (16.08.2026):**  
Maksymalna możliwa liczba elementów do samodzielnego wydrukowania na drukarce 3D lub pospawania w warunkach garażowych/DIY, przy jednoczesnym agresywnym użyciu upcyclingu, recyclingu i reuse, oraz utrzymaniu rozsądnego kosztu całkowitego.

Maintainability First pozostaje w mocy. To jest jego niskokosztowa, circularna ewolucja.

---

## Hierarchia materiałów i metod (od preferowanych)

1. **Reuse / Upcycle** – części z rozbitego Leafa, Tesli, Volt, przemysłowego złomu, oryginalnego Poloneza.
2. **Spawanie DIY** – stal kątownik / rura / blacha ze złomu lub hurtowni (MIG najlepiej).
3. **Druk 3D** – prowadnice, dystanse, klipsy, kanały, pokrywy, uchwyty, jigs, elementy niskiego obciążenia.
4. **Nowe kupione** – tylko tam, gdzie bezpieczeństwo lub niezawodność tego wymaga (złącza HV wysokoprądowe, styczniki, izolacja krytyczna, BMS jeśli nie da się użyć oryginalnego).

### Twarde limity bezpieczeństwa (nie do negocjacji)

- Główne ścieżki obciążenia (mocowanie silnika, ramy kaset baterii pod obciążeniem crash/wibracji) → **metal** (spawany lub solidnie skręcany).
- Obudowy baterii muszą zapewniać izolację elektryczną + ochronę mechaniczną + podstawową odporność ogniową. Czysty PLA/PETG jako jedyna ścianka kasety jest niedopuszczalny.
- 3D print używamy intensywnie, ale jako elementy pomocnicze, prowadzące, osłonowe i montażowe, nie jako główny nośnik sił crashowych.

---

## Power Pack (silnik + reduktor) – wersja circular DIY

**Preferowane źródła silnika (kolejność kosztowa):**
- Nissan Leaf EM57 (używany, rynek PL 2026: często 1,4–4,5 tys. PLN) – dobry moment, znany, dużo wiedzy społeczności.
- Inne używane jednostki z Leaf / e-NV200 / podobnych.
- Tesla Small Drive Unit – droższy, ale mocniejszy (jeśli budżet pozwala).
- Przemysłowe silniki AC + własny reduktor (wymaga więcej inżynierii).

**Rama power packu:**
- Spawana z kątownika / rury prostokątnej ze złomu lub taniej stali.
- Punkty mocowania do oryginalnych łap silnika Poloneza + dodatkowe wzmocnienia.
- 3D printed: dystanse, prowadnice przy montażu, osłony, uchwyty do złączy, jigs do spawania.

**Dock:**
- Mechaniczne pozycjonowanie + złącza HV/cooling/data.
- Część strukturalna spawana/skręcana, część prowadząca i osłonowa drukowana.

---

## Kasety baterii – wersja circular DIY

**Moduły:**  
Tesla Model S/X modules, Leaf modules, BYD blade (jeśli dostępne tanio), inne z rozbitek.  
Cel: kupować moduły, nie całe paczki fabryczne.

**Konstrukcja kasety:**
- Rama zewnętrzna: spawana lub solidnie skręcana z kątownika stalowego / aluminiowego (reuse blach i profili).
- Dno i wzmocnienia: blacha lub kratownica.
- Wewnętrzne prowadnice, dystanse między modułami, uchwyty, izolatory, kanały kablowe, pokrywy górne → **druk 3D** (PETG/ABS/nylon, ewentualnie z wkładkami metalowymi).
- Izolacja elektryczna: arkusze NOMEX / G10 / micarta / gruba taśma izolacyjna + powietrze.
- Szybkozłącza: kupione wysokoprądowe + interlock (tu nie oszczędzamy na bezpieczeństwie) lub dobrze zaprojektowane z upcyclingu jeśli spełniają normy.

**Cel montażu:** jedna osoba + podstawowe narzędzia ma wyciągnąć kasetę po odłączeniu złączy.

---

## Strategia kosztowa (cel)

Przy agresywnym upcyclingu i własnej robociźnie realny budżet materiałów na przyzwoitą konwersję Caro Plus / Borewicz może zejść w okolice **45–80k PLN** (zależnie od szczęścia na rynku wtórnym modułów i silnika).

To podejście jest spójne z duchem projektu: nie kupujemy gotowego luksusu, budujemy zrozumiały, naprawialny, możliwie tani system.
