# Data audit — collector_desnz_uk

- Audit seed: `20260918`
- Source version: live capture on 2026-09-18
- Test result: **39 passed**
- Execution: **PASS**
- Overall: **PARTIAL** — Valores e ponta validados; disponibilidade histórica do arquivo mutável agora é first_seen/inferred, e não uma falsa garantia oficial.
- Output: 7,290 observations, 6 series, 2003-06-09 to 2026-09-14.
- Sample: 20; values matched: 20; failures: 0; not verifiable: 0.

## Observation evidence

| # | Series | Period | Collector | Official source | Unit/frequency evidence | Result |
|---:|---|---|---:|---:|---|---|
| 1 | `DESNZ_ROADFUEL_ULSD_VATRATE` | 2003-06-09 | 17.5 | 17.5 | percent; weekly; CSV row 2; ULSD (Ultra low sulphur diesel) VAT percentage rate | **PASS** |
| 2 | `DESNZ_ROADFUEL_ULSD_PUMPPRICE` | 2026-09-14 | 190.72 | 190.72 | pence/litre; weekly; CSV row 456; ULSD (Ultra low sulphur diesel) Pump price in pence/litre | **PASS** |
| 3 | `DESNZ_ROADFUEL_ULSP_VATRATE` | 2007-06-18 | 17.5 | 17.5 | percent; weekly; CSV row 212; ULSP (Ultra low sulphur unleaded petrol) VAT percentage rate | **PASS** |
| 4 | `DESNZ_ROADFUEL_ULSD_PUMPPRICE` | 2003-10-06 | 77.66 | 77.66 | pence/litre; weekly; CSV row 19; ULSD (Ultra low sulphur diesel) Pump price in pence/litre | **PASS** |
| 5 | `DESNZ_ROADFUEL_ULSD_DUTYRATE` | 2007-05-28 | 48.35 | 48.35 | pence/litre; weekly; CSV row 209; ULSD (Ultra low sulphur diesel) Duty rate in pence/litre | **PASS** |
| 6 | `DESNZ_ROADFUEL_ULSD_PUMPPRICE` | 2006-04-03 | 95.64 | 95.64 | pence/litre; weekly; CSV row 149; ULSD (Ultra low sulphur diesel) Pump price in pence/litre | **PASS** |
| 7 | `DESNZ_ROADFUEL_ULSD_VATRATE` | 2015-10-19 | 20.0 | 20.0 | percent; weekly; CSV row 647; ULSD (Ultra low sulphur diesel) VAT percentage rate | **PASS** |
| 8 | `DESNZ_ROADFUEL_ULSD_DUTYRATE` | 2015-06-15 | 57.95 | 57.95 | pence/litre; weekly; CSV row 629; ULSD (Ultra low sulphur diesel) Duty rate in pence/litre | **PASS** |
| 9 | `DESNZ_ROADFUEL_ULSP_VATRATE` | 2013-03-25 | 20.0 | 20.0 | percent; weekly; CSV row 513; ULSP (Ultra low sulphur unleaded petrol) VAT percentage rate | **PASS** |
| 10 | `DESNZ_ROADFUEL_ULSD_VATRATE` | 2015-11-16 | 20.0 | 20.0 | percent; weekly; CSV row 651; ULSD (Ultra low sulphur diesel) VAT percentage rate | **PASS** |
| 11 | `DESNZ_ROADFUEL_ULSD_VATRATE` | 2025-11-24 | 20.0 | 20.0 | percent; weekly; CSV row 414; ULSD (Ultra low sulphur diesel) VAT percentage rate | **PASS** |
| 12 | `DESNZ_ROADFUEL_ULSP_VATRATE` | 2026-08-10 | 20.0 | 20.0 | percent; weekly; CSV row 451; ULSP (Ultra low sulphur unleaded petrol) VAT percentage rate | **PASS** |
| 13 | `DESNZ_ROADFUEL_ULSD_PUMPPRICE` | 2026-09-07 | 186.36 | 186.36 | pence/litre; weekly; CSV row 455; ULSD (Ultra low sulphur diesel) Pump price in pence/litre | **PASS** |
| 14 | `DESNZ_ROADFUEL_ULSP_DUTYRATE` | 2026-04-27 | 52.95 | 52.95 | pence/litre; weekly; CSV row 436; ULSP (Ultra low sulphur unleaded petrol) Duty rate in pence/litre | **PASS** |
| 15 | `DESNZ_ROADFUEL_ULSP_PUMPPRICE` | 2016-08-15 | 109.28 | 109.28 | pence/litre; weekly; CSV row 690; ULSP (Ultra low sulphur unleaded petrol) Pump price in pence/litre | **PASS** |
| 16 | `DESNZ_ROADFUEL_ULSP_VATRATE` | 2025-06-09 | 20.0 | 20.0 | percent; weekly; CSV row 390; ULSP (Ultra low sulphur unleaded petrol) VAT percentage rate | **PASS** |
| 17 | `DESNZ_ROADFUEL_ULSP_PUMPPRICE` | 2008-03-10 | 105.96 | 105.96 | pence/litre; weekly; CSV row 250; ULSP (Ultra low sulphur unleaded petrol) Pump price in pence/litre | **PASS** |
| 18 | `DESNZ_ROADFUEL_ULSD_VATRATE` | 2020-11-16 | 20.0 | 20.0 | percent; weekly; CSV row 152; ULSD (Ultra low sulphur diesel) VAT percentage rate | **PASS** |
| 19 | `DESNZ_ROADFUEL_ULSP_VATRATE` | 2025-10-06 | 20.0 | 20.0 | percent; weekly; CSV row 407; ULSP (Ultra low sulphur unleaded petrol) VAT percentage rate | **PASS** |
| 20 | `DESNZ_ROADFUEL_ULSD_VATRATE` | 2019-03-18 | 20.0 | 20.0 | percent; weekly; CSV row 65; ULSD (Ultra low sulphur diesel) VAT percentage rate | **PASS** |

