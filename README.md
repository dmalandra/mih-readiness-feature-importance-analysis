# Men's Ice Hockey Readiness Feature Importance Analysis

Random Forest feature importance analysis for neuromuscular readiness monitoring, developed as part of an athlete performance profiling system at the DIII level.

## Overview
This notebook uses a Random Forest model to identify which load and wellness metrics are most predictive of athlete readiness outcomes, pulling data from Google Sheets via the Sheets API.



### Credentials
This project uses a Google Service Account to access Google Sheets.

1. Obtain a sheets_keys.json service account key file from Google Cloud Console
2. Copy .env.example to .env:
```bash
cp .env.example .env
```
3. Update GOOGLE_SHEETS_KEY_PATH in .env to point to your key file

Never commit .env or sheets_keys.json to version control.

