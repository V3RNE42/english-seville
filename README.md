# English-First Businesses in Seville 🏴󠁧󠁢󠁥󠁮󠁧󠁿🗺️

A directory of **non-school businesses and services** in Seville city that operate
primarily in English or cater to English speakers.

> ⚠️ **This repo does NOT include schools or language academies.**
> Those are covered in [centros_compatibles](https://github.com/V3RNE42/centros_compatibles)
> (68 education centres with 41 verified phones).

**Live site:** https://english-seville.vercel.app

## Scope

Only **non-educational** English-first businesses in **Seville city** (41001–41020).

| Category | Status | Count |
|----------|--------|-------|
| Translation & Interpretation | 🟢 Complete | 12 |
| Tourist Guides / Tours | 🟢 Complete | 7 |
| Hotels & Accommodation | 🟢 Complete | 6 |
| Expat Services (legal, tax, relocation) | 🟢 Complete | 3 |
| Coworking Studios | 🟡 Partial | 2 |
| British/Irish Pubs | 🟡 Partial | 3 |
| International Food Stores | 🟡 Partial | 1 |
| English-speaking Medical/Dental | 🔴 Commented out | 0 |
| Real Estate (English-speaking) | 🔴 Pending | 0 |
| **Total verified** | | **34** |

**Legend:** 🟢 Complete (≥5) / 🟡 Partial (1-4) / 🔴 Not yet researched

## Map

Interactive Leaflet map with numbered markers, CartoDB light tiles, and
responsive design. Optimised for mobile.

## Data sources

- Independent web research
- Cross-referenced with existing user repos (avoiding duplicates)
- Verification: curl HTTP status + `<title>` tag matching + regional phone filters

## Repo structure

```
├── index.html        # Main directory (Leaflet map + cards)
├── PLAN.yaml         # Research roadmap for pending categories
├── README.md         # This file
└── favicon.ico/.png  # Site icon
```

## Deployment

Automatic via Vercel. Push to `main` → deploys instantly.

## Related projects

- [centros_compatibles](https://github.com/V3RNE42/centros_compatibles) — Education centres in Seville (68 entries, schools + academies only, no overlap with this repo)

## Workflow

Built using the `data-discovery-workflow` Hermes skill (subject-agnostic).
