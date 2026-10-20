# Matematika (Mathematics)

3 datasets — 152 records

> Browse at [listbase.org/cs/math/](https://listbase.org/cs/math/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Komplexní Sada Dat Vzorců a Pravidel Derivací](math-derivative-formulas.json) | 57 | 13 KB | [CSV](math-derivative-formulas_CS.csv) | [Excel](math-derivative-formulas_CS.xlsx) | [View](https://listbase.org/cs/math/math-derivative-formulas/) |
| [Sada dat Běžné Integrační Vzorce](math-integral-formulas.json) | 56 | 13 KB | [CSV](math-integral-formulas_CS.csv) | [Excel](math-integral-formulas_CS.xlsx) | [View](https://listbase.org/cs/math/math-integral-formulas/) |
| [Komplexní Soubor Dat Tabulky Laplaceovy Transformace](math-laplace-transform.json) | 39 | 9 KB | [CSV](math-laplace-transform_CS.csv) | [Excel](math-laplace-transform_CS.xlsx) | [View](https://listbase.org/cs/math/math-laplace-transform/) |

## Quick Start

```bash
# List all mathematics datasets
curl https://cdn.cs.listbase.org/index.json | jq '.datasets[] | select(.category=="math") | .id'

# Fetch a dataset
curl https://cdn.cs.listbase.org/math/math-derivative-formulas.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/cs/math/)
