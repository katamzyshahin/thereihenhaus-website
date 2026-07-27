# Das Reihenhaus – Website (Eleventy + Netlify CMS/Decap CMS)

## Struktur
- `src/index.njk` – Haupt-Template der Website
- `src/css/style.css` – Design (Farben, Layout)
- `src/_data/*.yaml` – Texte pro Sektion (Hero, Über uns, UGC, Affiliate, Digital Products, Kontakt, Sichtbarkeits-Toggles)
- `src/portfolio/*.md`, `src/testimonials/*.md`, `src/products/*.md` – einzelne Einträge (Projekte, Testimonials, Produkte)
- `src/admin/` – Content-Manager (erreichbar unter `/admin` nach dem Deployment)

## Lokal bauen (optional, nicht notwendig für Netlify)
```
npm install
npm run build
```
Netlify führt das automatisch bei jedem Push aus (siehe netlify.toml).

## Inhalte bearbeiten
Nach dem Setup (siehe Anleitung von Claude) unter `deine-domain/admin` einloggen und Inhalte direkt bearbeiten. Änderungen werden automatisch als Commit gespeichert und die Seite neu gebaut.
