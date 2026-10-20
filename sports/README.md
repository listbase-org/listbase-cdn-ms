# Sukan (Sports)

1 datasets — 36 records

> Browse at [listbase.org/ms/sports/](https://listbase.org/ms/sports/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Stadium di Malaysia](ms-stadium.json) | 36 | 16 KB | [CSV](ms-stadium_MS.csv) | [Excel](ms-stadium_MS.xlsx) | [View](https://listbase.org/ms/sports/ms-stadium/) |

## Quick Start

```bash
# List all sports datasets
curl https://cdn.ms.listbase.org/index.json | jq '.datasets[] | select(.category=="sports") | .id'

# Fetch a dataset
curl https://cdn.ms.listbase.org/sports/ms-stadium.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/ms/sports/)
