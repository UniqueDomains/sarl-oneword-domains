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

**Public extract:** 1,000 rows · **Live catalog:** 12,854 domains · **Median ask:** $9.82 · **High-demand under $2,500:** 0

**Last updated:** 2026-05-11  
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

| domain            | status    | ask_price | renewal_price | attractiveness | demand | length | registrar |
| ----------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | --------- |
| Books.sarl        | available | $8.98     | —             | 52             | 49     | 5      | namecheap |
| agents.sarl       | premium   | $82.50    | —             | 56             | 50     | 6      | name.com  |
| Ryan.sarl         | available | $8.98     | —             | 60             | 44     | 4      | namecheap |
| rewards.sarl      | premium   | $38.94    | $38.94        | 62             | 30     | 7      | namesilo  |
| jobs.sarl         | available | $8.98     | —             | 79             | 42     | 4      | namecheap |
| bills.sarl        | premium   | $82.50    | —             | 54             | 19     | 5      | name.com  |
| whynot.sarl       | available | $8.98     | —             | 74             | 39     | 7      | namecheap |
| links.sarl        | premium   | —         | —             | 70             | 38     | 5      | —         |
| events.sarl       | available | $8.98     | —             | 68             | 37     | 6      | namecheap |
| William.sarl      | available | $8.98     | —             | 74             | 31     | 7      | namecheap |
| maps.sarl         | available | $8.98     | —             | 56             | 31     | 4      | namecheap |
| inspiration.sarl  | available | $8.98     | —             | 88             | 30     | 11     | namecheap |
| videos.sarl       | available | $8.98     | —             | 52             | 30     | 6      | namecheap |
| quotes.sarl       | available | $8.98     | —             | 58             | 29     | 6      | namecheap |
| blocks.sarl       | available | $8.98     | —             | 53             | 29     | 6      | namecheap |
| commonground.sarl | available | $8.98     | —             | 74             | 28     | 13     | namecheap |
| brands.sarl       | available | $8.98     | —             | 62             | 28     | 6      | namecheap |
| gods.sarl         | available | $8.98     | —             | 72             | 27     | 4      | namecheap |
| bees.sarl         | available | $8.98     | —             | 54             | 27     | 4      | namecheap |
| trades.sarl       | available | $6.99     | $6.99         | 71             | 26     | 6      | namesilo  |

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

> Unique Domains. *Available .SARL One-Word Domains*. Version 2026-05-11. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .SARL page](https://unique.domains/domains/tld/sarl?utm_source=github&utm_medium=referral&utm_campaign=repo_sarl_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_sarl_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_sarl_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_sarl_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
