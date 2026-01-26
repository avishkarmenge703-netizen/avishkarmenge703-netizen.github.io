# Our AI Methodology

## How We Predict Fantasy Performance

Our model uses a three-step approach:

### 1. Data Collection
- Historical performance data (2021-2023 seasons)
- Player statistics from NFL sources
- Weekly matchup data

### 2. Feature Engineering
- 3-game moving averages
- Position-specific metrics
- Simple regression to mean

### 3. Prediction Algorithm
```python
prediction = average(last_3_games) * 0.95
