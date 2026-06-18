# SEO Audyt — Narzędzie do analizy stron

Darmowe narzędzie do kompleksowego audytu SEO oparte na Google PageSpeed Insights API.

## Demo

👉 [Otwórz narzędzie](https://TWOJA-NAZWA.github.io/seo-audyt/)

## Funkcje (wersja Light)

- ✅ Google PageSpeed Insights (mobile + desktop)
- ✅ On-Page SEO: tytuł, meta description, nagłówki, alt obrazów, canonical
- ✅ Podgląd fragmentu SERP z walidacją długości
- ✅ Core Web Vitals: LCP, CLS, FCP, TBT, Speed Index, TTI
- ✅ GEO / AI-readiness: llms.txt, Schema, E-E-A-T
- ✅ Wykresy (Chart.js): donuty wyników, słupki kategorii, CWV
- ✅ Export do PDF (wbudowany, przez Print → Zapisz jako PDF)
- ✅ Sekcja linki i backlinki z zaleceniami
- ✅ Techniczne SEO: SSL, robots.txt, sitemap, Schema.org
- ✅ Responsywny — działa na telefonie i tablecie

## Uruchomienie na GitHub Pages

1. Zrób Fork tego repozytorium lub stwórz nowe
2. Wgraj plik `index.html`
3. Wejdź w **Settings → Pages → Source: Deploy from branch → main → / (root)**
4. Po chwili strona będzie dostępna pod `https://TWOJA-NAZWA.github.io/NAZWA-REPO/`

## Uruchomienie lokalnie

Otwórz `index.html` bezpośrednio w przeglądarce — nie wymaga serwera.

## Export PDF

Kliknij **"Eksportuj PDF"** → otworzy się okno drukowania → wybierz **"Zapisz jako PDF"**.  
Raport zawiera wszystkie sekcje w formacie A4 zoptymalizowanym do druku.

## Technologie

- Vanilla HTML/CSS/JS — zero zależności backendowych
- [Chart.js 4.4](https://www.chartjs.org/) — wykresy
- [Google PageSpeed Insights API v5](https://developers.google.com/speed/docs/insights/v5/get-started) — darmowe, bez klucza API

## Roadmap (wersja Full / PC)

- [ ] Backlinki (Ahrefs / Semrush API)
- [ ] Crawl wewnętrzny (nagłówki HTTP, redirect chain)
- [ ] Historia audytów z porównaniem zmian w czasie
- [ ] Analiza konkurencji
- [ ] Eksport do XLSX

## Licencja

MIT — możesz używać, modyfikować i dystrybuować.
