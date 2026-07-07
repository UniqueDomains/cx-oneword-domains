# Available .CX One-Word Domains (11,135)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-11%2C135%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .cx one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **11,135 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 11,135 domains · **Median ask:** $23.70 · **High-demand under $2,500:** 0

**Last updated:** 2026-07-07
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

- `cx.csv`, public CSV extract (1,000 rows)
- `cx.json`, public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md`, field definitions for the exported files
- `METHODOLOGY.md`, scope, refresh policy, and caveats
- `CHANGELOG.md`, latest snapshot metadata
- `CITATION.cff`, machine-readable dataset citation metadata
- `LICENSE`, terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/cx-oneword-domains/main/cx.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain   | status    | ask_price | renewal_price | attractiveness | demand | length | registrar                     |
| -------- | --------- | --------- | ------------- | -------------- | ------ | ------ | ----------------------------- |
| ago.cx   | available | $18.99    | $18.99        | medium         | low    | 3      | namesilo                      |
| load.cx  | resell    | $26.98    | —             | high           | low    | 4      | CentralNic Ltd                |
| bce.cx   | premium   | $18.99    | $18.99        | medium         | low    | 3      | namesilo                      |
| coy.cx   | available | $18.99    | $18.99        | medium         | low    | 3      | namesilo                      |
| boost.cx | resell    | $26.98    | —             | high           | low    | 5      | CentralNic Ltd                |
| boat.cx  | premium   | $18.99    | $18.99        | high           | low    | 4      | namesilo                      |
| leg.cx   | available | $18.99    | $18.99        | high           | low    | 3      | namesilo                      |
| air.cx   | resell    | —         | —             | high           | medium | 3      | CentralNic Ltd                |
| tire.cx  | premium   | $18.99    | $18.99        | high           | low    | 4      | namesilo                      |
| lip.cx   | available | $18.99    | $18.99        | high           | low    | 3      | namesilo                      |
| ask.cx   | resell    | —         | —             | high           | medium | 3      | West263 International Limited |
| wool.cx  | premium   | $18.99    | $18.99        | medium         | low    | 4      | namesilo                      |
| mid.cx   | available | $26.98    | —             | high           | low    | 3      | namecheap                     |
| hit.cx   | resell    | —         | —             | high           | low    | 3      | CentralNic Ltd                |
| gates.cx | premium   | $18.99    | $18.99        | high           | low    | 5      | namesilo                      |
| oar.cx   | available | $18.99    | $18.99        | medium         | low    | 3      | namesilo                      |
| led.cx   | resell    | —         | —             | high           | low    | 3      | West263 International Limited |
| wagon.cx | premium   | $18.99    | $18.99        | medium         | low    | 5      | namesilo                      |
| sad.cx   | available | $26.98    | —             | high           | low    | 3      | namecheap                     |
| lot.cx   | resell    | —         | —             | medium         | low    | 3      | CentralNic Ltd                |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 11,135 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 0 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/cx?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_cx_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/cx?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_cx_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_cx_oneword_domains&utm_content=related_pricing)

## 🧱 Field summary

- `domain`, Fully qualified domain name.
- `status`, Current acquisition state for the domain in the public extract.
- `purchase_price`, Visible purchase price when available.
- `renewal_price`, Visible renewal price when available.
- `attractiveness`, Public composite naming band used as a decision-support signal.
- `demand`, Public buyer-pressure band when available.
- `length`, Character count without the TLD.
- `registrar`, Registrar name when known.
- `created_at`, Creation timestamp when known.
- `expires_at`, Expiry timestamp when known.

See [DATA_DICTIONARY.md](./DATA_DICTIONARY.md) for full definitions and types.

## ⚠️ Methodology and caveats

This selection includes 11,135 one-word .CX domain names, covering everyday terms, brand-style names, and niche phrases such as FinalFour.cx, ShopAround.cx, and HerbalTea.cx. With a median asking price near $24, most of these domains are priced for fast evaluation rather than long negotiation. Because .CX carries no industry restriction, the mix spans food, lifestyle, retail, and generic one-word concepts, giving both investors and founders a broad pool to compare before narrowing to a shortlist.

- 11,135 one-word .CX domains available for comparison
- Median asking price near $24 across the selection
- Mix of brandable names, generic terms, and niche phrases
- Updated daily to reflect current asking prices

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .CX One-Word Domains*. Version 2026-07-07. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .CX page](https://unique.domains/domains/tld/cx?utm_source=github&utm_medium=referral&utm_campaign=repo_cx_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_cx_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_cx_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_cx_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
