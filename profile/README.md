# Cookest

**A kitchen companion app built as a PAP (Prova de Aptidão Profissional) school project.**

Cookest helps users discover recipes, manage their meal planning, and explore nutritional data — with a mobile-first experience backed by a structured Rust API and a curated food dataset.

---

## Repositories

| Repo | Description | Stack |
|------|-------------|-------|
| [`Cookest`](https://github.com/Cookest/Cookest) | Rust/Actix-Web REST API. Handles auth, recipes, user data, and subscriptions. | Rust, Actix-Web, PostgreSQL |
| [`app`](https://github.com/Cookest/app) | Flutter mobile app. iOS + Android client for the API. | Dart, Flutter |
| [`docs`](https://github.com/Cookest/docs) | Documentation site — API reference, build guides, architecture notes. | Next.js, Fumadocs |

---

## Documentation

Full project documentation is available at:

**[cookest.github.io/docs](https://cookest.github.io/docs)** *(or the deployed URL for the docs repo)*

Covers the API (endpoints, auth flow, database schema), the Flutter app (setup, navigation, feature flags), and the ETL pipeline that feeds the food dataset.

---

## Tech at a glance

- **API** — Rust (Actix-Web 4), JWT auth, role-based access, PostgreSQL
- **Mobile** — Flutter, provider state management, custom design system
- **Data** — Python ETL pipeline ingesting MM-Food-100K, USDA, and TheMealDB
- **Docs** — Fumadocs + Next.js, deployed via GitHub Pages / Vercel

---

*PAP · 2025*
