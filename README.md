# ListBase CDN — Bahasa Melayu (ms)

Open dataset collection for **Bahasa Melayu** (Malay).
504 datasets across 15 categories with 496,790 total records.

> Browse and download at [https://listbase.org/ms/](https://listbase.org/ms/)

## Categories

| Category | Datasets |
|----------|----------|
| [Budaya dan Agama (Culture & Religion)](culture/) | 42 |
| [Pendidikan (Education)](education/) | 1 |
| [Hiburan (Entertainment)](entertainment/) | 1 |
| [Alam Sekitar (Environment)](environment/) | 1 |
| [Kewangan dan Perdagangan (Finance & Trade)](finance/) | 1 |
| [Makanan (Food & Nutrition)](food/) | 1 |
| [Geografi (Geography)](geography/) | 12 |
| [Kesihatan (Health)](health/) | 17 |
| [Bahasa (Language)](language/) | 1 |
| [Politik (Politics)](politics/) | 102 |
| [Rujukan (Reference)](reference/) | 248 |
| [Sukan (Sports)](sports/) | 1 |
| [Teknologi (Technology)](tech/) | 1 |
| [Masa dan Kalendar (Time & Calendar)](time/) | 20 |
| [Pengangkutan (Transport)](transport/) | 55 |

## Usage

### Browse on the web
Visit [listbase.org/ms/](https://listbase.org/ms/) to search, preview, and download in Excel, CSV, or PDF.

### Fetch via CDN
```bash
# Dataset index (metadata only)
curl https://cdn.ms.listbase.org/index.json

# Full dataset (JSON)
curl https://cdn.ms.listbase.org/geography/th-central-provinces.json

# Download as Excel or CSV
curl -O https://cdn.ms.listbase.org/geography/th-central-provinces_MS.xlsx
curl -O https://cdn.ms.listbase.org/geography/th-central-provinces_MS.csv

# Build dump (metadata + sample rows, gzipped)
curl https://cdn.ms.listbase.org/dump.json.gz | gunzip
```

### Use in JavaScript
```js
const res = await fetch('https://cdn.ms.listbase.org/geography/th-central-provinces.json');
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
│   ├── {dataset}_MS.csv   # CSV download
│   └── {dataset}_MS.xlsx  # Excel download
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
