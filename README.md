# English-First Businesses in Seville 🏴󠁧󠁢󠁥󠁮󠁧󠁿🗺️

A directory of businesses and services in **Seville city** that operate primarily in English or cater to English speakers.

**Live site:** https://english-seville.vercel.app (auto-deployed from `main`)

## What's included

| Category | Count |
|----------|-------|
| Language Academies | 26 entries (4 independent + 18 English Connection locations) |
| International/Bilingual Schools | 12 entries |
| International Food Stores | 1 |
| British/Irish Pubs | 1 |
| **Total** | **38 verified entries** |

Categories covered:
- Language academies (English immersion, TEFL, Cambridge prep)
- International and bilingual schools
- British/Irish pubs
- International food stores
- More categories being added (expat services, coworking, translation)

## Map

Interactive Leaflet map with numbered markers, CartoDB light tiles, and responsive design. Optimised for mobile.

## Data sources

- Primary: independent web research (June 2026)
- Cross-referenced with: centros_compatibles (V3RNE42/centros_compatibles)
- Verification: curl HTTP status + `<title>` tag matching + phone prefix filtering (95/954/955 = Sevilla)

## Repo structure

```
├── index.html          # Main directory page (Leaflet map + cards)
├── favicon.ico         # 16x16 favicon
├── favicon-32.png      # 32x32 favicon
└── README.md           # This file
```

## Deployment

Automatic via Vercel. Push to `main` → deploys instantly.

## Related projects

- [centros_compatibles](https://github.com/V3RNE42/centros_compatibles) — Education centres in Seville metropolitan area (68 entries, 41 verified phones)

## Workflow

Built using the `data-discovery-workflow` Hermes skill:
1. Phase 0: Scope definition (Seville city, English-first)
2. Phase 1: Discovery using existing datasets + verified scraping
3. Phase 2: Data enrichment (phone, web, GPS verification via curl + title check)
4. Phase 3: HTML construction (Leaflet map + cards pattern)
5. Phase 4: GitHub push + Vercel deploy
