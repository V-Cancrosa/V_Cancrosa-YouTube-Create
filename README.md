# YT Thumbnails

Statyczna strona do podglądu miniaturek filmów YouTube oraz przygotowywania promptów do nowych koncepcji miniaturek.

- `site/index.html` — podgląd istniejącej miniatury na podstawie linku lub identyfikatora filmu.
- `site/studio.html` — kreator promptu na podstawie gry, motywu i kierunku wizualnego.

## Uruchomienie lokalne

Otwórz `site/index.html` w przeglądarce. Studio jest dostępne pod `site/studio.html`. Projekt nie wymaga instalowania zależności ani kompilacji.

## GitHub Pages

Strona jest wdrażana automatycznie przez GitHub Actions po każdym pushu do gałęzi `main` oraz ręcznie z poziomu zakładki **Actions**. Workflow próbuje też włączyć GitHub Pages przy pierwszym uruchomieniu.

Jeśli pierwsze uruchomienie nie może włączyć Pages z powodu uprawnień, ustaw w repozytorium:

1. **Settings → Pages → Build and deployment → Source → GitHub Actions**.
2. W **Settings → Actions → General → Workflow permissions** pozostaw domyślne uprawnienia; workflow deklaruje wymagane uprawnienia samodzielnie.

Po zakończeniu workflow adres strony znajdziesz w **Settings → Pages**.
