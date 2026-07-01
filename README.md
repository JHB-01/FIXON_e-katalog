# FIXON e-katalog - publikacja na GitHub Pages

Ten folder jest gotowa paczka do publikacji e-katalogu FIXON jako statycznej strony GitHub Pages.

## Co jest w paczce

- `index.html` - gotowy e-katalog, plik startowy strony.
- `.nojekyll` - plik pomocniczy dla GitHub Pages, zeby GitHub niczego nie przetwarzal.

## Najprostsza publikacja przez przegladarke

1. Wejdz na GitHub i utworz nowe repozytorium, np. `fixon-e-katalog`.
2. Wejdz do repozytorium i kliknij `Add file` -> `Upload files`.
3. Przeciagnij do uploadu pliki z tego folderu: `index.html`, `.nojekyll` oraz ten `README.md`.
4. Kliknij `Commit changes`.
5. Wejdz w `Settings` -> `Pages`.
6. W sekcji `Build and deployment` ustaw:
   - `Source`: `Deploy from a branch`
   - `Branch`: `main`
   - folder: `/ (root)`
7. Kliknij `Save`.
8. Po chwili GitHub poda adres strony, zwykle w formacie:
   `https://TWOJ_LOGIN.github.io/fixon-e-katalog/`

## Aktualizacja katalogu pozniej

1. W tym projekcie edytuj plik `e-katalog.html`.
2. Skopiuj go ponownie jako `github-e-katalog/index.html`.
3. Na GitHubie wejdz w `index.html`, kliknij edycje albo upload nowej wersji.
4. Zrob `Commit changes`.

## Wazne

Wgrywaj zawartosc folderu `github-e-katalog`, a nie caly folder jako podfolder repozytorium.
