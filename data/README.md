# Data

The datasets come from a university course project and are **not published** in this repository. They are derived from the public synthetic dataset of So, Boucher and Valdez (2021), available at http://www2.math.uconn.edu/~valdez/data.html; the original file has a different structure (one table) and would need adapting before running the notebook.

Expected files (place them in this folder before knitting `R/tarification_auto.Rmd`):

| File | Content |
|---|---|
| `DB_CNT.xlsx` (sheet `DB_CNT`) | Policy portfolio (one row per contract) |
| `DB_SIN.txt` | Claims (number and amount per policy) |
| `DB_TELEMATICS.csv` | Telematics variables (driving behaviour) |

The script writes its outputs to `out/`.
