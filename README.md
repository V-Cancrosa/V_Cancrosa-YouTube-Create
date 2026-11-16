# YT Thumbnails

Prosta, statyczna strona do podglądu miniaturek filmów YouTube. Wklej link do filmu albo jego 11-znakowy identyfikator, wybierz rozmiar i otwórz miniaturę.

## Uruchomienie lokalne

Otwórz `site/index.html` w przeglądarce. Projekt nie wymaga instalowania zależności ani kompilacji.

## GitHub Pages

Strona jest wdrażana automatycznie przez GitHub Actions po każdym pushu do gałęzi `main` oraz ręcznie z poziomu zakładki **Actions**. Workflow próbuje też włączyć GitHub Pages przy pierwszym uruchomieniu.

Jeśli pierwsze uruchomienie nie może włączyć Pages z powodu uprawnień, ustaw w repozytorium:

1. **Settings → Pages → Build and deployment → Source → GitHub Actions**.
2. W **Settings → Actions → General → Workflow permissions** pozostaw domyślne uprawnienia; workflow deklaruje wymagane uprawnienia samodzielnie.

Po zakończeniu workflow adres strony znajdziesz w **Settings → Pages**.
