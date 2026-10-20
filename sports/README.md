# Sport (Sports)

1 datasets — 541 records

> Browse at [listbase.org/cs/sports/](https://listbase.org/cs/sports/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Sportovní prodejny](cs-sportovni-prodejny.json) | 541 | 54 KB | [CSV](cs-sportovni-prodejny_CS.csv) | [Excel](cs-sportovni-prodejny_CS.xlsx) | [View](https://listbase.org/cs/sports/cs-sportovni-prodejny/) |

## Quick Start

```bash
# List all sports datasets
curl https://cdn.cs.listbase.org/index.json | jq '.datasets[] | select(.category=="sports") | .id'

# Fetch a dataset
curl https://cdn.cs.listbase.org/sports/cs-sportovni-prodejny.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/cs/sports/)
