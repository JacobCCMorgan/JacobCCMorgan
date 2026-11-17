### Jacob (Chieh-Ta) Chiang — data scientist and data engineer, fleet telematics

Five years inside an ELD / fleet-telematics company: device telemetry at 30-second cadence from thousands of heavy-duty trucks, FMCSA ELD compliance and output files, hours-of-service rules, driver risk scoring, device-management data, and the operational data that comes with running a hardware-plus-SaaS business.

#### Projects on real, de-identified fleet data

Index, findings and limits of each project: [**fleet-data-lab**](https://github.com/JacobCCMorgan/fleet-data-lab)

| Area | Repository | What is in it |
|---|---|---|
| Data modeling | [telematics-marts](https://github.com/JacobCCMorgan/telematics-marts) | dbt on DuckDB: staging, intermediate and mart layers, a type-2 snapshot of subscription slots, 67 schema and 5 singular tests, 42 pytest checks that pin the published numbers |
| Data foundation | [telematics-data-foundation](https://github.com/JacobCCMorgan/telematics-data-foundation) | Pseudonymization pipeline, twelve Parquet tables, DuckDB views, 43 data-quality checks |
| Pipelines | [eld-telemetry-replay](https://github.com/JacobCCMorgan/eld-telemetry-replay) | Event-time replay of 30-second telemetry from 2,191 devices: per-device stateful consumer, trip and stop segmentation, late-data watermarks measured against the oracle |
| Pipelines | [eld-device-log-parser](https://github.com/JacobCCMorgan/eld-device-log-parser) | 85,000 lines of device firmware log parsed into nine event tables and observability metrics |
| Analysis and models | [eld-subscription-lifecycle](https://github.com/JacobCCMorgan/eld-subscription-lifecycle) | Seven years of one-year subscriptions: survival analysis, a 60-day renewal risk list and a twelve-month renewal calendar |
| Analysis and models | [eld-ecm-disconnect](https://github.com/JacobCCMorgan/eld-ecm-disconnect) | Persistent versus transient engine-connection loss: six scorers under repeated cross-validation, decision curves, a tiered field-visit list |
| Compliance | [fmcsa-eld-logbook-toolkit](https://github.com/JacobCCMorgan/fmcsa-eld-logbook-toolkit) | FMCSA ELD output-file parser and check-value validator, eRODS reconciliation, hours-of-service rules engine |

#### Reference implementations on fictional fleets and public data

[**data-portfolio**](https://github.com/JacobCCMorgan/data-portfolio): a catalog of fleet / connected-vehicle business problems with engineered, reproducible reference implementations.

Python · SQL · dbt · pandas · DuckDB · scikit-learn / XGBoost · lifelines · pytest · GitHub Actions · Tableau · Firebase / GCP

[LinkedIn](https://www.linkedin.com/in/jacob-chiang)
