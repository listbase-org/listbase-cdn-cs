# ListBase CDN — Čeština (cs)

Open dataset collection for **Čeština** (Czech).
477 datasets across 21 categories with 414,525 total records.

> Browse and download at [https://listbase.org/cs/](https://listbase.org/cs/)

## Categories

| Category | Datasets |
|----------|----------|
| [Kultura a Náboženství (Culture & Religion)](culture/) | 10 |
| [Vzdělávání (Education)](education/) | 3 |
| [Zábava (Entertainment)](entertainment/) | 1 |
| [Životní prostředí (Environment)](environment/) | 19 |
| [Finance a Obchod (Finance & Trade)](finance/) | 12 |
| [Jídlo a Výživa (Food & Nutrition)](food/) | 10 |
| [Geografie (Geography)](geography/) | 141 |
| [Zdraví (Health)](health/) | 4 |
| [Jazyk (Language)](language/) | 6 |
| [Matematika (Mathematics)](math/) | 3 |
| [Hudba (Music)](music/) | 3 |
| [Politika (Politics)](politics/) | 3 |
| [Reference](reference/) | 150 |
| [Věda (Science)](science/) | 30 |
| [Společnost (Society)](society/) | 1 |
| [Sport (Sports)](sports/) | 1 |
| [Technologie (Technology)](tech/) | 15 |
| [Čas a Kalendář (Time & Calendar)](time/) | 5 |
| [Cestovní ruch (Tourism)](tourism/) | 14 |
| [Doprava (Transport)](transport/) | 21 |
| [Jednotky a Měření (Units & Measurements)](units/) | 25 |

## Usage

### Browse on the web
Visit [listbase.org/cs/](https://listbase.org/cs/) to search, preview, and download in Excel, CSV, or PDF.

### Fetch via CDN
```bash
# Dataset index (metadata only)
curl https://cdn.cs.listbase.org/index.json

# Full dataset (JSON)
curl https://cdn.cs.listbase.org/geography/th-central-provinces.json

# Download as Excel or CSV
curl -O https://cdn.cs.listbase.org/geography/th-central-provinces_CS.xlsx
curl -O https://cdn.cs.listbase.org/geography/th-central-provinces_CS.csv

# Build dump (metadata + sample rows, gzipped)
curl https://cdn.cs.listbase.org/dump.json.gz | gunzip
```

### Use in JavaScript
```js
const res = await fetch('https://cdn.cs.listbase.org/geography/th-central-provinces.json');
const data = await res.json();
console.log(data.name);    // "ภาคกลาง — จังหวัดในภาคกลาง"
console.log(data.rows);    // [{ ... }, ...]
```

## File Structure

```
├── index.json              # Dataset index (metadata + file info)
├── dump.json.gz            # Build dump (metadata + 20 sample rows per dataset)
├── {category}/
│   ├── README.md           # Category overview
│   ├── {dataset}.json      # Full dataset with rows
│   ├── {dataset}_CS.csv   # CSV download
│   └── {dataset}_CS.xlsx  # Excel download
```

## Dataset JSON Format

Each `.json` file contains:

| Field | Description |
|-------|-------------|
| `id` | Unique dataset identifier |
| `name` | Dataset name |
| `description` | What this dataset contains |
| `category` | Category (e.g. geography, finance) |
| `source` | Data source attribution |
| `updated` | Last updated date |
| `record_count` | Number of records |
| `columns` | Column definitions (key, label, type) |
| `rows` | Array of data records |

## License

Data is provided under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).
See individual dataset `source` fields for original data attribution.

---

Part of [ListBase](https://listbase.org) — Free Reference Tables & Lists
