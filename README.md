# GOOG 1m OHLCV US stocks Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-1_194_537_rows-blue)](https://getdata.finance/datasets/goog) [![Updated](https://img.shields.io/badge/weekly_update-every_Saturday_8am_UTC-green)](https://getdata.finance) [![Full data on getdata.finance](https://img.shields.io/badge/download-getdata.finance-orange)](https://getdata.finance/datasets/goog)

### -> [**Download the full GOOG dataset on getdata.finance**](https://getdata.finance/datasets/goog)

**GOOG 1m OHLCV us stocks historical data** — ultra high-quality 1m OHLCV for **GOOG**. US equity cash and extended sessions — institutional-style OHLCV candles for US stocks. Clean `datetime, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

## Table of contents

- [Why this dataset?](#why-this-dataset)
- [Download sample CSV](#download-sample)
- [GitHub Pages preview](#github-pages)
- [Sample vs full dataset](#sample-vs-full-dataset)
- [Timeframes on GetData](#timeframes-on-getdata)
- [Weekly updates](#weekly-updates)
- [Data preview](#data-preview)
- [Schema](#schema)
- [Code examples](#code-examples)
- [Download full data on getdata.finance](#download-full-data-on-getdata)

## Why this dataset?

- **Ultra high-quality 1m OHLCV** for **GOOG** (US stocks)
- **US equity cash and extended sessions — institutional-style OHLCV candles for US stocks**
- **Clean CSV schema** — `datetime, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`1m`) · **9 timeframes** on [getdata.finance](https://getdata.finance/datasets/goog) · **1,194,537** `1m` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [getdata.finance](https://getdata.finance) every **Saturday, 8am UTC+0**; GitHub `1m` sample updated in sync

> **Sample on GitHub** · `GOOG_1m.csv` (48,750 rows, `2026-02-02` -> `2026-07-31`). **Full archive on [getdata.finance](https://getdata.finance/datasets/goog)** — **1,194,537** `1m` rows (~74.56 MB), **9 timeframes** (1m · 3m · 5m · 15m · 30m · 1H · 12H · 3D · 1W), `2011-05-09` -> `2026-07-29`.

## Download sample

**[GOOG_1m.csv](https://github.com/getdata-finance/goog-1m-ohlcv-stocks-historical-data/blob/main/GOOG_1m.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/getdata-finance/goog-1m-ohlcv-stocks-historical-data/main/GOOG_1m.csv)) · [GitHub Releases](https://github.com/getdata-finance/goog-1m-ohlcv-stocks-historical-data/releases)

## GitHub Pages

Interactive chart & stats: **[https://getdata-finance.github.io/goog-1m-ohlcv-stocks-historical-data/](https://getdata-finance.github.io/goog-1m-ohlcv-stocks-historical-data/)**

Full archive & live chart on getdata.finance: **[https://getdata.finance/datasets/goog](https://getdata.finance/datasets/goog)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([getdata.finance](https://getdata.finance/datasets/goog))** |
|---|--:|---|
| Instrument | GOOG · US stocks | GOOG · US stocks |
| Timeframes | `1m` (sample) | **9** — 1m · 3m · 5m · 15m · 30m · 1H · 12H · 3D · 1W |
| 1m rows | 48,750 | **1,194,537** |
| Size | 4.83 MB | ~74.56 MB |
| Period | `2026-02-02` -> `2026-07-31` | `2011-05-09` -> `2026-07-29` |
| File | `GOOG_1m.csv` | ZIP on [getdata.finance](https://getdata.finance/datasets/goog) |
| Coverage report | — | [GOOG coverage](https://getdata.finance/coverage/goog) |
| Updates | Weekly (Saturday, 8am UTC+0) — GitHub sample | Weekly (Saturday, 8am UTC+0) — all timeframes |

## Timeframes on GetData

This GitHub repository ships a **`1m` evaluation sample** only. On **[getdata.finance](https://getdata.finance/datasets/goog)**, each full asset archive is delivered as a ZIP with **9 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m** · **3m** · **5m** · **15m** · **30m** · **1H** · **12H** · **3D** · **1W**

GitHub = `1m` sample · [getdata.finance](https://getdata.finance/datasets/goog) = all **9** timeframes above for the same instrument.

## Weekly updates

- **[getdata.finance](https://getdata.finance)** — Full datasets are updated every Saturday, 8am UTC+0.
- **GitHub (this repo)** — GitHub samples are refreshed weekly (every Saturday, 8am UTC+0), in sync with getdata.finance.

When a new `1m` sample is published on GitHub, the README, chart preview and CSV reflect the latest week of data.

## Data preview

First and latest rows from the GitHub sample **`GOOG_1m.csv`**:

**First rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-02-02T14:30:00+00:00 | 336.15 | 336.15 | 333.38 | 334.46 | 546 |
| 2026-02-02T14:31:00+00:00 | 334.46 | 334.54 | 333.37 | 334.45 | 424 |
| 2026-02-02T14:32:00+00:00 | 334.45 | 335.34 | 333.62 | 334.8 | 339 |
| 2026-02-02T14:33:00+00:00 | 334.8 | 336.61 | 334.68 | 335.49 | 346 |
| 2026-02-02T14:34:00+00:00 | 335.49 | 336.45 | 335.38 | 336.32 | 280 |

**Last rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-07-31T19:55:00+00:00 | 361.06 | 361.06 | 359.76 | 360.45 | 606 |
| 2026-07-31T19:56:00+00:00 | 360.45 | 360.83 | 360.4 | 360.73 | 308 |
| 2026-07-31T19:57:00+00:00 | 360.73 | 361.02 | 360.08 | 360.08 | 439 |
| 2026-07-31T19:58:00+00:00 | 360.08 | 360.84 | 359.97 | 360.69 | 377 |
| 2026-07-31T19:59:00+00:00 | 360.69 | 360.73 | 359.25 | 360.05 | 464 |

## Schema

| Column | Description |
| --- | --- |
| `datetime` | Bar open timestamp (UTC, ISO-8601). |
| `open` | Opening price of the candlestick bar. |
| `high` | Highest price during the bar. |
| `low` | Lowest price during the bar. |
| `close` | Closing price of the candlestick bar. |
| `volume` | Tick volume (number of price updates) during the bar. |

```text
datetime,open,high,low,close,volume
```

## Code examples

### pandas

```python
import pandas as pd

df = pd.read_csv('GOOG_1m.csv', parse_dates=['datetime'])
df.set_index('datetime', inplace=True)
print(df.describe())
print(df.resample('1h').agg({'open': 'first', 'high': 'max',
                              'low': 'min', 'close': 'last', 'volume': 'sum'}).head())
```

### backtrader

```python
import backtrader as bt
import pandas as pd

df = pd.read_csv('GOOG_1m.csv', parse_dates=['datetime'])
df.set_index('datetime', inplace=True)

class PandasData(bt.feeds.PandasData):
    params = (('datetime', None), ('open', 'open'), ('high', 'high'),
              ('low', 'low'), ('close', 'close'), ('volume', 'volume'))

cerebro = bt.Cerebro()
cerebro.adddata(PandasData(dataname=df))
# cerebro.addstrategy(YourStrategy)
# cerebro.run()
```

### vectorbt

```python
import pandas as pd
import vectorbt as vbt

df = pd.read_csv('GOOG_1m.csv', parse_dates=['datetime'])
close = df.set_index('datetime')['close']
fast, slow = vbt.MA.run(close, 10), vbt.MA.run(close, 50)
entries = fast.ma_crossed_above(slow)
exits = fast.ma_crossed_below(slow)
pf = vbt.Portfolio.from_signals(close, entries, exits, init_cash=10_000, freq='1min')
print(pf.stats())
```

## Download full data

The complete **GOOG** archive on **[getdata.finance](https://getdata.finance/datasets/goog)** includes **9 OHLCV timeframes** (1m · 3m · 5m · 15m · 30m · 1H · 12H · 3D · 1W) — **1,194,537** rows at `1m`, plus all other timeframes in the same ZIP.

**[-> Get the full GOOG dataset on getdata.finance](https://getdata.finance/datasets/goog)**

---
*GetData · GOOG 1m OHLCV sample on GitHub · Full historical data on [getdata.finance](https://getdata.finance/datasets/goog) · 2026-08-04 UTC*
