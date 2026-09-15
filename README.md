# collector_desnz_uk

Standalone collector for public DESNZ datasets relevant to UK inflation. The
initial dataset is [Weekly road fuel prices](https://www.gov.uk/government/statistics/weekly-road-fuel-prices).

The repository owns DESNZ extraction and raw point-in-time persistence. It does
not map predictors to CPI targets or calculate monthly/modelled features; those
tasks belong to `uk_inflation_predictors`.

## Current coverage

- Publisher: Department for Energy Security and Net Zero (DESNZ)
- Dataset: UK weekly road fuel prices
- Official history: 9 June 2003 to the latest publication
- Artifacts: frozen 2003–2017 CSV plus dynamically discovered 2018–present CSV
- Series: ULSP and ULSD pump prices, duty rates and VAT rates (6 raw series)
- Schema: `collector_desnz_uk`

## Run locally

```bash
python -m pip install -r requirements.txt
cp .env.example .env
python main.py
```

The default local database URL is documented in `.env.example`. Raw snapshots
are written below the gitignored snapshot directory configured there.
