FOOTBALL LEAGUE MANAGER — WERSJA 3.0

NOWE FUNKCJE
- Herby drużyn: dodawanie własnych obrazów PNG/JPG/WebP w Ustawieniach.
- Kolorystyka: zielona, niebieska, czerwona i fioletowa.
- Daty kolejek: wybór daty pierwszej kolejki i odstępu między kolejkami.
- Awans i spadek: ustawienie liczby klubów awansujących/spadających; przy tworzeniu następnego sezonu podajesz nazwy nowych drużyn awansujących.
- Eksport tabeli do PDF przez systemowy dialog drukowania przeglądarki (wybierz „Zapisz jako PDF”).
- Archiwum wielu sezonów na urządzeniu.
- Eksport/import kopii JSON obejmującej bieżący sezon i archiwum.
- Zachowana zgodność z dotychczasowym zapisem sezonu v2.

PUBLIKACJA AKTUALIZACJI
W istniejącym repozytorium GitHub otwórz Code → Add file → Upload files.
Prześlij pliki z tej paczki do katalogu głównego repozytorium, zastępując istniejące:
index.html, app.js, manifest.webmanifest, sw.js, README.txt.
W folderze icons pozostaw istniejące icon-192.png i icon-512.png (można je ponownie przesłać, nie jest to konieczne).
Zatwierdź zmiany przyciskiem Commit changes.
GitHub Pages wdroży aktualizację automatycznie. Po wdrożeniu zamknij aplikację i uruchom ją ponownie z dostępem do internetu, aby service worker pobrał nową wersję.

UWAGA O DANYCH
Dane sezonów, herbów, ustawień i archiwum są przechowywane lokalnie w przeglądarce/aplikacji na tym urządzeniu. Nie są synchronizowane z innymi urządzeniami. Przed aktualizacją zalecany jest eksport kopii JSON w zakładce „Zapis i kopia”. Aktualizacja plików aplikacji nie powinna usuwać localStorage, ale kopia zapasowa jest zalecana.

INSTALACJA
Aplikacja działa jako PWA po udostępnieniu przez HTTPS (np. GitHub Pages). Po pierwszym uruchomieniu zasoby są cache'owane do pracy offline.
