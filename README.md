# Available .HOST One-Word Domains (22,487)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-22%2C487%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .host one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **22,487 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 22,487 domains · **Median ask:** $238.02 · **High-demand under $2,500:** 64

**Last updated:** 2026-09-26
**Canonical page:** `https://unique.domains/domains/tld/host`
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/host?utm_source=github&utm_medium=referral&utm_campaign=repo_host_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./host.csv">CSV</a> / <a href="./host.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_host_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_host_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .HOST search](https://unique.domains/domains/tld/host?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_host_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .HOST search](https://unique.domains/domains/tld/host?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_host_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_host_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .HOST one-word domain catalog.

### Files

- `host.csv`, public CSV extract (1,000 rows)
- `host.json`, public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md`, field definitions for the exported files
- `METHODOLOGY.md`, scope, refresh policy, and caveats
- `CHANGELOG.md`, latest snapshot metadata
- `CITATION.cff`, machine-readable dataset citation metadata
- `LICENSE`, terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/host-oneword-domains/main/host.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain       | status    | ask_price | renewal_price | attractiveness | demand | length | registrar          |
| ------------ | --------- | --------- | ------------- | -------------- | ------ | ------ | ------------------ |
| afar.host    | available | $4.99     | $109.99       | medium         | low    | 4      | namesilo           |
| managed.host | resell    | —         | —             | high           | low    | 7      | Namify Domains Inc |
| aga.host     | premium   | $325      | $650          | high           | low    | 3      | namecheap          |
| agee.host    | available | $4.99     | $109.99       | medium         | low    | 4      | namesilo           |
| shirley.host | resell    | —         | —             | high           | low    | 7      | —                  |
| ago.host     | premium   | $640      | $640          | high           | low    | 3      | namesilo           |
| amyl.host    | available | $4.99     | $109.99       | medium         | low    | 4      | namesilo           |
| amc.host     | premium   | $650      | $1,300        | high           | medium | 3      | namecheap          |
| awny.host    | available | $4.99     | $109.99       | medium         | low    | 4      | namesilo           |
| ana.host     | premium   | $312.50   | —             | high           | low    | 3      | name.com           |
| babu.host    | available | $9.99     | $47.48        | high           | low    | 4      | namecheap          |
| asl.host     | premium   | $325      | $650          | high           | low    | 3      | namecheap          |
| bmus.host    | available | $4.99     | $109.99       | medium         | low    | 4      | namesilo           |
| bai.host     | premium   | $325      | $650          | high           | low    | 3      | namecheap          |
| clef.host    | available | $4.99     | $109.99       | high           | low    | 4      | namesilo           |
| beg.host     | premium   | $312.50   | —             | high           | low    | 3      | name.com           |
| daly.host    | available | $4.99     | $109.99       | high           | low    | 4      | namesilo           |
| bjp.host     | premium   | $312.50   | —             | high           | low    | 3      | name.com           |
| damp.host    | available | $134.99   | $134.99       | medium         | low    | 4      | name.com           |
| bop.host     | premium   | $640      | $640          | high           | low    | 3      | namesilo           |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 22,487 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 64 high-demand names under $2,500          |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/host?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_host_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/host?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_host_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_host_oneword_domains&utm_content=related_pricing)

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
- `status_verified_at`, When status was last established against the registry. Null means never checked.

See [DATA_DICTIONARY.md](./DATA_DICTIONARY.md) for full definitions and types.

## ⚠️ Methodology and caveats

This list of one-word .host domain names spans a wide range of themes, from short action words like 'getup.host' to compound brandables like 'gettogether.host'. With a median asking price near $271 across 12,229 names, this set gives founders and investors a broad view of pricing and naming patterns within the .host extension. Because .host signals hosting, infrastructure, and tech-adjacent projects, many of these names read as ready-to-use brand candidates rather than generic filler.

- 12,229 one-word .host domain names in this set
- Median asking price near $271 per domain
- Mix of short, action, and compound brandable names
- Updated daily to reflect current listings and pricing

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The snapshot date above is when this file was written, not when each row was checked. Read `status_verified_at` for that: a name whose status was last established months ago is exported with its real date rather than the snapshot's.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .HOST One-Word Domains*. Version 2026-09-26. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .HOST page](https://unique.domains/domains/tld/host?utm_source=github&utm_medium=referral&utm_campaign=repo_host_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_host_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_host_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_host_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `kai@unique.domains`
