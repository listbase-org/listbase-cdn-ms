# Teknologi (Technology)

1 datasets — 58 records

> Browse at [listbase.org/ms/tech/](https://listbase.org/ms/tech/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Perpustakaan di Malaysia](ms-perpustakaan.json) | 58 | 25 KB | [CSV](ms-perpustakaan_MS.csv) | [Excel](ms-perpustakaan_MS.xlsx) | [View](https://listbase.org/ms/tech/ms-perpustakaan/) |

## Quick Start

```bash
# List all technology datasets
curl https://cdn.ms.listbase.org/index.json | jq '.datasets[] | select(.category=="tech") | .id'

# Fetch a dataset
curl https://cdn.ms.listbase.org/tech/ms-perpustakaan.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/ms/tech/)
