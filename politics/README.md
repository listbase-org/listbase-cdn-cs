# Politika (Politics)

3 datasets — 1,539 records

> Browse at [listbase.org/cs/politics/](https://listbase.org/cs/politics/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Kamerové body](cs-kamerove-body.json) | 1,043 | 114 KB | [CSV](cs-kamerove-body_CS.csv) | [Excel](cs-kamerove-body_CS.xlsx) | [View](https://listbase.org/cs/politics/cs-kamerove-body/) |
| [Vládní úřady](cs-vladni-urady.json) | 484 | 58 KB | [CSV](cs-vladni-urady_CS.csv) | [Excel](cs-vladni-urady_CS.xlsx) | [View](https://listbase.org/cs/politics/cs-vladni-urady/) |
| [Prezidenti České republiky a Československa](cs-prezidenti.json) | 12 | 11 KB | [CSV](cs-prezidenti_CS.csv) | [Excel](cs-prezidenti_CS.xlsx) | [View](https://listbase.org/cs/politics/cs-prezidenti/) |

## Quick Start

```bash
# List all politics datasets
curl https://cdn.cs.listbase.org/index.json | jq '.datasets[] | select(.category=="politics") | .id'

# Fetch a dataset
curl https://cdn.cs.listbase.org/politics/cs-kamerove-body.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/cs/politics/)
