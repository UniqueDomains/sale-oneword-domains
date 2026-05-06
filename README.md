# Available .SALE One-Word Domains (12,077)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-12%2C077%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .sale one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **12,077 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 12,077 domains · **Median ask:** $47.35 · **High-demand under $2,500:** 0

**Last updated:** 2026-05-06  
**Canonical page:** `https://unique.domains/domains/tld/sale`  
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/sale?utm_source=github&utm_medium=referral&utm_campaign=repo_sale_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./sale.csv">CSV</a> / <a href="./sale.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_sale_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_sale_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .SALE search](https://unique.domains/domains/tld/sale?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_sale_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .SALE search](https://unique.domains/domains/tld/sale?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_sale_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_sale_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .SALE one-word domain catalog.

### Files

- `sale.csv` — public CSV extract (1,000 rows)
- `sale.json` — public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/sale-oneword-domains/main/sale.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain           | status    | ask_price | renewal_price | attractiveness | demand | length | registrar                                                 |
| ---------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | --------------------------------------------------------- |
| forces.sale      | available | $5.99     | —             | 82             | 12     | 6      | name.com                                                  |
| getup.sale       | available | $5.99     | —             | 82             | 14     | 6      | name.com                                                  |
| dogsit.sale      | available | $5.99     | —             | 96             | 2      | 6      | name.com                                                  |
| edamame.sale     | available | $5.99     | —             | 80             | 9      | 7      | name.com                                                  |
| gearup.sale      | available | $5.99     | —             | 80             | 16     | 7      | name.com                                                  |
| playon.sale      | available | $5.99     | —             | 80             | 14     | 7      | name.com                                                  |
| QandA.sale       | available | $48.98    | —             | 80             | 10     | 7      | namecheap                                                 |
| pierogi.sale     | available | $5.99     | —             | 82             | 7      | 7      | name.com                                                  |
| rumcake.sale     | available | $5.99     | —             | 81             | 3      | 8      | name.com                                                  |
| beawake.sale     | available | $5.99     | —             | 84             | 3      | 8      | name.com                                                  |
| chaitea.sale     | available | $5.99     | —             | 86             | 3      | 8      | name.com                                                  |
| spectra.sale     | available | $5.99     | —             | 62             | 34     | 7      | name.com                                                  |
| agents.sale      | resell    | —         | —             | 56             | 50     | 6      | Global Domains International, Inc. DBA DomainCostClub.com |
| travelers.sale   | premium   | $118.80   | $118.80       | 58             | 61     | 9      | namesilo                                                  |
| letsgo.sale      | available | $5.99     | —             | 57             | 31     | 7      | name.com                                                  |
| wealth.sale      | resell    | —         | —             | 84             | 31     | 6      | Global Domains International, Inc. DBA DomainCostClub.com |
| RedSox.sale      | premium   | $84       | $84           | 72             | 60     | 7      | namecheap                                                 |
| inspiration.sale | available | $5.99     | —             | 88             | 30     | 11     | name.com                                                  |
| instore.sale     | resell    | —         | —             | 74             | 12     | 8      | GoDaddy.com, LLC                                          |
| Books.sale       | premium   | $1,400    | $1,400        | 52             | 49     | 5      | namecheap                                                 |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 12,077 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 0 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/sale?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_sale_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/sale?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_sale_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_sale_oneword_domains&utm_content=related_pricing)

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

This selection is entirely made up of one-word .sale domains. The extension signals promotions, commerce, discounts, or direct-response intent, so the strongest names are the ones where the word and the extension read naturally together. Examples like Gearup.sale, Useit.sale, Getup.sale, and Dogsit.sale feel more intuitive than words with weak retail or offer-based meaning. When comparing these domains, focus on how clearly the name fits a sales context, how memorable it sounds aloud, and whether the asking price justifies the term’s flexibility. The median ask is 47.35, which keeps attention on fit, clarity, and renewal discipline rather than headline pricing.

- Best fits are words that pair naturally with .sale
- Short, clear verbs and nouns tend to read more cleanly
- Median ask is 47.35, so price gaps should be justified
- Check trademark overlap before choosing brand-like terms

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .SALE One-Word Domains*. Version 2026-05-06. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .SALE page](https://unique.domains/domains/tld/sale?utm_source=github&utm_medium=referral&utm_campaign=repo_sale_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_sale_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_sale_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_sale_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
