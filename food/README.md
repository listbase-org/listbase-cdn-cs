# Jídlo a Výživa (Food & Nutrition)

10 datasets — 25,670 records

> Browse at [listbase.org/cs/food/](https://listbase.org/cs/food/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Restaurace](cs-restaurace.json) | 11,766 | 1185 KB | [CSV](cs-restaurace_CS.csv) | [Excel](cs-restaurace_CS.xlsx) | [View](https://listbase.org/cs/food/cs-restaurace/) |
| [Hospody](cs-hospody.json) | 4,182 | 420 KB | [CSV](cs-hospody_CS.csv) | [Excel](cs-hospody_CS.xlsx) | [View](https://listbase.org/cs/food/cs-hospody/) |
| [Kavárny](cs-kavarny.json) | 3,728 | 372 KB | [CSV](cs-kavarny_CS.csv) | [Excel](cs-kavarny_CS.xlsx) | [View](https://listbase.org/cs/food/cs-kavarny/) |
| [Rychlé občerstvení](cs-rychle-obcerstveni.json) | 3,173 | 317 KB | [CSV](cs-rychle-obcerstveni_CS.csv) | [Excel](cs-rychle-obcerstveni_CS.xlsx) | [View](https://listbase.org/cs/food/cs-rychle-obcerstveni/) |
| [Bary](cs-bary.json) | 1,577 | 157 KB | [CSV](cs-bary_CS.csv) | [Excel](cs-bary_CS.xlsx) | [View](https://listbase.org/cs/food/cs-bary/) |
| [Vinotéky](cs-vinoteky.json) | 417 | 44 KB | [CSV](cs-vinoteky_CS.csv) | [Excel](cs-vinoteky_CS.xlsx) | [View](https://listbase.org/cs/food/cs-vinoteky/) |
| [Zmrzlinárny](cs-zmrzlinarny.json) | 320 | 34 KB | [CSV](cs-zmrzlinarny_CS.csv) | [Excel](cs-zmrzlinarny_CS.xlsx) | [View](https://listbase.org/cs/food/cs-zmrzlinarny/) |
| [Pivní zahrady](cs-pivni-zahrady.json) | 243 | 26 KB | [CSV](cs-pivni-zahrady_CS.csv) | [Excel](cs-pivni-zahrady_CS.xlsx) | [View](https://listbase.org/cs/food/cs-pivni-zahrady/) |
| [Pivovary v Česku — Czech breweries](cs-pivovary.json) | 185 | 1017 KB | [CSV](cs-pivovary_CS.csv) | [Excel](cs-pivovary_CS.xlsx) | [View](https://listbase.org/cs/food/cs-pivovary/) |
| [Michelinské restaurace v Česku](cs-michelin-restaurace.json) | 79 | 91 KB | [CSV](cs-michelin-restaurace_CS.csv) | [Excel](cs-michelin-restaurace_CS.xlsx) | [View](https://listbase.org/cs/food/cs-michelin-restaurace/) |

## Quick Start

```bash
# List all food & nutrition datasets
curl https://cdn.cs.listbase.org/index.json | jq '.datasets[] | select(.category=="food") | .id'

# Fetch a dataset
curl https://cdn.cs.listbase.org/food/cs-restaurace.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/cs/food/)
