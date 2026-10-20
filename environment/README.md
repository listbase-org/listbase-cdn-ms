# Alam Sekitar (Environment)

1 datasets — 55 records

> Browse at [listbase.org/ms/environment/](https://listbase.org/ms/environment/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Stesen janakuasa di Malaysia](ms-stesen-janakuasa.json) | 55 | 26 KB | [CSV](ms-stesen-janakuasa_MS.csv) | [Excel](ms-stesen-janakuasa_MS.xlsx) | [View](https://listbase.org/ms/environment/ms-stesen-janakuasa/) |

## Quick Start

```bash
# List all environment datasets
curl https://cdn.ms.listbase.org/index.json | jq '.datasets[] | select(.category=="environment") | .id'

# Fetch a dataset
curl https://cdn.ms.listbase.org/environment/ms-stesen-janakuasa.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/ms/environment/)
