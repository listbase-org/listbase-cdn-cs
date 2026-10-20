# Technologie (Technology)

15 datasets — 7,820 records

> Browse at [listbase.org/cs/tech/](https://listbase.org/cs/tech/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Knihovny v Česku](cs-knihovna.json) | 6,643 | 6379 KB | [CSV](cs-knihovna_CS.csv) | [Excel](cs-knihovna_CS.xlsx) | [View](https://listbase.org/cs/tech/cs-knihovna/) |
| [Emoji vlajky zemí](cs-zeme-emoji-vlajky.json) | 252 | 39 KB | [CSV](cs-zeme-emoji-vlajky_CS.csv) | [Excel](cs-zeme-emoji-vlajky_CS.xlsx) | [View](https://listbase.org/cs/tech/cs-zeme-emoji-vlajky/) |
| [Sada Dat Kódů Jazyků ISO 639 a Rodných Názvů](tech-language-codes.json) | 183 | 25 KB | [CSV](tech-language-codes_CS.csv) | [Excel](tech-language-codes_CS.xlsx) | [View](https://listbase.org/cs/tech/tech-language-codes/) |
| [Kompletní Datový Soubor Referenční Tabulky a Kódů Znaků ASCII](tech-ascii-table.json) | 128 | 28 KB | [CSV](tech-ascii-table_CS.csv) | [Excel](tech-ascii-table_CS.xlsx) | [View](https://listbase.org/cs/tech/tech-ascii-table/) |
| [Soubor Dat Univerzálních Klávesových Zkratek pro Windows a macOS](tech-keyboard-shortcuts.json) | 77 | 16 KB | [CSV](tech-keyboard-shortcuts_CS.csv) | [Excel](tech-keyboard-shortcuts_CS.xlsx) | [View](https://listbase.org/cs/tech/tech-keyboard-shortcuts/) |
| [Dataset HTML Znakových Entit a Speciálních Symbolů](tech-html-entities.json) | 75 | 17 KB | [CSV](tech-html-entities_CS.csv) | [Excel](tech-html-entities_CS.xlsx) | [View](https://listbase.org/cs/tech/tech-html-entities/) |
| [Dataset Běžných Čísel Síťových Portů a Služeb](tech-port-numbers.json) | 73 | 15 KB | [CSV](tech-port-numbers_CS.csv) | [Excel](tech-port-numbers_CS.xlsx) | [View](https://listbase.org/cs/tech/tech-port-numbers/) |
| [Datový Set Běžných MIME Typů a Přípon Souborů](tech-mime-types.json) | 70 | 13 KB | [CSV](tech-mime-types_CS.csv) | [Excel](tech-mime-types_CS.xlsx) | [View](https://listbase.org/cs/tech/tech-mime-types/) |
| [Sada Dat Běžných Symbolů Unicode a HTML Entit](tech-unicode-symbols.json) | 70 | 14 KB | [CSV](tech-unicode-symbols_CS.csv) | [Excel](tech-unicode-symbols_CS.xlsx) | [View](https://listbase.org/cs/tech/tech-unicode-symbols/) |
| [HTTP Status Codes Dataset](tech-http-codes.json) | 62 | 14 KB | [CSV](tech-http-codes_CS.csv) | [Excel](tech-http-codes_CS.xlsx) | [View](https://listbase.org/cs/tech/tech-http-codes/) |
| [Sada Dat Základních Vzorů Regulárních Výrazů](tech-regex-patterns.json) | 45 | 12 KB | [CSV](tech-regex-patterns_CS.csv) | [Excel](tech-regex-patterns_CS.xlsx) | [View](https://listbase.org/cs/tech/tech-regex-patterns/) |
| [Sada Dat Velikostí a Rozměrů Obrázků Sociálních Médií](tech-social-media-sizes.json) | 42 | 12 KB | [CSV](tech-social-media-sizes_CS.csv) | [Excel](tech-social-media-sizes_CS.xlsx) | [View](https://listbase.org/cs/tech/tech-social-media-sizes/) |
| [Screen Resolutions & Aspect Ratios Dataset](tech-screen-resolutions.json) | 35 | 9 KB | [CSV](tech-screen-resolutions_CS.csv) | [Excel](tech-screen-resolutions_CS.xlsx) | [View](https://listbase.org/cs/tech/tech-screen-resolutions/) |
| [Datová Sada Velikostí Papíru a Pixelových Rozměrů](tech-paper-sizes.json) | 33 | 13 KB | [CSV](tech-paper-sizes_CS.csv) | [Excel](tech-paper-sizes_CS.xlsx) | [View](https://listbase.org/cs/tech/tech-paper-sizes/) |
| [Dataset Tabulek Pravdivosti Logických Hradel](tech-logic-gates.json) | 32 | 9 KB | [CSV](tech-logic-gates_CS.csv) | [Excel](tech-logic-gates_CS.xlsx) | [View](https://listbase.org/cs/tech/tech-logic-gates/) |

## Quick Start

```bash
# List all technology datasets
curl https://cdn.cs.listbase.org/index.json | jq '.datasets[] | select(.category=="tech") | .id'

# Fetch a dataset
curl https://cdn.cs.listbase.org/tech/cs-knihovna.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/cs/tech/)
