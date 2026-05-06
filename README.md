# Available .CX One-Word Domains (11,128)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-11%2C128%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .cx one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **11,128 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 11,128 domains · **Median ask:** $31.22 · **High-demand under $2,500:** 0

**Last updated:** 2026-05-06  
**Canonical page:** `https://unique.domains/domains/tld/cx`  
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/cx?utm_source=github&utm_medium=referral&utm_campaign=repo_cx_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./cx.csv">CSV</a> / <a href="./cx.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_cx_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_cx_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .CX search](https://unique.domains/domains/tld/cx?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_cx_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .CX search](https://unique.domains/domains/tld/cx?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_cx_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_cx_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .CX one-word domain catalog.

### Files

- `cx.csv` — public CSV extract (1,000 rows)
- `cx.json` — public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/cx-oneword-domains/main/cx.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain          | status    | ask_price | renewal_price | attractiveness | demand | length | registrar                     |
| --------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | ----------------------------- |
| travelers.cx    | available | $18.99    | $18.99        | 58             | 61     | 9      | namesilo                      |
| online.cx       | resell    | —         | —             | 70             | 62     | 7      | West263 International Limited |
| letsgo.cx       | available | $26.98    | —             | 57             | 31     | 7      | namecheap                     |
| agents.cx       | resell    | —         | —             | 56             | 50     | 6      | CentralNic Ltd                |
| inspiration.cx  | available | $26.98    | —             | 88             | 30     | 11     | namecheap                     |
| call.cx         | resell    | —         | —             | 80             | 37     | 4      | CentralNic Ltd                |
| rewards.cx      | available | $18.99    | $18.99        | 62             | 30     | 7      | namesilo                      |
| tickets.cx      | resell    | —         | —             | 64             | 34     | 7      | CentralNic Ltd                |
| spaces.cx       | available | $26.98    | —             | 54             | 30     | 6      | namecheap                     |
| traders.cx      | resell    | —         | —             | 60             | 26     | 7      | CentralNic Ltd                |
| doctors.cx      | available | $79.99    | —             | 56             | 26     | 7      | name.com                      |
| loans.cx        | resell    | —         | —             | 58             | 24     | 5      | CentralNic Ltd                |
| schools.cx      | available | $26.98    | —             | 72             | 24     | 7      | namecheap                     |
| shops.cx        | available | $79.99    | —             | 64             | 24     | 5      | name.com                      |
| whats.cx        | available | $18.99    | $18.99        | 58             | 24     | 5      | namesilo                      |
| echoes.cx       | available | $18.99    | $18.99        | 56             | 24     | 6      | namesilo                      |
| superhero.cx    | available | $26.98    | —             | 84             | 23     | 9      | namecheap                     |
| motorsport.cx   | available | $26.98    | —             | 74             | 23     | 10     | namecheap                     |
| deeplearning.cx | available | $26.98    | —             | 74             | 23     | 13     | namecheap                     |
| pros.cx         | available | $18.99    | $18.99        | 53             | 23     | 4      | namesilo                      |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 11,128 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 0 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/cx?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_cx_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/cx?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_cx_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_cx_oneword_domains&utm_content=related_pricing)

## 🧱 Field summary

- `domain` — Fully qualified domain name.
- `status` — Current acquisition state for the domain in the public extract.
- `purchase_price` — Visible purchase price when available.
- `renewal_price` — Visible renewal price when available.
- `attractiveness` — Composite naming score used as a decision-support signal.
- `demand` — Relative buyer-pressure score when available.
- `length` — Character count without the TLD.
- `registrar` — Registrar name when known.
- `created_at` — Creation timestamp when known.
- `expires_at` — Expiry timestamp when known.

See [DATA_DICTIONARY.md](./DATA_DICTIONARY.md) for full definitions and types.

## ⚠️ Methodology and caveats

This selection is focused entirely on one-word .cx domains. The names range from concise words like dozen.cx and swerve.cx to broader terms like effect.cx, trophy.cx, and examine.cx, plus longer options such as generaleducation.cx. For founders, the main question is whether the word is memorable, easy to say, and specific enough to anchor a brand without creating confusion. For investors, the key is price discipline: the median ask is 31.22, so quality differences matter more than headline pricing alone. When comparing these domains, weigh word clarity, commercial relevance, length, and the added adoption risk that can come with a non-mainstream extension like .cx.

- Favor strong, clear words over long or ambiguous terms
- Use price discipline: median ask is 31.22
- Short names like dozen.cx are easier to recall
- Non-mainstream .cx adds adoption and resale risk

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .CX One-Word Domains*. Version 2026-05-06. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .CX page](https://unique.domains/domains/tld/cx?utm_source=github&utm_medium=referral&utm_campaign=repo_cx_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_cx_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_cx_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_cx_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
