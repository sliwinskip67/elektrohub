# Mini Sklep – szybkie uruchomienie

Masz gotowy `index.html`. Wystarczy go opublikować:

## Opcja A: Netlify Drop (najszybsza)
1. Wejdź na https://app.netlify.com/drop
2. Przeciągnij i upuść plik `index.html`.
3. Otrzymasz natychmiast działający link (możesz go potem spersonalizować).

## Opcja B: GitHub Pages
1. Załóż repozytorium `minisklep` (Public).
2. Wgraj `index.html` do repo.
3. Wejdź w **Settings → Pages** i ustaw **Deploy from a branch**, branch `main`, folder `/ (root)`.
4. Link będzie w formacie: `https://twoja-nazwa.github.io/minisklep/`

## Edycja produktów
W pliku `index.html` znajdź sekcję `const PRODUCTS` i zmień:
- `title`, `desc`, `price`, `image`, `paymentLink`

Powodzenia!