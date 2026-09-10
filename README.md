# UKOIL 15m OHLCV Commodities Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-357_278_rows-blue)](https://getdata.finance/datasets/ukoil) [![Updated](https://img.shields.io/badge/weekly_update-every_Saturday_8am_UTC-green)](https://getdata.finance) [![Full data on getdata.finance](https://img.shields.io/badge/download-getdata.finance-orange)](https://getdata.finance/datasets/ukoil)

### -> [**Download the full UKOIL dataset on getdata.finance**](https://getdata.finance/datasets/ukoil)

**UKOIL 15m OHLCV commodities historical data** — ultra high-quality 15m OHLCV for **Brent Crude Oil**. Clean `datetime, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

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

- **Ultra high-quality 15m OHLCV** for **Brent Crude Oil** (Commodities)
- **Clean CSV schema** — `datetime, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`15m`) · **11 timeframes** on [getdata.finance](https://getdata.finance/datasets/ukoil) · **357,278** `15m` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [getdata.finance](https://getdata.finance) every **Saturday, 8am UTC+0**; GitHub `15m` sample updated in sync

> **Sample on GitHub** · `UKOIL_15m.csv` (10,776 rows, `2026-03-10` -> `2026-09-09`, 959.48 KB). **Full archive on [getdata.finance](https://getdata.finance/datasets/ukoil)** — **357,278** `15m` rows (full `1m`: 5,228,763), **11 timeframes**, `2010-02-01` -> `2026-09-09`.

## Download sample

**[UKOIL_15m.csv](https://github.com/getdata-finance/ukoil-15m-ohlcv-commodities-historical-data/blob/main/UKOIL_15m.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/getdata-finance/ukoil-15m-ohlcv-commodities-historical-data/main/UKOIL_15m.csv)) · [GitHub Releases](https://github.com/getdata-finance/ukoil-15m-ohlcv-commodities-historical-data/releases)

## GitHub Pages

Interactive chart & stats: **[https://getdata-finance.github.io/ukoil-15m-ohlcv-commodities-historical-data/](https://getdata-finance.github.io/ukoil-15m-ohlcv-commodities-historical-data/)**

Full archive & live chart on getdata.finance: **[https://getdata.finance/datasets/ukoil](https://getdata.finance/datasets/ukoil)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([getdata.finance](https://getdata.finance/datasets/ukoil))** |
|---|--:|---|
| Instrument | Brent Crude Oil · Commodities | Brent Crude Oil · Commodities |
| Timeframes | `15m` (sample) | **11** — 1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W |
| 15m rows | 10,776 | **357,278** |
| Size | 959.48 KB | full ZIP on [getdata.finance](https://getdata.finance/datasets/ukoil) |
| Period | `2026-03-10` -> `2026-09-09` | `2010-02-01` -> `2026-09-09` |
| File | `UKOIL_15m.csv` | ZIP on [getdata.finance](https://getdata.finance/datasets/ukoil) |
| Coverage report | — | [UKOIL coverage](https://getdata.finance/coverage/ukoil) |
| Updates | Weekly (Saturday, 8am UTC+0) — GitHub sample | Weekly (Saturday, 8am UTC+0) — all timeframes |

## Timeframes on GetData

This GitHub repository ships a **`15m` evaluation sample** only. On **[getdata.finance](https://getdata.finance/datasets/ukoil)**, each full asset archive is delivered as a ZIP with **11 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W**

GitHub = `15m` sample · [getdata.finance](https://getdata.finance/datasets/ukoil) = all **11** timeframes above for the same instrument.

## Weekly updates

- **[getdata.finance](https://getdata.finance)** — Full datasets are updated every Saturday, 8am UTC+0.
- **GitHub (this repo)** — GitHub samples are refreshed weekly (every Saturday, 8am UTC+0), in sync with getdata.finance.

When a new `15m` sample is published on GitHub, the README, chart preview and CSV reflect the latest week of data.

## Data preview

First and latest rows from the GitHub sample **`UKOIL_15m.csv`**:

**First rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-03-10T18:45:00+00:00 | 88.66 | 89.14 | 87.88 | 88.34 | 8139 |
| 2026-03-10T19:00:00+00:00 | 88.34 | 89.22 | 88.214 | 88.899 | 5719 |
| 2026-03-10T19:15:00+00:00 | 88.899 | 91.01 | 88.88 | 90.888 | 9340 |
| 2026-03-10T19:30:00+00:00 | 90.888 | 91.299 | 89.228 | 90.459 | 9773 |
| 2026-03-10T19:45:00+00:00 | 90.459 | 91.318 | 90.458 | 90.9 | 6402 |

**Last rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-09-09T01:00:00+00:00 | 99.289 | 99.53 | 99.205 | 99.29 | 4039 |
| 2026-09-09T01:15:00+00:00 | 99.29 | 99.406 | 99.154 | 99.389 | 2962 |
| 2026-09-09T01:30:00+00:00 | 99.389 | 99.471 | 99.284 | 99.296 | 2172 |
| 2026-09-09T01:45:00+00:00 | 99.296 | 99.331 | 99.199 | 99.27 | 2369 |
| 2026-09-09T02:00:00+00:00 | 99.27 | 99.295 | 99.251 | 99.285 | 242 |

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

df = pd.read_csv('UKOIL_15m.csv', parse_dates=['datetime'])
df.set_index('datetime', inplace=True)
print(df.describe())
```

### backtrader

```python
import backtrader as bt
import pandas as pd

df = pd.read_csv('UKOIL_15m.csv', parse_dates=['datetime'])
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

df = pd.read_csv('UKOIL_15m.csv', parse_dates=['datetime'])
close = df.set_index('datetime')['close']
fast, slow = vbt.MA.run(close, 10), vbt.MA.run(close, 50)
entries = fast.ma_crossed_above(slow)
exits = fast.ma_crossed_below(slow)
pf = vbt.Portfolio.from_signals(close, entries, exits, init_cash=10_000, freq='15min')
print(pf.stats())
```

## Download full data

The complete **UKOIL** archive on **[getdata.finance](https://getdata.finance/datasets/ukoil)** includes **11 OHLCV timeframes** (1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W) — **357,278** rows at `15m`, plus all other timeframes in the same ZIP.

**[-> Get the full UKOIL dataset on getdata.finance](https://getdata.finance/datasets/ukoil)**

---
*GetData · UKOIL 15m OHLCV sample on GitHub · Full historical data on [getdata.finance](https://getdata.finance/datasets/ukoil)*
