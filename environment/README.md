# Životní prostředí (Environment)

19 datasets — 33,869 records

> Browse at [listbase.org/cs/environment/](https://listbase.org/cs/environment/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Vrcholy](cs-vrcholy.json) | 12,705 | 1238 KB | [CSV](cs-vrcholy_CS.csv) | [Excel](cs-vrcholy_CS.xlsx) | [View](https://listbase.org/cs/environment/cs-vrcholy/) |
| [Vodní plochy](cs-vodni-plochy.json) | 12,305 | 1234 KB | [CSV](cs-vodni-plochy_CS.csv) | [Excel](cs-vodni-plochy_CS.xlsx) | [View](https://listbase.org/cs/environment/cs-vodni-plochy/) |
| [Prameny](cs-prameny.json) | 2,469 | 253 KB | [CSV](cs-prameny_CS.csv) | [Excel](cs-prameny_CS.xlsx) | [View](https://listbase.org/cs/environment/cs-prameny/) |
| [Významné stromy](cs-pamatne-stromy.json) | 1,720 | 177 KB | [CSV](cs-pamatne-stromy_CS.csv) | [Excel](cs-pamatne-stromy_CS.xlsx) | [View](https://listbase.org/cs/environment/cs-pamatne-stromy/) |
| [Skalní stěny](cs-skalni-steny.json) | 1,057 | 107 KB | [CSV](cs-skalni-steny_CS.csv) | [Excel](cs-skalni-steny_CS.xlsx) | [View](https://listbase.org/cs/environment/cs-skalni-steny/) |
| [Přírodní rezervace a národní přírodní rezervace v Česku](cs-prirodni-rezervace.json) | 953 | 2244 KB | [CSV](cs-prirodni-rezervace_CS.csv) | [Excel](cs-prirodni-rezervace_CS.xlsx) | [View](https://listbase.org/cs/environment/cs-prirodni-rezervace/) |
| [Elektrárny v Česku](cs-elektrarny.json) | 671 | 346 KB | [CSV](cs-elektrarny_CS.csv) | [Excel](cs-elektrarny_CS.xlsx) | [View](https://listbase.org/cs/environment/cs-elektrarny/) |
| [Sluneční elektrárny v Česku](cs-slunecni-elektrarny.json) | 598 | 305 KB | [CSV](cs-slunecni-elektrarny_CS.csv) | [Excel](cs-slunecni-elektrarny_CS.xlsx) | [View](https://listbase.org/cs/environment/cs-slunecni-elektrarny/) |
| [Jeskyně](cs-jeskyne.json) | 480 | 50 KB | [CSV](cs-jeskyne_CS.csv) | [Excel](cs-jeskyne_CS.xlsx) | [View](https://listbase.org/cs/environment/cs-jeskyne/) |
| [Údolí](cs-udoli.json) | 368 | 38 KB | [CSV](cs-udoli_CS.csv) | [Excel](cs-udoli_CS.xlsx) | [View](https://listbase.org/cs/environment/cs-udoli/) |
| [Balvany](cs-balvany.json) | 251 | 26 KB | [CSV](cs-balvany_CS.csv) | [Excel](cs-balvany_CS.xlsx) | [View](https://listbase.org/cs/environment/cs-balvany/) |
| [Mokřady](cs-mokrady.json) | 215 | 23 KB | [CSV](cs-mokrady_CS.csv) | [Excel](cs-mokrady_CS.xlsx) | [View](https://listbase.org/cs/environment/cs-mokrady/) |
| [Hnědouhelné elektrárny v Česku](cs-hnedouhelne-elektrarny.json) | 25 | 19 KB | [CSV](cs-hnedouhelne-elektrarny_CS.csv) | [Excel](cs-hnedouhelne-elektrarny_CS.xlsx) | [View](https://listbase.org/cs/environment/cs-hnedouhelne-elektrarny/) |
| [Měrné jednotky: energy (14)](cs-jednotky-energy.json) | 14 | 5 KB | [CSV](cs-jednotky-energy_CS.csv) | [Excel](cs-jednotky-energy_CS.xlsx) | [View](https://listbase.org/cs/environment/cs-jednotky-energy/) |
| [Černouhelné elektrárny v Česku](cs-cernouhelne-elektrarny.json) | 11 | 9 KB | [CSV](cs-cernouhelne-elektrarny_CS.csv) | [Excel](cs-cernouhelne-elektrarny_CS.xlsx) | [View](https://listbase.org/cs/environment/cs-cernouhelne-elektrarny/) |
| [Vodní elektrárny v Česku](cs-vodni-elektrarny.json) | 9 | 8 KB | [CSV](cs-vodni-elektrarny_CS.csv) | [Excel](cs-vodni-elektrarny_CS.xlsx) | [View](https://listbase.org/cs/environment/cs-vodni-elektrarny/) |
| [Větrné elektrárny v Česku](cs-vetrne-elektrarny.json) | 7 | 7 KB | [CSV](cs-vetrne-elektrarny_CS.csv) | [Excel](cs-vetrne-elektrarny_CS.xlsx) | [View](https://listbase.org/cs/environment/cs-vetrne-elektrarny/) |
| [Jaderné elektrárny v Česku](cs-jaderne-elektrarny.json) | 6 | 5 KB | [CSV](cs-jaderne-elektrarny_CS.csv) | [Excel](cs-jaderne-elektrarny_CS.xlsx) | [View](https://listbase.org/cs/environment/cs-jaderne-elektrarny/) |
| [Měrné jednotky: temperature (5)](cs-jednotky-temperature.json) | 5 | 3 KB | [CSV](cs-jednotky-temperature_CS.csv) | [Excel](cs-jednotky-temperature_CS.xlsx) | [View](https://listbase.org/cs/environment/cs-jednotky-temperature/) |

## Quick Start

```bash
# List all environment datasets
curl https://cdn.cs.listbase.org/index.json | jq '.datasets[] | select(.category=="environment") | .id'

# Fetch a dataset
curl https://cdn.cs.listbase.org/environment/cs-vrcholy.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/cs/environment/)
