# Finance a Obchod (Finance & Trade)

12 datasets — 3,907 records

> Browse at [listbase.org/cs/finance/](https://listbase.org/cs/finance/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Bankomaty](cs-bankomaty.json) | 1,636 | 165 KB | [CSV](cs-bankomaty_CS.csv) | [Excel](cs-bankomaty_CS.xlsx) | [View](https://listbase.org/cs/finance/cs-bankomaty/) |
| [Banky (OSM)](cs-osm-banky.json) | 1,346 | 137 KB | [CSV](cs-osm-banky_CS.csv) | [Excel](cs-osm-banky_CS.xlsx) | [View](https://listbase.org/cs/finance/cs-osm-banky/) |
| [Stavebniny](cs-stavebniny.json) | 344 | 36 KB | [CSV](cs-stavebniny_CS.csv) | [Excel](cs-stavebniny_CS.xlsx) | [View](https://listbase.org/cs/finance/cs-stavebniny/) |
| [SWIFT/BIC kódy — Česko](cs-swift-kody.json) | 148 | 21 KB | [CSV](cs-swift-kody_CS.csv) | [Excel](cs-swift-kody_CS.xlsx) | [View](https://listbase.org/cs/finance/cs-swift-kody/) |
| [Dataset Registru Předpon Čárových Kódů a Zemí GS1](finance-gs1-codes.json) | 126 | 19 KB | [CSV](finance-gs1-codes_CS.csv) | [Excel](finance-gs1-codes_CS.xlsx) | [View](https://listbase.org/cs/finance/finance-gs1-codes/) |
| [Datový Soubor Kapitol Kódů HS (Harmonizovaný Systém)](finance-hs-codes.json) | 98 | 22 KB | [CSV](finance-hs-codes_CS.csv) | [Excel](finance-hs-codes_CS.xlsx) | [View](https://listbase.org/cs/finance/finance-hs-codes/) |
| [Komplexní Datový Soubor Sazeb DPH/GST Podle Zemí](finance-vat-rates.json) | 75 | 18 KB | [CSV](finance-vat-rates_CS.csv) | [Excel](finance-vat-rates_CS.xlsx) | [View](https://listbase.org/cs/finance/finance-vat-rates/) |
| [Banky v České republice — kódy platebního styku](cs-banky.json) | 53 | 15 KB | [CSV](cs-banky_CS.csv) | [Excel](cs-banky_CS.xlsx) | [View](https://listbase.org/cs/finance/cs-banky/) |
| [Banky v ČR — účastníci systému CERTIS](cs-banky-certis.json) | 45 | 13 KB | [CSV](cs-banky-certis_CS.csv) | [Excel](cs-banky-certis_CS.xlsx) | [View](https://listbase.org/cs/finance/cs-banky-certis/) |
| [Dataset Kódů a Specifikací Přepravních Kontejnerů ISO 6346](finance-container-codes.json) | 14 | 8 KB | [CSV](finance-container-codes_CS.csv) | [Excel](finance-container-codes_CS.xlsx) | [View](https://listbase.org/cs/finance/finance-container-codes/) |
| [Plynové elektrárny v Česku](cs-plynove-elektrarny.json) | 11 | 9 KB | [CSV](cs-plynove-elektrarny_CS.csv) | [Excel](cs-plynove-elektrarny_CS.xlsx) | [View](https://listbase.org/cs/finance/cs-plynove-elektrarny/) |
| [Sada dat Incoterms 2020 Pravidla a Definice](finance-incoterms.json) | 11 | 8 KB | [CSV](finance-incoterms_CS.csv) | [Excel](finance-incoterms_CS.xlsx) | [View](https://listbase.org/cs/finance/finance-incoterms/) |

## Quick Start

```bash
# List all finance & trade datasets
curl https://cdn.cs.listbase.org/index.json | jq '.datasets[] | select(.category=="finance") | .id'

# Fetch a dataset
curl https://cdn.cs.listbase.org/finance/cs-bankomaty.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/cs/finance/)
