# USDJPY 1d OHLCV Forex Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-521_rows-blue)](https://ork.ad/) [![Updated](https://img.shields.io/badge/weekly_update-every_Sunday-green)](https://ork.ad/) [![Full data on ork.ad](https://img.shields.io/badge/download-ork.ad-orange)](https://ork.ad/)

### → [**Download the full USDJPY dataset on ork.ad**](https://ork.ad/)

**USDJPY 1d OHLCV Forex historical data** — ultra high-quality 1d OHLCV for **US Dollar / Japanese Yen**. 24/5 FX liquidity with Asian, European and US sessions — not limited to US market hours. Clean `time, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

## Table of contents

- [Why this dataset?](#why-this-dataset)
- [Download sample CSV](#download-sample)
- [GitHub Pages preview](#github-pages)
- [Sample vs full dataset](#sample-vs-full-dataset)
- [Timeframes on ork.ad](#timeframes-on-orkad)
- [Weekly updates](#weekly-updates)
- [Data preview](#data-preview)
- [Schema](#schema)
- [Code examples](#code-examples)
- [Download full data on ork.ad](#download-full-data)

## Why this dataset?

- **Ultra high-quality 1d OHLCV** for **US Dollar / Japanese Yen** (Forex)
- **24/5 FX liquidity with Asian, European and US sessions — not limited to US market hours**
- **Clean CSV schema** — `time, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`1d`) · **13 timeframes** on [ork.ad](https://ork.ad/) · **521** `1d` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [ork.ad](https://ork.ad/) every **Sunday**; GitHub `1d` sample updated in sync

> **Sample on GitHub** · `USDJPY_1d.csv` (622 rows, `2024-07-02` → `2026-07-02`). **Full archive on [ork.ad](https://ork.ad/)** — **521** `1d` rows (~0.04 MB), **13 timeframes** (``1m`, `3m`, `5m`, `15m`, `30m`, `1H`, `2H`, `4H`, `8H`, `12H`, `16H`, `1D`, `1W``), `2024-10-28` → `2026-07-02`.

## Download sample

**[USDJPY_1d.csv](https://github.com/ork-ad/usdjpy-1d-ohlcv-forex-historical-data/blob/main/USDJPY_1d.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/ork-ad/usdjpy-1d-ohlcv-forex-historical-data/main/USDJPY_1d.csv)) · [GitHub Releases](https://github.com/ork-ad/usdjpy-1d-ohlcv-forex-historical-data/releases) when the release workflow is active.

## GitHub Pages

Interactive chart & stats: **[https://ork-ad.github.io/usdjpy-1d-ohlcv-forex-historical-data/](https://ork-ad.github.io/usdjpy-1d-ohlcv-forex-historical-data/)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([ork.ad](https://ork.ad/))** |
|---|--:|---|
| Instrument | US Dollar / Japanese Yen · Forex | US Dollar / Japanese Yen · Forex |
| Timeframes | `1d` (sample) | **13** — `1m`, `3m`, `5m`, `15m`, `30m`, `1H`, `2H`, `4H`, `8H`, `12H`, `16H`, `1D`, `1W` |
| 1d rows | 622 | **521** |
| Size | 0.04 MB | ~0.04 MB |
| Period | `2024-07-02` → `2026-07-02` | `2024-10-28` → `2026-07-02` |
| File | `USDJPY_1d.csv` | ZIP on [ork.ad](https://ork.ad/) |
| Updates | Weekly (Sunday) — GitHub sample | Weekly (Sunday) — all timeframes |

## Timeframes on ork.ad

This GitHub repository ships a **`1d` evaluation sample** only. On **[ork.ad](https://ork.ad/)**, each full asset archive is delivered as a ZIP with **13 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m** · **3m** · **5m** · **15m** · **30m** · **1H** · **2H** · **4H** · **8H** · **12H** · **16H** · **1D** · **1W**

GitHub = `1d` sample · [ork.ad](https://ork.ad/) = all **13** timeframes above for the same instrument.

## Weekly updates

- **[ork.ad](https://ork.ad/)** — Full datasets on ork.ad are updated every Sunday.
- **GitHub (this repo)** — GitHub samples are refreshed weekly (every Sunday), in sync with ork.ad.

When a new `1d` sample is published on GitHub, the README, chart preview and CSV reflect the latest week of data.

## Data preview

First and latest rows from the GitHub sample **`USDJPY_1d.csv`**:

**First rows**

| time | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2024-07-02T00:00:00Z | 161.5156 | 161.7486 | 161.2716 | 161.4916 | 193484.0 |
| 2024-07-03T00:00:00Z | 161.4916 | 161.9546 | 160.7696 | 161.5882317161585 | 235271.0 |
| 2024-07-04T00:00:00Z | 161.5882317161585 | 161.6056 | 160.9462188760943 | 161.3616 | 160094.0 |
| 2024-07-05T00:00:00Z | 161.3616 | 161.39722789613938 | 160.3322065960329 | 160.762 | 300945.0 |
| 2024-07-07T00:00:00Z | 160.7506 | 160.8176 | 160.5772114960574 | 160.64121277606378 | 11209.0 |

**Last rows**

| time | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| time | open | high | low | close | volume |
| 2026-06-28T00:00:00Z | 161.702 | 161.862 | 161.697 | 161.787 | 4604.0 |
| 2026-06-29T00:00:00Z | 161.787 | 161.974 | 161.713 | 161.917 | 103940.0 |
| 2026-06-30T00:00:00Z | 161.917 | 162.665 | 161.914 | 162.627 | 175489.0 |
| 2026-07-01T00:00:00Z | 162.627 | 162.831 | 162.289 | 162.543 | 150297.0 |

## Schema

```text
time,open,high,low,close,volume
```

## Code examples

### pandas

```python
import pandas as pd

df = pd.read_csv('USDJPY_1d.csv', parse_dates=['time'])
df.set_index('time', inplace=True)
print(df.describe())
print(df.resample('1D').agg({'open': 'first', 'high': 'max',
                              'low': 'min', 'close': 'last', 'volume': 'sum'}).head())
```

### backtrader

```python
import backtrader as bt
import pandas as pd

df = pd.read_csv('USDJPY_1d.csv', parse_dates=['time'])
df.set_index('time', inplace=True)

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

df = pd.read_csv('USDJPY_1d.csv', parse_dates=['time'])
close = df.set_index('time')['close']
fast, slow = vbt.MA.run(close, 10), vbt.MA.run(close, 50)
entries = fast.ma_crossed_above(slow)
exits = fast.ma_crossed_below(slow)
pf = vbt.Portfolio.from_signals(close, entries, exits, init_cash=10_000, freq='1D')
print(pf.stats())
```

## Download full data

The complete **USDJPY** archive on **[ork.ad](https://ork.ad/)** includes **13 OHLCV timeframes** (`1m`, `3m`, `5m`, `15m`, `30m`, `1H`, `2H`, `4H`, `8H`, `12H`, `16H`, `1D`, `1W`) — **521** rows at `1d`, plus all other timeframes in the same ZIP.

**[→ Get the full USDJPY dataset on ork.ad](https://ork.ad/)**

---
*GetData · USDJPY 1d OHLCV sample on GitHub · Full historical data on [ork.ad](https://ork.ad/) · 2026-07-04 UTC*