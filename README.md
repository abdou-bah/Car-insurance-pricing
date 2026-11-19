# Data

The datasets come from a university course project and are **not published** in this repository.

Expected files (place them in this folder before knitting `R/tarification_auto.Rmd`):

| File | Content |
|---|---|
| `DB_CNT.xlsx` (sheet `DB_CNT`) | Policy portfolio (one row per contract) |
| `DB_SIN.txt` | Claims (number and amount per policy) |
| `DB_TELEMATICS.csv` | Telematics variables (driving behaviour) |

The script writes its outputs to `out/`.
