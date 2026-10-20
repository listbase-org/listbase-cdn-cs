# Kultura a Náboženství (Culture & Religion)

10 datasets — 5,538 records

> Browse at [listbase.org/cs/culture/](https://listbase.org/cs/culture/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Kostely v Česku (Churches in Czechia)](cs-kostely.json) | 3,139 | 23691 KB | [CSV](cs-kostely_CS.csv) | [Excel](cs-kostely_CS.xlsx) | [View](https://listbase.org/cs/culture/cs-kostely/) |
| [Hrady a tvrze v České republice (Castles and fortresses in the Czech Republic)](cs-hrady.json) | 851 | 614 KB | [CSV](cs-hrady_CS.csv) | [Excel](cs-hrady_CS.xlsx) | [View](https://listbase.org/cs/culture/cs-hrady/) |
| [Divadla v Česku (Theatres in the Czech Republic)](cs-divadla.json) | 546 | 626 KB | [CSV](cs-divadla_CS.csv) | [Excel](cs-divadla_CS.xlsx) | [View](https://listbase.org/cs/culture/cs-divadla/) |
| [Czech monasteries (kláštery v Česku)](cs-klastery.json) | 300 | 509 KB | [CSV](cs-klastery_CS.csv) | [Excel](cs-klastery_CS.xlsx) | [View](https://listbase.org/cs/culture/cs-klastery/) |
| [Zámky v Česku (Chateaux in Czech Republic)](cs-zamky.json) | 209 | 1405 KB | [CSV](cs-zamky_CS.csv) | [Excel](cs-zamky_CS.xlsx) | [View](https://listbase.org/cs/culture/cs-zamky/) |
| [Galerie](cs-galerie.json) | 208 | 23 KB | [CSV](cs-galerie_CS.csv) | [Excel](cs-galerie_CS.xlsx) | [View](https://listbase.org/cs/culture/cs-galerie/) |
| [Umělecká centra](cs-umelecka-centra.json) | 143 | 16 KB | [CSV](cs-umelecka-centra_CS.csv) | [Excel](cs-umelecka-centra_CS.xlsx) | [View](https://listbase.org/cs/culture/cs-umelecka-centra/) |
| [Zahrady v Česku (Historical gardens of Czechia)](cs-zahrady.json) | 113 | 164 KB | [CSV](cs-zahrady_CS.csv) | [Excel](cs-zahrady_CS.xlsx) | [View](https://listbase.org/cs/culture/cs-zahrady/) |
| [Czech cathedrals (katedrály a konkatedrály v Česku)](cs-katedraly.json) | 15 | 161 KB | [CSV](cs-katedraly_CS.csv) | [Excel](cs-katedraly_CS.xlsx) | [View](https://listbase.org/cs/culture/cs-katedraly/) |
| [Světové dědictví UNESCO v Česku](cs-svetove-dedictvi-unesco.json) | 14 | 14 KB | [CSV](cs-svetove-dedictvi-unesco_CS.csv) | [Excel](cs-svetove-dedictvi-unesco_CS.xlsx) | [View](https://listbase.org/cs/culture/cs-svetove-dedictvi-unesco/) |

## Quick Start

```bash
# List all culture & religion datasets
curl https://cdn.cs.listbase.org/index.json | jq '.datasets[] | select(.category=="culture") | .id'

# Fetch a dataset
curl https://cdn.cs.listbase.org/culture/cs-kostely.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/cs/culture/)
