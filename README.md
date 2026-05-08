# Available .CAMP One-Word Domains (11,993)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-11%2C993%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .camp one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **11,993 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 11,993 domains · **Median ask:** $20.45 · **High-demand under $2,500:** 0

**Last updated:** 2026-05-08  
**Canonical page:** `https://unique.domains/domains/tld/camp`  
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/camp?utm_source=github&utm_medium=referral&utm_campaign=repo_camp_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./camp.csv">CSV</a> / <a href="./camp.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_camp_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_camp_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .CAMP search](https://unique.domains/domains/tld/camp?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_camp_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .CAMP search](https://unique.domains/domains/tld/camp?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_camp_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_camp_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .CAMP one-word domain catalog.

### Files

- `camp.csv` — public CSV extract (1,000 rows)
- `camp.json` — public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/camp-oneword-domains/main/camp.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain           | status    | ask_price | renewal_price | attractiveness | demand | length | registrar           |
| ---------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | ------------------- |
| whynot.camp      | available | $11.99    | —             | 74             | 39     | 7      | name.com            |
| web.camp         | resell    | —         | —             | 72             | 62     | 3      | Porkbun LLC         |
| jobs.camp        | premium   | $500      | —             | 79             | 42     | 4      | name.com            |
| stories.camp     | available | $11.99    | —             | 58             | 36     | 7      | name.com            |
| homes.camp       | resell    | —         | —             | 86             | 34     | 5      | united-domains GmbH |
| events.camp      | premium   | $500      | —             | 68             | 37     | 6      | name.com            |
| etc.camp         | available | $11.99    | —             | 58             | 34     | 3      | name.com            |
| guns.camp        | resell    | —         | —             | 68             | 22     | 4      | Porkbun LLC         |
| sites.camp       | premium   | $500      | —             | 53             | 26     | 5      | name.com            |
| payments.camp    | available | $11.99    | —             | 58             | 33     | 8      | name.com            |
| trailers.camp    | premium   | $242      | $242          | 54             | 15     | 8      | namesilo            |
| color.camp       | available | $11.99    | —             | 80             | 32     | 5      | name.com            |
| motorsports.camp | premium   | $250      | —             | 74             | 13     | 11     | name.com            |
| teams.camp       | available | $11.99    | —             | 62             | 32     | 5      | name.com            |
| William.camp     | available | $78.98    | —             | 74             | 31     | 7      | namecheap           |
| videos.camp      | available | $11.99    | —             | 52             | 30     | 6      | name.com            |
| cams.camp        | available | $11.99    | —             | 52             | 29     | 4      | name.com            |
| gems.camp        | available | $11.99    | —             | 70             | 28     | 4      | name.com            |
| forms.camp       | available | $11.99    | —             | 54             | 28     | 5      | name.com            |
| gods.camp        | available | $11.99    | —             | 72             | 27     | 4      | name.com            |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 11,993 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 0 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/camp?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_camp_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/camp?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_camp_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_camp_oneword_domains&utm_content=related_pricing)

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

These domains are all one-word names in the .camp TLD. The set mixes short, flexible terms such as yet.camp, bow.camp, and built.camp with more descriptive options like corporate.camp, vegetable.camp, and defence.camp. For founders, the main question is whether the word is memorable, easy to explain, and specific enough to justify using .camp instead of a more familiar extension. For investors, the key test is narrower: whether the word has enough commercial clarity or resale relevance in this TLD to support the ask. With a median ask of 20.45, the edge usually comes from picking cleaner words, stronger intent, and lower regret names rather than chasing volume.

- Short words like yet.camp are easier to recall and say
- Descriptive terms can signal niche use but narrow buyer fit
- Check whether the word feels natural with the .camp ending
- Avoid names with obvious trademark or ambiguity concerns

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .CAMP One-Word Domains*. Version 2026-05-08. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .CAMP page](https://unique.domains/domains/tld/camp?utm_source=github&utm_medium=referral&utm_campaign=repo_camp_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_camp_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_camp_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_camp_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
