# svektor.se

Webbplats för **Svektor AB** — ett litet, oberoende bolag som bygger små appar.

Statisk sida som publiceras via GitHub Pages på <https://svektor.se> (se `CNAME`).

## Struktur

| Fil | Sida |
|-----|------|
| `index.html` | Startsida (svenska) |
| `support.html` | Support (svenska) |
| `integritet.html` | Integritetspolicy (svenska) |
| `en/index.html` | Home (engelska) |
| `en/support.html` | Support (engelska) |
| `en/privacy.html` | Privacy Policy (engelska) |
| `assets/style.css` | All styling (grafisk profil delad med apparna: marinblå `#002B5C`, signalgul `#F5C400`) |
| `favicon.svg` | Ikon / logotypmärke |
| `404.html`, `robots.txt`, `sitemap.xml` | Övrigt |

## Utveckla lokalt

Ingen byggprocess. Öppna `index.html` i en webbläsare, eller kör en enkel server:

```bash
python3 -m http.server 8000
# http://localhost:8000
```

## Redigera innehåll

- Text ändras direkt i respektive `.html`-fil. Håll svenska och engelska versionerna i synk.
- Färger, typsnitt och komponenter styrs från `assets/style.css` (CSS-variabler överst).
- Kontaktadresser: `info@svektor.se` (allmänt) och `support@svektor.se` (support).
