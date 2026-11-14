# Football League Manager — PWA

## Co zawiera
- terminarz każdy z każdym, mecz i rewanż (2–20 drużyn)
- edycja wyników i automatyczna tabela
- forma ostatnich pięciu spotkań
- statystyki ataku i obrony
- historia pozycji w tabeli
- symulacja końca sezonu
- prognozy 1/X/2 liczone z modelu Poisson + Elo
- automatyczny zapis lokalny oraz eksport/import kopii JSON
- PWA z cache offline

## Publikacja i instalacja
Aplikacja musi być udostępniona pod adresem HTTPS, np. przez GitHub Pages. Nie uruchamiaj jej przez otwieranie `index.html` z ZIP-a ani przez `file://` — wtedy instalacja PWA i service worker nie zadziałają.

Po opublikowaniu:
1. Otwórz adres HTTPS w Chrome na Androidzie.
2. W menu Chrome wybierz „Zainstaluj aplikację” (lub „Dodaj do ekranu głównego”).
3. Uruchom aplikację z ikony. Po pierwszym otwarciu zasoby zostaną zapisane do pracy offline.

Dane sezonu są zapisywane lokalnie w pamięci przeglądarki/aplikacji na tym urządzeniu. Eksportuj regularnie plik JSON jako kopię zapasową. Ten pakiet nie zawiera synchronizacji między urządzeniami.
