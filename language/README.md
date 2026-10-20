# Jazyk (Language)

6 datasets — 708 records

> Browse at [listbase.org/cs/language/](https://listbase.org/cs/language/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Komplexní Tabulka Čínských Pinyin Slabik a Průvodce Výslovností](lang-pinyin-table.json) | 408 | 101 KB | [CSV](lang-pinyin-table_CS.csv) | [Excel](lang-pinyin-table_CS.xlsx) | [View](https://listbase.org/cs/language/lang-pinyin-table/) |
| [Jazyky podle ISO 639-1](cs-jazyky.json) | 115 | 22 KB | [CSV](cs-jazyky_CS.csv) | [Excel](cs-jazyky_CS.xlsx) | [View](https://listbase.org/cs/language/cs-jazyky/) |
| [Datová Sada Tabulky Klasifikace Anglických Zájmen](lang-english-pronouns.json) | 69 | 21 KB | [CSV](lang-english-pronouns_CS.csv) | [Excel](lang-english-pronouns_CS.xlsx) | [View](https://listbase.org/cs/language/lang-english-pronouns/) |
| [Datová Sada Japonské Tabulky Hiragany a Mapování Romaji](lang-hiragana-table.json) | 46 | 11 KB | [CSV](lang-hiragana-table_CS.csv) | [Excel](lang-hiragana-table_CS.xlsx) | [View](https://listbase.org/cs/language/lang-hiragana-table/) |
| [Kompletní sada dat tabulky znaků japonské katakany](lang-katakana-table.json) | 46 | 11 KB | [CSV](lang-katakana-table_CS.csv) | [Excel](lang-katakana-table_CS.xlsx) | [View](https://listbase.org/cs/language/lang-katakana-table/) |
| [Kompletní Sada Dat Znaků Řecké Abecedy](lang-greek-alphabet.json) | 24 | 9 KB | [CSV](lang-greek-alphabet_CS.csv) | [Excel](lang-greek-alphabet_CS.xlsx) | [View](https://listbase.org/cs/language/lang-greek-alphabet/) |

## Quick Start

```bash
# List all language datasets
curl https://cdn.cs.listbase.org/index.json | jq '.datasets[] | select(.category=="language") | .id'

# Fetch a dataset
curl https://cdn.cs.listbase.org/language/lang-pinyin-table.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/cs/language/)
