# Premier League Match Analysis

An exploratory Jupyter Notebook project for analyzing English Premier League
match statistics and full-time results.

## Project contents

- `premier_league_explore.ipynb` - notebook for loading and exploring the data
- `data/PL Matches.csv` - original Premier League match data
- `data/raw_seasons/` - original season CSV downloads
- `data/combined/PremierLeague_2017-2026.csv` - combined match data for complete
  seasons from 2017/18 through 2025/26

## Load the combined data

```python
import pandas as pd

df = pd.read_csv("data/combined/PremierLeague_2017-2026.csv")
```
