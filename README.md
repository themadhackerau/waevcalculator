# Synergy EV Plan Comparison

Interactive comparison tool for Synergy (WA) residential electricity plans — optimised for electric vehicle charging.

## What it does

Models your exact EV charging costs across Synergy's three residential plans:

- **Home Plan (A1)** — flat rate
- **Midday Saver** — time-of-use
- **EV Add-On** — TOU with overnight EV window

Adjustable sliders for:
- EV consumption (kWh/100km)
- Annual distance (km)
- Charging pattern (Super Off-Peak / Overnight / 50-50 split / custom)

All rates are Synergy's confirmed 1 July 2025 tariffs (GST inclusive).

## Usage

Open `synergy-ev-plans.html` in any browser. No build step, no dependencies (Chart.js loads from CDN).

## Rates

| Period | A1 | Midday Saver | EV Add-On |
|---|---|---|---|
| Super Off-Peak (9am–3pm) | 32.37c | 8.62c | 8.62c |
| Off-Peak (9pm–9am) | 32.37c | 23.69c | 23.69c (6–9am, 9–11pm) |
| Overnight (11pm–6am) | 32.37c | — | 19.38c |
| Peak (3pm–9pm) | 32.37c | 53.84c | 53.84c |
| Supply charge | 116.05c/day | 129.23c/day | 129.23c/day |

## License

MIT