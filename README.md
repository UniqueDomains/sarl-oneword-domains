# Available .SARL One-Word Domains (17,811)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-17%2C811%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .sarl one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **17,811 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 17,811 domains · **Median ask:** $8.98 · **High-demand under $2,500:** 3

**Last updated:** 2026-08-20
**Canonical page:** `https://unique.domains/domains/tld/sarl`
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/sarl?utm_source=github&utm_medium=referral&utm_campaign=repo_sarl_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./sarl.csv">CSV</a> / <a href="./sarl.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_sarl_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_sarl_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .SARL search](https://unique.domains/domains/tld/sarl?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_sarl_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .SARL search](https://unique.domains/domains/tld/sarl?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_sarl_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_sarl_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .SARL one-word domain catalog.

### Files

- `sarl.csv`, public CSV extract (1,000 rows)
- `sarl.json`, public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md`, field definitions for the exported files
- `METHODOLOGY.md`, scope, refresh policy, and caveats
- `CHANGELOG.md`, latest snapshot metadata
- `CITATION.cff`, machine-readable dataset citation metadata
- `LICENSE`, terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/sarl-oneword-domains/main/sarl.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain     | status    | ask_price | renewal_price | attractiveness | demand | length | registrar |
| ---------- | --------- | --------- | ------------- | -------------- | ------ | ------ | --------- |
| hello.sarl | available | —         | —             | high           | low    | 5      | —         |
| easy.sarl  | available | $8.98     | —             | high           | medium | 4      | namecheap |
| aft.sarl   | available | $6.98     | $8.98         | low            | low    | 3      | namecheap |
| apt.sarl   | premium   | $41.25    | —             | high           | low    | 3      | name.com  |
| bce.sarl   | available | $6.99     | $6.99         | medium         | low    | 3      | namesilo  |
| ben.sarl   | premium   | $38.94    | $38.94        | high           | medium | 3      | namesilo  |
| dye.sarl   | available | $6.99     | $6.99         | medium         | low    | 3      | namesilo  |
| bio.sarl   | premium   | $78.54    | $78.54        | high           | medium | 3      | namesilo  |
| far.sarl   | available | $6.99     | $6.99         | high           | low    | 3      | namesilo  |
| bot.sarl   | premium   | $500      | —             | high           | medium | 3      | name.com  |
| Fla.sarl   | available | $6.99     | $6.99         | medium         | low    | 3      | namesilo  |
| cap.sarl   | premium   | $38.94    | $38.94        | high           | low    | 3      | namesilo  |
| fog.sarl   | available | $6.99     | $6.99         | high           | low    | 3      | namesilo  |
| ccc.sarl   | premium   | $38.94    | $38.94        | low            | medium | 3      | namesilo  |
| ilx.sarl   | available | $6.98     | $8.98         | low            | low    | 3      | namecheap |
| cut.sarl   | premium   | $82.50    | $82.50        | high           | low    | 3      | name.com  |
| los.sarl   | available | $8.98     | —             | high           | low    | 3      | namecheap |
| DJI.sarl   | premium   | $78.54    | $78.54        | high           | low    | 3      | namesilo  |
| lxi.sarl   | available | $6.98     | $8.98         | low            | low    | 3      | namecheap |
| fly.sarl   | premium   | $78.54    | $78.54        | high           | low    | 3      | namesilo  |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 17,811 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 3 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/sarl?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_sarl_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/sarl?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_sarl_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_sarl_oneword_domains&utm_content=related_pricing)

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

This is a curated set of 12,854 one-word .sarl domain names, spanning everyday English words and short phrases such as inspiration.sarl, headout.sarl, and homes.sarl. Because .sarl is a newer top-level domain tied to the French limited-liability company structure, pricing stays low: the median ask across this selection is about $9.61. That makes it possible to secure a clean, one-word address without competing for a premium legacy TLD. Updated daily, this list covers a wide range of tones, from action verbs like makeit.sarl and steerclear.sarl to descriptive nouns like destination.sarl and finals.sarl, giving investors and founders a broad pool to evaluate for cost, memorability, and long-term renewal value.

- 12,854 one-word .sarl domain names in this selection
- Median asking price around $9.61 — budget-friendly entry
- Themes range from travel and lifestyle to business terms
- Updated daily to reflect the current .sarl inventory

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .SARL One-Word Domains*. Version 2026-08-20. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .SARL page](https://unique.domains/domains/tld/sarl?utm_source=github&utm_medium=referral&utm_campaign=repo_sarl_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_sarl_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_sarl_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_sarl_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
