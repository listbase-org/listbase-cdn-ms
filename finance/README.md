# Kewangan dan Perdagangan (Finance & Trade)

1 datasets — 144 records

> Browse at [listbase.org/ms/finance/](https://listbase.org/ms/finance/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Senarai Bank di Malaysia](ms-bank.json) | 144 | 29 KB | [CSV](ms-bank_MS.csv) | [Excel](ms-bank_MS.xlsx) | [View](https://listbase.org/ms/finance/ms-bank/) |

## Quick Start

```bash
# List all finance & trade datasets
curl https://cdn.ms.listbase.org/index.json | jq '.datasets[] | select(.category=="finance") | .id'

# Fetch a dataset
curl https://cdn.ms.listbase.org/finance/ms-bank.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/ms/finance/)
