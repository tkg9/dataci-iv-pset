# DataCI IV problem set data

Public data files for Yale SOM **MGT 510 (FA26) Data Analysis and Causal Inference**, Problem Set: Instrumental Variables (family heir vs. outside CEO).

## Files

- `family_ceo_transitions.csv` — 12,000 simulated CEO transitions
- `family_ceo_transitions_README.txt` — data dictionary

## Load in Python / Colab

```python
import pandas as pd

RAW_URL = "https://raw.githubusercontent.com/tkg9/dataci-iv-pset/main/family_ceo_transitions.csv"
df = pd.read_csv(RAW_URL)
```

The raw CSV URL is also:

https://raw.githubusercontent.com/tkg9/dataci-iv-pset/main/family_ceo_transitions.csv
