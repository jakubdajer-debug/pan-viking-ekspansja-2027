# Pan Viking – Ekspansja 2027

Aplikacja planowania ekspansji od Q4 2026 do Q4 2027, przeniesiona z oryginalnego pliku HTML bez zmiany wyglądu i logiki.

## Uruchomienie

Otwórz `index.html` w przeglądarce lub odwiedź stronę opublikowaną przez GitHub Pages.

## Funkcje

- Interaktywna mapa Polski i planowanie obszarów obsługi.
- Planowanie w kwartałach Q4 2026–Q4 2027.
- Scenariusze A, B i C.
- Zapis planów w lokalnej pamięci przeglądarki.
- Generowanie raportów PDF.

## Dane

Plany są zapisywane w `localStorage` dla danej przeglądarki i adresu strony. Nie są synchronizowane między komputerami ani przesyłane do repozytorium. Dane zapisane podczas korzystania z lokalnego pliku HTML nie przechodzą automatycznie na adres GitHub Pages. Podkłady mapowe Esri wymagają połączenia z internetem.

## Publikacja

W ustawieniach repozytorium wybierz **Pages → Deploy from a branch → main → / (root)** i zapisz.

Plik `index.html` zawiera całą aplikację, osadzone dane mapowe i biblioteki. Nie wymaga instalacji zależności ani kompilacji.
