# Trackman Distance Calculator

A mobile-friendly golf distance calculator that adjusts yardage for elevation, wind, and lie conditions.

**Live:** [nrtattrie.github.io/trackman](https://nrtattrie.github.io/trackman)

## Features

- **Elevation adjustment** — enter height differential in feet/inches (uphill/downhill)
- **Lie presets** — Fairway, Light Rough, Heavy Rough, FW Bunker, GS Bunker with distance and spin % indicators
- **Wind compass** — select direction and speed; headwind/tailwind/crosswind factored into aim distance
- **Instant result** — shows an "aim for" yardage range updated in real time

## How It Works

The calculator takes your true distance to the pin and adjusts for:

1. **Elevation:** +1 yard per 3 feet of height change
2. **Lie:** divides by the lie's distance % (e.g. heavy rough at 86% means aim further)
3. **Wind:** headwind adds ~1 yd/mph, tailwind subtracts ~0.5 yd/mph, diagonal winds use the head/tail component

Result is displayed as a +/- 2 yard range.

## Usage

Open the link on any phone or desktop browser. Enter distance, select conditions, and read the aim yardage.
