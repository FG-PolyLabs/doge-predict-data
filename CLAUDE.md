# doge-predict-data

Data repository for the Doge Predict project. JSON files here are auto-committed by the backend.

## Four-Repo Structure

| Repo | Role |
|------|------|
| `doge-predict-frontend-admin` | Admin frontend |
| `doge-predict-backend` | API + jobs (writes to this repo) |
| `doge-predict-frontend-public` | Public frontend (reads this repo) |
| `doge-predict-data` | JSON data files (this repo) |

## Files

All files are JSON arrays. Do not edit manually.

- `tracked_tokens.json` — tokens being tracked
- `price_snapshots.json` — price history
- `betting_markets.json` — active markets
- `market_snapshots.json` — market odds history
- `strategies.json` — betting strategies
- `backtest_results.json` — backtest results
