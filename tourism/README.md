# Cestovní ruch (Tourism)

14 datasets — 72,456 records

> Browse at [listbase.org/cs/tourism/](https://listbase.org/cs/tourism/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Informační body](cs-informacni-body.json) | 54,270 | 5797 KB | [CSV](cs-informacni-body_CS.csv) | [Excel](cs-informacni-body_CS.xlsx) | [View](https://listbase.org/cs/tourism/cs-informacni-body/) |
| [Umělecká díla](cs-umelecka-dila.json) | 3,811 | 389 KB | [CSV](cs-umelecka-dila_CS.csv) | [Excel](cs-umelecka-dila_CS.xlsx) | [View](https://listbase.org/cs/tourism/cs-umelecka-dila/) |
| [Penziony](cs-penziony.json) | 3,370 | 345 KB | [CSV](cs-penziony_CS.csv) | [Excel](cs-penziony_CS.xlsx) | [View](https://listbase.org/cs/tourism/cs-penziony/) |
| [Hotely](cs-hotely.json) | 3,271 | 331 KB | [CSV](cs-hotely_CS.csv) | [Excel](cs-hotely_CS.xlsx) | [View](https://listbase.org/cs/tourism/cs-hotely/) |
| [Turistické atrakce](cs-turisticke-atrakce.json) | 2,666 | 279 KB | [CSV](cs-turisticke-atrakce_CS.csv) | [Excel](cs-turisticke-atrakce_CS.xlsx) | [View](https://listbase.org/cs/tourism/cs-turisticke-atrakce/) |
| [Muzea (OSM)](cs-osm-muzea.json) | 1,398 | 156 KB | [CSV](cs-osm-muzea_CS.csv) | [Excel](cs-osm-muzea_CS.xlsx) | [View](https://listbase.org/cs/tourism/cs-osm-muzea/) |
| [Vyhlídky](cs-vyhlidky.json) | 1,368 | 143 KB | [CSV](cs-vyhlidky_CS.csv) | [Excel](cs-vyhlidky_CS.xlsx) | [View](https://listbase.org/cs/tourism/cs-vyhlidky/) |
| [Kempy](cs-kempy.json) | 902 | 94 KB | [CSV](cs-kempy_CS.csv) | [Excel](cs-kempy_CS.xlsx) | [View](https://listbase.org/cs/tourism/cs-kempy/) |
| [Apartmány](cs-apartmany.json) | 624 | 67 KB | [CSV](cs-apartmany_CS.csv) | [Excel](cs-apartmany_CS.xlsx) | [View](https://listbase.org/cs/tourism/cs-apartmany/) |
| [Hostely](cs-hostely.json) | 408 | 43 KB | [CSV](cs-hostely_CS.csv) | [Excel](cs-hostely_CS.xlsx) | [View](https://listbase.org/cs/tourism/cs-hostely/) |
| [Chaty](cs-chaty.json) | 296 | 32 KB | [CSV](cs-chaty_CS.csv) | [Excel](cs-chaty_CS.xlsx) | [View](https://listbase.org/cs/tourism/cs-chaty/) |
| [Turistické oblasti České republiky (CzechTourism)](cs-turisticke-oblasti.json) | 43 | 6 KB | [CSV](cs-turisticke-oblasti_CS.csv) | [Excel](cs-turisticke-oblasti_CS.xlsx) | [View](https://listbase.org/cs/tourism/cs-turisticke-oblasti/) |
| [Turistické regiony České republiky (CzechTourism)](cs-turisticke-regiony.json) | 17 | 3 KB | [CSV](cs-turisticke-regiony_CS.csv) | [Excel](cs-turisticke-regiony_CS.xlsx) | [View](https://listbase.org/cs/tourism/cs-turisticke-regiony/) |
| [Kategorie hromadných ubytovacích zařízení (ČSÚ)](cs-kategorie-ubytovacich-zarizeni.json) | 12 | 3 KB | [CSV](cs-kategorie-ubytovacich-zarizeni_CS.csv) | [Excel](cs-kategorie-ubytovacich-zarizeni_CS.xlsx) | [View](https://listbase.org/cs/tourism/cs-kategorie-ubytovacich-zarizeni/) |

## Quick Start

```bash
# List all tourism datasets
curl https://cdn.cs.listbase.org/index.json | jq '.datasets[] | select(.category=="tourism") | .id'

# Fetch a dataset
curl https://cdn.cs.listbase.org/tourism/cs-informacni-body.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/cs/tourism/)
