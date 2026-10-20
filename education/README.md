# Pendidikan (Education)

1 datasets — 145 records

> Browse at [listbase.org/ms/education/](https://listbase.org/ms/education/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Malaysia — Universities (universiti)](ms-universiti.json) | 145 | 42 KB | [CSV](ms-universiti_MS.csv) | [Excel](ms-universiti_MS.xlsx) | [View](https://listbase.org/ms/education/ms-universiti/) |

## Quick Start

```bash
# List all education datasets
curl https://cdn.ms.listbase.org/index.json | jq '.datasets[] | select(.category=="education") | .id'

# Fetch a dataset
curl https://cdn.ms.listbase.org/education/ms-universiti.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/ms/education/)
