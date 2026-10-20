# Geografi (Geography)

12 datasets — 27,303 records

> Browse at [listbase.org/ms/geography/](https://listbase.org/ms/geography/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Sungai di Malaysia](ms-sungai.json) | 24,290 | 8770 KB | [CSV](ms-sungai_MS.csv) | [Excel](ms-sungai_MS.xlsx) | [View](https://listbase.org/ms/geography/ms-sungai/) |
| [Gunung di Malaysia](ms-gunung.json) | 1,668 | 604 KB | [CSV](ms-gunung_MS.csv) | [Excel](ms-gunung_MS.xlsx) | [View](https://listbase.org/ms/geography/ms-gunung/) |
| [Senarai Bandar dan Pekan Malaysia](ms-bandar.json) | 444 | 126 KB | [CSV](ms-bandar_MS.csv) | [Excel](ms-bandar_MS.xlsx) | [View](https://listbase.org/ms/geography/ms-bandar/) |
| [Kod panggilan negara](ms-kod-panggilan-negara.json) | 242 | 51 KB | [CSV](ms-kod-panggilan-negara_MS.csv) | [Excel](ms-kod-panggilan-negara_MS.xlsx) | [View](https://listbase.org/ms/geography/ms-kod-panggilan-negara/) |
| [Pulau di Malaysia](ms-pulau.json) | 195 | 73 KB | [CSV](ms-pulau_MS.csv) | [Excel](ms-pulau_MS.xlsx) | [View](https://listbase.org/ms/geography/ms-pulau/) |
| [Pantai di Malaysia](ms-pantai.json) | 158 | 60 KB | [CSV](ms-pantai_MS.csv) | [Excel](ms-pantai_MS.xlsx) | [View](https://listbase.org/ms/geography/ms-pantai/) |
| [Air terjun dan jeram di Malaysia](ms-air-terjun.json) | 145 | 84 KB | [CSV](ms-air-terjun_MS.csv) | [Excel](ms-air-terjun_MS.xlsx) | [View](https://listbase.org/ms/geography/ms-air-terjun/) |
| [Gua di Malaysia](ms-gua.json) | 92 | 35 KB | [CSV](ms-gua_MS.csv) | [Excel](ms-gua_MS.xlsx) | [View](https://listbase.org/ms/geography/ms-gua/) |
| [Taman negara di Malaysia](ms-taman-negara.json) | 25 | 12 KB | [CSV](ms-taman-negara_MS.csv) | [Excel](ms-taman-negara_MS.xlsx) | [View](https://listbase.org/ms/geography/ms-taman-negara/) |
| [Tasik di Malaysia](ms-tasik.json) | 19 | 9 KB | [CSV](ms-tasik_MS.csv) | [Excel](ms-tasik_MS.xlsx) | [View](https://listbase.org/ms/geography/ms-tasik/) |
| [Rumah api di Malaysia](ms-rumah-api.json) | 13 | 8 KB | [CSV](ms-rumah-api_MS.csv) | [Excel](ms-rumah-api_MS.xlsx) | [View](https://listbase.org/ms/geography/ms-rumah-api/) |
| [Tanjung di Malaysia](ms-tanjung.json) | 12 | 7 KB | [CSV](ms-tanjung_MS.csv) | [Excel](ms-tanjung_MS.xlsx) | [View](https://listbase.org/ms/geography/ms-tanjung/) |

## Quick Start

```bash
# List all geography datasets
curl https://cdn.ms.listbase.org/index.json | jq '.datasets[] | select(.category=="geography") | .id'

# Fetch a dataset
curl https://cdn.ms.listbase.org/geography/ms-sungai.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/ms/geography/)
