# ICT Macro Windows

A clean, customizable TradingView Pine Script (v6) indicator that highlights Inner Circle Trader (ICT) macro windows directly on intraday charts.

---

## Features

- **4 Independent Macro Windows**: Pre-configured for London, NY AM, NY PM, and a Custom window.
- **Visual Customization**:
  - Box mode: Dynamic High–Low of the macro or full chart height.
  - Border styles (Solid, Dashed, Dotted, None) and independent fill transparency.
  - Optional full background shading per window.
- **Dynamic Labels**: Displays window name and local macro start/end times with customizable positioning (top/bottom) and font size.
- **Timezone Support**: Quick presets (`America/New_York`, `Asia/Kolkata`, `Europe/London`, `UTC`) or any custom IANA timezone.
- **Day Filters**: Toggle individual days of the week (Mon–Sun) for each window.
- **Alerts**: Includes both static `alertcondition()` triggers and dynamic alerts specifying the window name, time, and timezone.
- **Timeframe Guard**: Alerts you on-chart if used outside recommended intraday timeframes (1m to 15m).

---

## Installation

1. Open [TradingView](https://www.tradingview.com) and open any intraday chart (e.g., 1m, 3m, 5m).
2. Click on **Pine Editor** at the bottom of the screen.
3. Open [`ict_macros.pine`](ict_macros.pine), copy all code, and paste it into the editor.
4. Click **Save** and then click **Add to chart**.

---

## Quick Settings Overview

| Section | Key Settings | Description |
| --- | --- | --- |
| **General** | Timezone, Max macros to keep, Label size & color | Sets global timezone, maximum retained drawings (FIFO), and default label styling. |
| **Window 1 (London)** | Enabled, Name, Session time, Days active, Colors | Defaults to London session with customizable box and border styles. |
| **Window 2 (NY AM)** | Enabled, Name, Session time, Days active, Colors | Defaults to NY Morning session. |
| **Window 3 (NY PM)** | Enabled, Name, Session time, Days active, Colors | Defaults to NY Afternoon session. |
| **Window 4 (Custom)** | Enabled, Name, Session time, Days active, Colors | Fully customizable extra window. |

---

## License

This project is licensed under the [Mozilla Public License 2.0](LICENSE).
