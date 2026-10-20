# Hiburan (Entertainment)

1 datasets — 118 records

> Browse at [listbase.org/ms/entertainment/](https://listbase.org/ms/entertainment/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Saluran TV Malaysia](ms-saluran-tv.json) | 118 | 45 KB | [CSV](ms-saluran-tv_MS.csv) | [Excel](ms-saluran-tv_MS.xlsx) | [View](https://listbase.org/ms/entertainment/ms-saluran-tv/) |

## Quick Start

```bash
# List all entertainment datasets
curl https://cdn.ms.listbase.org/index.json | jq '.datasets[] | select(.category=="entertainment") | .id'

# Fetch a dataset
curl https://cdn.ms.listbase.org/entertainment/ms-saluran-tv.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/ms/entertainment/)
