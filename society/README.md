# Společnost (Society)

1 datasets — 790 records

> Browse at [listbase.org/cs/society/](https://listbase.org/cs/society/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [České policejní stanice](cs-policejni-stanice.json) | 790 | 92 KB | [CSV](cs-policejni-stanice_CS.csv) | [Excel](cs-policejni-stanice_CS.xlsx) | [View](https://listbase.org/cs/society/cs-policejni-stanice/) |

## Quick Start

```bash
# List all society datasets
curl https://cdn.cs.listbase.org/index.json | jq '.datasets[] | select(.category=="society") | .id'

# Fetch a dataset
curl https://cdn.cs.listbase.org/society/cs-policejni-stanice.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/cs/society/)
