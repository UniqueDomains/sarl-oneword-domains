# Available .SARL One-Word Domains (12,854)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-12%2C854%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .sarl one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **12,854 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 12,854 domains · **Median ask:** $9.63 · **High-demand under $2,500:** 0

**Last updated:** 2026-06-04  
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

- `sarl.csv` — public CSV extract (1,000 rows)
- `sarl.json` — public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/sarl-oneword-domains/main/sarl.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain         | status    | ask_price | renewal_price | attractiveness | demand | length | registrar |
| -------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | --------- |
| easy.sarl      | available | $8.98     | —             | 128            | 67     | 4      | namecheap |
| bot.sarl       | premium   | $500      | —             | 98             | 58     | 3      | name.com  |
| macedonia.sarl | available | $8.98     | —             | 70             | 52     | 9      | namecheap |
| industry.sarl  | premium   | $38.94    | $38.94        | 68             | 58     | 8      | namesilo  |
| startup.sarl   | available | $6.99     | $6.99         | 82             | 49     | 7      | namesilo  |
| ink.sarl       | premium   | $38.94    | $38.94        | 94             | 51     | 3      | namesilo  |
| stellar.sarl   | available | $8.98     | —             | 78             | 49     | 7      | namecheap |
| create.sarl    | premium   | $38.94    | $38.94        | 107            | 50     | 6      | namesilo  |
| platform.sarl  | available | $6.99     | $6.99         | 92             | 48     | 8      | namesilo  |
| ben.sarl       | premium   | $38.94    | $38.94        | 84             | 49     | 3      | namesilo  |
| happy.sarl     | available | $6.99     | $6.99         | 78             | 48     | 5      | namesilo  |
| bio.sarl       | premium   | $78.54    | $78.54        | 78             | 44     | 3      | namesilo  |
| marketing.sarl | available | $8.98     | —             | 74             | 48     | 9      | namecheap |
| photo.sarl     | premium   | $38.94    | $38.94        | 92             | 42     | 5      | namesilo  |
| sports.sarl    | available | $6.99     | $6.99         | 110            | 47     | 6      | namesilo  |
| key.sarl       | premium   | $38.94    | $38.94        | 80             | 42     | 3      | namesilo  |
| found.sarl     | available | $6.99     | $6.99         | 92             | 47     | 5      | namesilo  |
| pocket.sarl    | premium   | $38.94    | $38.94        | 72             | 42     | 6      | namesilo  |
| based.sarl     | available | $6.99     | $6.99         | 96             | 46     | 5      | namesilo  |
| org.sarl       | premium   | $500      | —             | 54             | 42     | 3      | name.com  |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 12,854 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 0 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/sarl?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_sarl_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/sarl?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_sarl_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_sarl_oneword_domains&utm_content=related_pricing)

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

This set is defined by a single constraint: the domains use the .sarl extension and the name is one word. That creates a wide mix of dictionary terms, descriptive words, personal names, and higher-risk strings. Examples here include cord.sarl, principal.sarl, background.sarl, compelling.sarl, affable.sarl, ana.sarl, and interim.sarl. When comparing these domains, start with linguistic clarity and commercial fit. Short, clean words are usually easier to remember, while longer or abstract words need a stronger reason to exist. Price discipline matters too: the median ask is 9.82, so unusually expensive names should justify that premium with exceptional clarity or stronger relevance.

- Favor clear, memorable words over vague or awkward terms
- Check trademark exposure on names like reebok.sarl
- Use the 9.82 median ask as a price discipline anchor
- Prefer words that read naturally with the .sarl ending

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .SARL One-Word Domains*. Version 2026-06-04. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .SARL page](https://unique.domains/domains/tld/sarl?utm_source=github&utm_medium=referral&utm_campaign=repo_sarl_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_sarl_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_sarl_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_sarl_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
