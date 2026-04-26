# Available .PARTS One-Word Domains (11,775)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-11%2C775%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .parts one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **11,775 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 11,775 domains

**Last updated:** 2026-04-26  
**Canonical page:** `https://unique.domains/domains/tld/parts`  
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/parts?utm_source=github&utm_medium=referral&utm_campaign=repo_parts_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./parts.csv">CSV</a> / <a href="./parts.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_parts_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_parts_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .PARTS search](https://unique.domains/domains/tld/parts?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_parts_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .PARTS search](https://unique.domains/domains/tld/parts?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_parts_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_parts_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .PARTS one-word domain catalog.

### Files

- `parts.csv` — public CSV extract (1,000 rows)
- `parts.json` — public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/parts-oneword-domains/main/parts.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain         | status    | ask_price | renewal_price | attractiveness | demand | length | registrar |
| -------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | --------- |
| matcha.parts   | available | $15.99    | —             | 86             | 39     | 6      | name.com  |
| justin.parts   | premium   | $82.50    | —             | 58             | 38     | 7      | name.com  |
| prompts.parts  | available | $15.99    | —             | 54             | 39     | 7      | name.com  |
| events.parts   | premium   | $82.50    | —             | 68             | 37     | 6      | name.com  |
| spectra.parts  | available | $15.99    | —             | 62             | 34     | 7      | name.com  |
| partners.parts | premium   | $82.50    | —             | 61             | 32     | 8      | name.com  |
| payments.parts | available | $15.99    | —             | 58             | 33     | 8      | name.com  |
| William.parts  | premium   | $138.60   | $138.60       | 74             | 31     | 7      | namecheap |
| teams.parts    | available | $15.99    | —             | 62             | 32     | 5      | name.com  |
| pages.parts    | premium   | $82.50    | —             | 52             | 28     | 5      | name.com  |
| trends.parts   | available | $15.99    | —             | 60             | 32     | 6      | name.com  |
| tips.parts     | premium   | $123.75   | —             | 80             | 26     | 4      | name.com  |
| maps.parts     | available | $15.99    | —             | 56             | 31     | 4      | name.com  |
| toys.parts     | premium   | $118.80   | $118.80       | 60             | 24     | 4      | namesilo  |
| rewards.parts  | available | $15.99    | —             | 62             | 30     | 7      | name.com  |
| girls.parts    | premium   | $123.75   | —             | 83             | 23     | 5      | name.com  |
| spaces.parts   | available | $15.99    | —             | 54             | 30     | 6      | name.com  |
| guns.parts     | premium   | $82.50    | —             | 68             | 22     | 4      | name.com  |
| heroes.parts   | available | $15.99    | —             | 68             | 29     | 6      | name.com  |
| flights.parts  | premium   | $78.54    | $78.54        | 61             | 22     | 7      | namesilo  |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                                   |
| ----------------------- | ------------------------------------------------ |
| 1,000-row public sample | 11,775 live domains                              |
| Static CSV / JSON       | live search and daily refresh                    |
| Basic exported fields   | deeper price, demand, risk, and workflow context |
| No persistence          | Radar, saved search, and alerts                  |
| No founder workflow     | Project, shortlist, and next-step workflow       |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/parts?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_parts_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/parts?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_parts_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_parts_oneword_domains&utm_content=related_pricing)

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

This repository follows the exact public search represented by the canonical page above.

- This repository is a public extract, not the full live catalog.
- Counts, prices, and statuses can change over time.
- Scores are decision-support signals, not guarantees of resale value.
- Trademark, SEO, and risk signals should be treated as screening inputs, not legal or specialist advice.
- Unique Domains contains deeper filters, monitoring, and decision workflows than this public extract.

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .PARTS One-Word Domains*. Version 2026-04-26. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .PARTS page](https://unique.domains/domains/tld/parts?utm_source=github&utm_medium=referral&utm_campaign=repo_parts_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_parts_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_parts_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_parts_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
