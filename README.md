# Hi, I'm Asier 👋

I build practical software from Barcelona — automation, web scraping, and small full-stack tools that take a tedious manual process and run it end to end.

## Featured project

### 🚢 [Busca Prácticas — Deck Cadet Job Search Dashboard](https://github.com/bonsalvadorasier-blip/app-job-search-deck-cadet)

A local dashboard that automates the job hunt for a deck cadet looking for sea-time: it finds European shipping companies, digs through each one's website for the right contact, and sends a personalized application by email — then tracks every reply in one place.

- **Sources ~600 shipping companies** from Wikidata, maritime-association directories (ANAVE, VDR, Rederi, Armateurs de France, Interferry) and OpenStreetMap
- **Crawls each company's site** to find the best hiring contact (`cadets@`, `crewing@`, `jobs@`...), deobfuscates protected emails, and respects `robots.txt`
- **Sends and tracks applications** over Gmail (SMTP/IMAP), auto-classifying replies as interview / info request / rejection / automated
- **Simulation → Test → Real modes**, each in its own database, so nothing goes out until you're ready
- Pure Python standard library backend with a vanilla JS/HTML/CSS frontend — no heavy frameworks, runs entirely on your own machine

**Stack:** Python · SQLite · IMAP/SMTP · web scraping · vanilla JS

## What I'm into

- Turning a slow manual workflow into something that runs itself
- Pulling structured data out of messy real-world sources (directories, PDFs, half-broken company sites)
- Local-first tools over unnecessary cloud infrastructure

## 📍 Based in

Barcelona, Spain
