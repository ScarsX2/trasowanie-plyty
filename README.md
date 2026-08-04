# Trasowanie płyty fundamentowej — Masywny Dom

Narzędzie do trasowania i kontroli wymiarów płyty fundamentowej na budowie.
Jeden plik HTML, **działa w 100% offline** — bez internetu, bez CDN, bez serwera.

## Otwórz

**https://scarsx2.github.io/trasowanie-plyty/**

Na budowie zwykle nie ma zasięgu, więc otwórz link raz w domu i zapisz stronę na telefonie
(Chrome → menu ⋮ → *Pobierz* / *Dodaj do ekranu głównego*). Potem działa bez sieci.

## Co robi

- **Dwa obrysy** — zewnętrzny i wewnętrzny, powiązane grubością ściany. Ten, którego nie zmierzysz, wylicza się z drugiego.
- **Obie przekątne dla obu obrysów** + różnica |A–C| − |B–D|, boki, kąty i odchyłki od 90°.
- **Warianty** MD69 / MD86 / MD100 + opcja lustrzana i osobny slot na aktualny projekt.
- **Podgląd na żywo** — narożniki przeciąga się palcem albo przesuwa przyciskami; wszystko przelicza się natychmiast. Odchyłki są przerysowane (×1…×100), żeby milimetry były widoczne.
- **Korekta narożników** — konkretne zalecenia typu „narożnik C: w lewo 2,3 mm, w dół 6,0 mm”, w trzech trybach dopasowania (najlepsze / baza A–B stała / ręczne).
- **Ustawienie budynku na płycie** — gdy płyta wyszła nierówno: przesuwasz cały obrys i widzisz zapas w każdym narożniku, z automatem szukającym najlepszego kompromisu.
- **Kontrola grubości ściany** na środku każdego boku.
- Kolejność trasowania krok po kroku, jednostki mm/cm/m, zapis zestawów pomiarów, raport tekstowy i wydruk do PDF.

## Uwagi

- Wymiary MD86 (11620 × 8260 zewn.) pochodzą z rzutu projektowego — **zweryfikuj przed użyciem na budowie**.
- MD69 i MD100 są puste, do uzupełnienia własnymi wartościami. Zapisują się w pamięci przeglądarki.
- Pomiar taśmą daje kształt obrysu, ale nie jego położenie względem drugiego obrysu — zmierzony obrys wewnętrzny jest nasuwany na zewnętrzny metodą najlepszego dopasowania. Do bezwzględnej kontroli grubości ściany użyj wprowadzania współrzędnych X/Y.
- Domyślna tolerancja: ±2 mm na boku i przekątnej, ±0,1° na kącie. Wszystko edytowalne.

## Aktualizacja

Plik źródłowy to `index.html`. Nadpisujesz, commitujesz, pushujesz — Pages odświeża się samo w minutę.