## Filtering and metadata

- `{"file":"https://assets.publishing.service.gov.uk/media/68a3326b32d2c63f869343a3/weekly_road_fuel_prices_2003_to_2017.csv","raw_rows":760,"columns":["Date","ULSP (Ultra low sulphur unleaded petrol) Pump price in pence/litre","ULSD (Ultra low sulphur diesel) Pump price in pence/litre","ULSP (Ultra low sulphur unleaded petrol) Duty rate in pence/litre","ULSD (Ultra low sulphur diesel) Duty rate in pence/litre","ULSP (Ultra low sulphur unleaded petrol) VAT percentage rate","ULSD (Ultra low sulphur diesel) VAT percentage rate"]}`
- `{"file":"https://assets.publishing.service.gov.uk/media/6aa801e097b321a2d34ee250/CSV__2018_-__.csv","raw_rows":455,"columns":["Date","ULSP (Ultra low sulphur unleaded petrol) Pump price in pence/litre","ULSD (Ultra low sulphur diesel) Pump price in pence/litre","ULSP (Ultra low sulphur unleaded petrol) Duty rate in pence/litre","ULSD (Ultra low sulphur diesel) Duty rate in pence/litre","ULSP (Ultra low sulphur unleaded petrol) VAT percentage rate","ULSD (Ultra low sulphur diesel) VAT percentage rate"]}`

The audit read the captured official artifact independently of the collector parser. It checked identifier linkage, published labels, units, frequency and first/latest boundaries. Source artifacts are identified by SHA-256 in the audit evidence.

## Point-in-time and revisions

Predictor as-of queries filter availability before ranking vintages. `inferred` and `unknown` remain excluded by default. Current mutable-file backfills are recorded at `first_seen`; later observed revisions create later vintages and do not inherit an original release timestamp. Actual pre-collection historical editions remain `NOT_VERIFIABLE` unless an archived source file exists.

## Corrections

- Backfills do arquivo mutável usam first_seen; datas antigas da página deixaram de ser tratadas como prova do valor atual.
- Consulta as-of protege linhas legadas contra vazamento anterior a collected_at.

## Result

**PARTIAL** — Valores e ponta validados; disponibilidade histórica do arquivo mutável agora é first_seen/inferred, e não uma falsa garantia oficial.
