# Time-Series Insights API Study

**A notebook-based exploration of Google's TimeSeries Insights API.**

The repository contains a time-series anomaly-detection notebook, a JSON data artifact, and saved illustrations. The previous README listed several unrelated Google Cloud API examples; this guide describes the files actually present here.

## Repository contents

| File | Purpose |
| --- | --- |
| `01-01-realtime-anomaly-detection-using-timeseries-insights-api.ipynb` | Main notebook |
| `timeseries-anomaly.json` | Time-series data artifact used by the study |
| `api_generated_timeseries.png` | Saved illustration |
| `appending_new_event.png` | Saved event-append illustration |
| `timeseries_json.png`, `timeseries_tabular.png` | Data representation illustrations |

## Inspect the study

```bash
git clone https://github.com/Vijay-glitch495/Time-series-anomaly-detection.git
cd Time-series-anomaly-detection
```

Open the notebook in Jupyter or a compatible notebook viewer. Review its setup cells, data provenance, API calls, and outputs before running it. Execution requires a suitable Google Cloud project and credentials; verify current service availability and billing requirements in official Google Cloud documentation. Do not commit credentials.

## Scope and outcomes

The repository's outcome is a notebook and saved demonstration artifacts. It does not establish a continuously running monitoring service, measured production latency, or independently validated anomaly-detection accuracy. A fresh cloud execution was not performed during this documentation update.

Before using the study in a research result or a production setting, document the dataset source, event timestamps, anomaly labels, evaluation protocol, and service configuration. Preserve applicable notebook/data attribution and the existing [LICENSE](LICENSE).
