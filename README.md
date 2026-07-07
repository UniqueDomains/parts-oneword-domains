# Available .PARTS One-Word Domains (12,254)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-12%2C254%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .parts one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **12,254 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 12,254 domains · **Median ask:** $23.21 · **High-demand under $2,500:** 0

**Last updated:** 2026-07-07
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

- `parts.csv`, public CSV extract (1,000 rows)
- `parts.json`, public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md`, field definitions for the exported files
- `METHODOLOGY.md`, scope, refresh policy, and caveats
- `CHANGELOG.md`, latest snapshot metadata
- `CITATION.cff`, machine-readable dataset citation metadata
- `LICENSE`, terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/parts-oneword-domains/main/parts.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain           | status    | ask_price | renewal_price | attractiveness | demand | length | registrar                                   |
| ---------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | ------------------------------------------- |
| out.parts        | premium   | $78.54    | $78.54        | high           | low    | 3      | namesilo                                    |
| off.parts        | premium   | $242      | $242          | high           | low    | 3      | namesilo                                    |
| special.parts    | premium   | $123.75   | —             | high           | low    | 7      | name.com                                    |
| smooth.parts     | available | $15.99    | —             | high           | low    | 6      | name.com                                    |
| present.parts    | available | $15.99    | —             | high           | low    | 7      | name.com                                    |
| shh.parts        | available | $15.99    | —             | medium         | low    | 3      | name.com                                    |
| poker.parts      | resell    | —         | —             | high           | medium | 5      | Mesh Digital Limited                        |
| aaa.parts        | premium   | $260      | $260          | high           | medium | 3      | namecheap                                   |
| atop.parts       | available | $15.99    | —             | medium         | low    | 4      | name.com                                    |
| smart.parts      | resell    | —         | —             | high           | medium | 5      | Sav.com, LLC                                |
| add.parts        | premium   | $78.54    | $78.54        | high           | low    | 3      | namesilo                                    |
| axis.parts       | available | $15.99    | —             | medium         | medium | 4      | name.com                                    |
| spare.parts      | resell    | —         | —             | medium         | low    | 5      | GoDaddy Online Services Cayman Islands Ltd. |
| ADS.parts        | premium   | $78.54    | $78.54        | high           | medium | 3      | namesilo                                    |
| Bets.parts       | available | $15.99    | —             | high           | low    | 4      | name.com                                    |
| premium.parts    | resell    | —         | —             | high           | low    | 7      | united-domains GmbH                         |
| are.parts        | premium   | $38.94    | $38.94        | high           | low    | 3      | namesilo                                    |
| blob.parts       | available | $15.99    | —             | medium         | low    | 4      | name.com                                    |
| compatible.parts | resell    | —         | —             | high           | low    | 10     | GoDaddy.com, LLC                            |
| btw.parts        | premium   | $38.94    | $38.94        | high           | low    | 3      | namesilo                                    |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 12,254 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 0 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/parts?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_parts_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/parts?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_parts_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_parts_oneword_domains&utm_content=related_pricing)

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

This selection covers one-word .parts domain names built from everyday English vocabulary, including out.parts, half.parts, christmas.parts, and okay.parts. With a median ask near $23, most of these domains are affordable to acquire outright, offering a straightforward starting point for evaluating short, memorable names. When comparing these domains, look at spelling simplicity, trademark exposure, and how well each word carries meaning outside the .parts context.

- 12,254 one-word .parts domains built from common English words
- Median ask near $23 keeps most names easy to acquire outright
- Examples: out.parts, half.parts, okay.parts, and christmas.parts
- Short, ownable words ready for branding or portfolio building

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .PARTS One-Word Domains*. Version 2026-07-07. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .PARTS page](https://unique.domains/domains/tld/parts?utm_source=github&utm_medium=referral&utm_campaign=repo_parts_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_parts_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_parts_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_parts_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
