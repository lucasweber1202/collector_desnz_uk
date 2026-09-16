# Standalone portability

Verified 2026-09-16. No fleet sibling is required.

```powershell
git clone https://github.com/lucasweber1202/collector_desnz_uk.git
Set-Location collector_desnz_uk
py -3.11 -m venv .venv
.\.venv\Scripts\Activate.ps1
python -m pip install -e ".[dev]"
Copy-Item .env.example .env
python -m pytest -q
ruff check .
mypy .
python main.py --source-id desnz_road_fuels
```

Python 3.11/3.12. Local collection requires `COLLECTOR_DB_URL`; Databricks is
optional behind `PROD=true`. Raw snapshots write below configurable
`COLLECTOR_RAW_DIR` (default repository-local `_raw`). Network: HTTPS to
`www.gov.uk` and official GOV.UK attachment hosts. Standard corporate proxy/CA
variables are supported by the HTTP stack; TLS is not disabled.

Certification: standalone code PASS; sibling required NO; database and internet
required for collection; Databricks not required.
