# Vzdělávání (Education)

3 datasets — 6,105 records

> Browse at [listbase.org/cs/education/](https://listbase.org/cs/education/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Školy](cs-skoly.json) | 3,779 | 427 KB | [CSV](cs-skoly_CS.csv) | [Excel](cs-skoly_CS.xlsx) | [View](https://listbase.org/cs/education/cs-skoly/) |
| [Mateřské školy](cs-materske-skoly.json) | 2,296 | 247 KB | [CSV](cs-materske-skoly_CS.csv) | [Excel](cs-materske-skoly_CS.xlsx) | [View](https://listbase.org/cs/education/cs-materske-skoly/) |
| [Česko — Univerzity](cs-univerzity.json) | 30 | 11 KB | [CSV](cs-univerzity_CS.csv) | [Excel](cs-univerzity_CS.xlsx) | [View](https://listbase.org/cs/education/cs-univerzity/) |

## Quick Start

```bash
# List all education datasets
curl https://cdn.cs.listbase.org/index.json | jq '.datasets[] | select(.category=="education") | .id'

# Fetch a dataset
curl https://cdn.cs.listbase.org/education/cs-skoly.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/cs/education/)
