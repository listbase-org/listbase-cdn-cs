# Hudba (Music)

3 datasets — 775 records

> Browse at [listbase.org/cs/music/](https://listbase.org/cs/music/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Skály](cs-skaly.json) | 613 | 62 KB | [CSV](cs-skaly_CS.csv) | [Excel](cs-skaly_CS.xlsx) | [View](https://listbase.org/cs/music/cs-skaly/) |
| [Sada Dat Referenční Tabulky Akordů Klavíru](music-piano-chords.json) | 84 | 22 KB | [CSV](music-piano-chords_CS.csv) | [Excel](music-piano-chords_CS.xlsx) | [View](https://listbase.org/cs/music/music-piano-chords/) |
| [Komplexní Datová Sada Kytarových Akordů](music-guitar-chords.json) | 78 | 24 KB | [CSV](music-guitar-chords_CS.csv) | [Excel](music-guitar-chords_CS.xlsx) | [View](https://listbase.org/cs/music/music-guitar-chords/) |

## Quick Start

```bash
# List all music datasets
curl https://cdn.cs.listbase.org/index.json | jq '.datasets[] | select(.category=="music") | .id'

# Fetch a dataset
curl https://cdn.cs.listbase.org/music/cs-skaly.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/cs/music/)
