# Makanan (Food & Nutrition)

1 datasets — 149 records

> Browse at [listbase.org/ms/food/](https://listbase.org/ms/food/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Restoran Michelin di Malaysia](ms-restoran-michelin.json) | 149 | 146 KB | [CSV](ms-restoran-michelin_MS.csv) | [Excel](ms-restoran-michelin_MS.xlsx) | [View](https://listbase.org/ms/food/ms-restoran-michelin/) |

## Quick Start

```bash
# List all food & nutrition datasets
curl https://cdn.ms.listbase.org/index.json | jq '.datasets[] | select(.category=="food") | .id'

# Fetch a dataset
curl https://cdn.ms.listbase.org/food/ms-restoran-michelin.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/ms/food/)
