# GOOG 1m OHLCV US stocks Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-635_127_rows-blue)](https://getdata.finance/datasets/goog) [![Updated](https://img.shields.io/badge/weekly_update-every_Saturday_8am_UTC-green)](https://getdata.finance) [![Full data on getdata.finance](https://img.shields.io/badge/download-getdata.finance-orange)](https://getdata.finance/datasets/goog)

### -> [**Download the full GOOG dataset on getdata.finance**](https://getdata.finance/datasets/goog)

**GOOG 1m OHLCV stocks historical data** — ultra high-quality 1m OHLCV for **Alphabet**. Clean `time, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

## Table of contents

- [Why this dataset?](#why-this-dataset)
- [Download sample CSV](#download-sample)
- [Sample vs full dataset](#sample-vs-full-dataset)
- [Timeframes on GetData](#timeframes-on-getdata)
- [Weekly updates](#weekly-updates)
- [Data preview](#data-preview)
- [Schema](#schema)
- [Download full data on getdata.finance](#download-full-data-on-getdata)

## Why this dataset?

- **Ultra high-quality 1m OHLCV** for **Alphabet** (US stocks)
- **Clean CSV schema** — `time, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`1m`) · **11 timeframes** on [getdata.finance](https://getdata.finance/datasets/goog) · **635,127** `1m` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [getdata.finance](https://getdata.finance) every **Saturday, 8am UTC+0**; GitHub `1m` sample updated in sync

> **Sample on GitHub** · `GOOG_1m.csv` (55,440 rows, `2026-02-06` -> `2026-09-01`). **Full archive on [getdata.finance](https://getdata.finance/datasets/goog)** — **635,127** `1m` rows, **11 timeframes**, `2020-02-25` -> `2026-09-01`.

## Download sample

**[GOOG_1m.csv](https://github.com/getdata-finance/goog-1m-ohlcv-stocks-historical-data/blob/main/GOOG_1m.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/getdata-finance/goog-1m-ohlcv-stocks-historical-data/main/GOOG_1m.csv))

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([getdata.finance](https://getdata.finance/datasets/goog))** |
|---|--:|---|
| Instrument | Alphabet · US stocks | Alphabet · US stocks |
| Timeframes | `1m` (sample) | **11** — 1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W |
| 1m rows | 55,440 | **635,127** |
| Period | `2026-02-06` -> `2026-09-01` | `2020-02-25` -> `2026-09-01` |
| File | `GOOG_1m.csv` | ZIP on [getdata.finance](https://getdata.finance/datasets/goog) |
| Coverage report | — | [GOOG coverage](https://getdata.finance/coverage/goog) |
| Updates | Weekly (Saturday, 8am UTC+0) — GitHub sample | Weekly (Saturday, 8am UTC+0) — all timeframes |

## Timeframes on GetData

This GitHub repository ships a **`1m` evaluation sample** only. On **[getdata.finance](https://getdata.finance/datasets/goog)**, each full asset archive is delivered as a ZIP with **11 gap-free OHLCV timeframes**:

**1m** · **3m** · **5m** · **15m** · **30m** · **1H** · **4H** · **12H** · **1D** · **3D** · **1W**

## Weekly updates

- **[getdata.finance](https://getdata.finance)** — Full datasets updated every Saturday, 8am UTC+0.
- **GitHub (this repo)** — GitHub samples refreshed weekly, in sync with getdata.finance.

## Data preview

First and latest rows from the GitHub sample **`GOOG_1m.csv`**:

**First rows**

| time | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-02-06T20:00:00+00:00 | 321.78 | 321.83 | 321.64 | 321.7 | 201 |
| 2026-02-06T20:01:00+00:00 | 321.7 | 322.06 | 321.7 | 322.06 | 153 |
| 2026-02-06T20:02:00+00:00 | 322.06 | 322.22 | 322 | 322.16 | 106 |
| 2026-02-06T20:03:00+00:00 | 322.16 | 322.25 | 322.07 | 322.08 | 120 |
| 2026-02-06T20:04:00+00:00 | 322.08 | 322.15 | 321.93 | 321.98 | 114 |

**Last rows**

| time | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-09-01T19:55:00+00:00 | 331.49 | 331.73 | 331.39 | 331.43 | 237 |
| 2026-09-01T19:56:00+00:00 | 331.43 | 331.46 | 331.29 | 331.39 | 193 |
| 2026-09-01T19:57:00+00:00 | 331.39 | 331.43 | 331.22 | 331.25 | 281 |
| 2026-09-01T19:58:00+00:00 | 331.25 | 331.47 | 331.24 | 331.47 | 252 |
| 2026-09-01T19:59:00+00:00 | 331.47 | 331.78 | 331.4 | 331.61 | 353 |

## Schema

| Column | Description |
| --- | --- |
| `time` | Bar open timestamp (UTC, ISO-8601). |
| `open` | Opening price of the candlestick bar. |
| `high` | Highest price during the bar. |
| `low` | Lowest price during the bar. |
| `close` | Closing price of the candlestick bar. |
| `volume` | Tick volume (number of price updates) during the bar. |

```text
time,open,high,low,close,volume
```

## Download full data

Full GOOG archive — 11 timeframes, gap-free, updated weekly:

**[-> Get the full GOOG dataset on getdata.finance](https://getdata.finance/datasets/goog)**
