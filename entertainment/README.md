# Zábava (Entertainment)

1 datasets — 392 records

> Browse at [listbase.org/cs/entertainment/](https://listbase.org/cs/entertainment/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Knihkupectví](cs-knihkupectvi.json) | 392 | 41 KB | [CSV](cs-knihkupectvi_CS.csv) | [Excel](cs-knihkupectvi_CS.xlsx) | [View](https://listbase.org/cs/entertainment/cs-knihkupectvi/) |

## Quick Start

```bash
# List all entertainment datasets
curl https://cdn.cs.listbase.org/index.json | jq '.datasets[] | select(.category=="entertainment") | .id'

# Fetch a dataset
curl https://cdn.cs.listbase.org/entertainment/cs-knihkupectvi.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/cs/entertainment/)
