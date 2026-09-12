# EUSTX50 1d OHLCV Index Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-3_573_rows-blue)](https://getdata.finance/datasets/eustx50) [![Updated](https://img.shields.io/badge/weekly_update-every_Saturday_8am_UTC-green)](https://getdata.finance) [![Full data on getdata.finance](https://img.shields.io/badge/download-getdata.finance-orange)](https://getdata.finance/datasets/eustx50)

### -> [**Download the full EUSTX50 dataset on getdata.finance**](https://getdata.finance/datasets/eustx50)

**EUSTX50 1d OHLCV index historical data** — ultra high-quality 1d OHLCV for **EURO STOXX 50**. Clean `datetime, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

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

- **Ultra high-quality 1d OHLCV** for **EURO STOXX 50** (Index)
- **Clean CSV schema** — `datetime, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`1d`) · **11 timeframes** on [getdata.finance](https://getdata.finance/datasets/eustx50) · **3,573** `1d` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [getdata.finance](https://getdata.finance) every **Saturday, 8am UTC+0**; GitHub `1d` sample updated in sync

> **Sample on GitHub** · `EUSTX50_1d.csv` (732 rows, `2023-10-24` -> `2026-09-11`, 63.47 KB). **Full archive on [getdata.finance](https://getdata.finance/datasets/eustx50)** — **3,573** `1d` rows (full `1m`: 2,770,438), **11 timeframes**, `2012-08-27` -> `2026-09-11`.

## Download sample

**[EUSTX50_1d.csv](https://github.com/getdata-finance/eustx50-1d-ohlcv-index-historical-data/blob/main/EUSTX50_1d.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/getdata-finance/eustx50-1d-ohlcv-index-historical-data/main/EUSTX50_1d.csv)) · [GitHub Releases](https://github.com/getdata-finance/eustx50-1d-ohlcv-index-historical-data/releases)

## GitHub Pages

Interactive chart & stats: **[https://getdata-finance.github.io/eustx50-1d-ohlcv-index-historical-data/](https://getdata-finance.github.io/eustx50-1d-ohlcv-index-historical-data/)**

Full archive & live chart on getdata.finance: **[https://getdata.finance/datasets/eustx50](https://getdata.finance/datasets/eustx50)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([getdata.finance](https://getdata.finance/datasets/eustx50))** |
|---|--:|---|
| Instrument | EURO STOXX 50 · Index | EURO STOXX 50 · Index |
| Timeframes | `1d` (sample) | **11** — 1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W |
| 1d rows | 732 | **3,573** |
| Size | 63.47 KB | full ZIP on [getdata.finance](https://getdata.finance/datasets/eustx50) |
| Period | `2023-10-24` -> `2026-09-11` | `2012-08-27` -> `2026-09-11` |
| File | `EUSTX50_1d.csv` | ZIP on [getdata.finance](https://getdata.finance/datasets/eustx50) |
| Coverage report | — | [EUSTX50 coverage](https://getdata.finance/coverage/eustx50) |
| Updates | Weekly (Saturday, 8am UTC+0) — GitHub sample | Weekly (Saturday, 8am UTC+0) — all timeframes |

## Timeframes on GetData

This GitHub repository ships a **`1d` evaluation sample** only. On **[getdata.finance](https://getdata.finance/datasets/eustx50)**, each full asset archive is delivered as a ZIP with **11 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W**

GitHub = `1d` sample · [getdata.finance](https://getdata.finance/datasets/eustx50) = all **11** timeframes above for the same instrument.

## Weekly updates

- **[getdata.finance](https://getdata.finance)** — Full datasets are updated every Saturday, 8am UTC+0.
- **GitHub (this repo)** — GitHub samples are refreshed weekly (every Saturday, 8am UTC+0), in sync with getdata.finance.

When a new `1d` sample is published on GitHub, the README, chart preview and CSV reflect the latest week of data.

## Data preview

First and latest rows from the GitHub sample **`EUSTX50_1d.csv`**:

**First rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2023-10-24T00:00:00+00:00 | 4054.945 | 4107.035 | 4054.945 | 4102.065 | 12285 |
| 2023-10-25T00:00:00+00:00 | 4102.065 | 4116.335 | 4071.315 | 4081.385 | 14118 |
| 2023-10-26T00:00:00+00:00 | 4081.385 | 4097.735 | 4046.715 | 4066.255 | 21583 |
| 2023-10-27T00:00:00+00:00 | 4066.255 | 4101.335 | 4019.315 | 4029.335 | 16570 |
| 2023-10-30T00:00:00+00:00 | 4029.335 | 4083.875 | 4029.335 | 4071.925 | 11854 |

**Last rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-09-07T00:00:00+00:00 | 6398.6 | 6408.76 | 6369.76 | 6396.78 | 8372 |
| 2026-09-08T00:00:00+00:00 | 6396.78 | 6417.18 | 6361.67 | 6375.72 | 16250 |
| 2026-09-09T00:00:00+00:00 | 6375.72 | 6384.55 | 6275.54 | 6299.11 | 18177 |
| 2026-09-10T00:00:00+00:00 | 6299.59 | 6329.98 | 6250.97 | 6258.04 | 24775 |
| 2026-09-11T00:00:00+00:00 | 6258.04 | 6342.26 | 6258.04 | 6320.3 | 19281 |

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

df = pd.read_csv('EUSTX50_1d.csv', parse_dates=['datetime'])
df.set_index('datetime', inplace=True)
print(df.describe())
```

### backtrader

```python
import backtrader as bt
import pandas as pd

df = pd.read_csv('EUSTX50_1d.csv', parse_dates=['datetime'])
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

df = pd.read_csv('EUSTX50_1d.csv', parse_dates=['datetime'])
close = df.set_index('datetime')['close']
fast, slow = vbt.MA.run(close, 10), vbt.MA.run(close, 50)
entries = fast.ma_crossed_above(slow)
exits = fast.ma_crossed_below(slow)
pf = vbt.Portfolio.from_signals(close, entries, exits, init_cash=10_000, freq='1d')
print(pf.stats())
```

## Download full data

The complete **EUSTX50** archive on **[getdata.finance](https://getdata.finance/datasets/eustx50)** includes **11 OHLCV timeframes** (1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W) — **3,573** rows at `1d`, plus all other timeframes in the same ZIP.

**[-> Get the full EUSTX50 dataset on getdata.finance](https://getdata.finance/datasets/eustx50)**

---
*GetData · EUSTX50 1d OHLCV sample on GitHub · Full historical data on [getdata.finance](https://getdata.finance/datasets/eustx50)*
