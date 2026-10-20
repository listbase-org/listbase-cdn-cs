# Zdraví (Health)

4 datasets — 3,762 records

> Browse at [listbase.org/cs/health/](https://listbase.org/cs/health/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Lékárny](cs-lekarny.json) | 2,417 | 239 KB | [CSV](cs-lekarny_CS.csv) | [Excel](cs-lekarny_CS.xlsx) | [View](https://listbase.org/cs/health/cs-lekarny/) |
| [Sociální zařízení](cs-socialni-zarizeni.json) | 591 | 67 KB | [CSV](cs-socialni-zarizeni_CS.csv) | [Excel](cs-socialni-zarizeni_CS.xlsx) | [View](https://listbase.org/cs/health/cs-socialni-zarizeni/) |
| [Optiky](cs-optiky.json) | 493 | 50 KB | [CSV](cs-optiky_CS.csv) | [Excel](cs-optiky_CS.xlsx) | [View](https://listbase.org/cs/health/cs-optiky/) |
| [Nemocnice](cs-nemocnice.json) | 261 | 31 KB | [CSV](cs-nemocnice_CS.csv) | [Excel](cs-nemocnice_CS.xlsx) | [View](https://listbase.org/cs/health/cs-nemocnice/) |

## Quick Start

```bash
# List all health datasets
curl https://cdn.cs.listbase.org/index.json | jq '.datasets[] | select(.category=="health") | .id'

# Fetch a dataset
curl https://cdn.cs.listbase.org/health/cs-lekarny.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/cs/health/)
