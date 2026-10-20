# Čas a Kalendář (Time & Calendar)

5 datasets — 1,088 records

> Browse at [listbase.org/cs/time/](https://listbase.org/cs/time/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [České státní svátky a významné dny (1952–2030)](cs-statni-svatky-a-vyznamne-dny.json) | 794 | 479 KB | [CSV](cs-statni-svatky-a-vyznamne-dny_CS.csv) | [Excel](cs-statni-svatky-a-vyznamne-dny_CS.xlsx) | [View](https://listbase.org/cs/time/cs-statni-svatky-a-vyznamne-dny/) |
| [České státní svátky (multijazyčné, openpotato/OpenHolidays)](cs-statni-svatky-multijazycne.json) | 154 | 75 KB | [CSV](cs-statni-svatky-multijazycne_CS.csv) | [Excel](cs-statni-svatky-multijazycne_CS.xlsx) | [View](https://listbase.org/cs/time/cs-statni-svatky-multijazycne/) |
| [České školní prázdniny (multijazyčné, openpotato/OpenHolidays)](cs-skolni-prazdniny.json) | 116 | 66 KB | [CSV](cs-skolni-prazdniny_CS.csv) | [Excel](cs-skolni-prazdniny_CS.xlsx) | [View](https://listbase.org/cs/time/cs-skolni-prazdniny/) |
| [Komplexní Datová Sada Zvířat Čínského Zvěrokruhu (12 Znamení)](time-chinese-zodiac.json) | 12 | 11 KB | [CSV](time-chinese-zodiac_CS.csv) | [Excel](time-chinese-zodiac_CS.xlsx) | [View](https://listbase.org/cs/time/time-chinese-zodiac/) |
| [Kompletní Data Západních Znamení Zvěrokruhu](time-zodiac-signs.json) | 12 | 9 KB | [CSV](time-zodiac-signs_CS.csv) | [Excel](time-zodiac-signs_CS.xlsx) | [View](https://listbase.org/cs/time/time-zodiac-signs/) |

## Quick Start

```bash
# List all time & calendar datasets
curl https://cdn.cs.listbase.org/index.json | jq '.datasets[] | select(.category=="time") | .id'

# Fetch a dataset
curl https://cdn.cs.listbase.org/time/cs-statni-svatky-a-vyznamne-dny.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/cs/time/)
