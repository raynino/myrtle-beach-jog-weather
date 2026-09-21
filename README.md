# Myrtle Beach Jog Weather

A simple, single-file web app that helps you find the **best times to jog** in Myrtle Beach, SC (29577) over the next 7 days.

It pulls live hourly data from the **National Weather Service** (`api.weather.gov`) and scores each hour based on:

- Temperature (ideal ~60–75 °F)
- Relative humidity (lower is better)
- Probability of precipitation
- Preferred times of day (morning & evening)

## Features

- Summary cards: current conditions, best overall window, lowest humidity
- Day-by-day breakdown with morning & evening recommendations
- Lowest-humidity times listed for each day
- Air quality note + link to AirNow.gov
- Works as a local file or via GitHub Pages
- Refresh button + localStorage cache

## How to use

### Option 1 – Local file (recommended for privacy)
1. Download `index.html`
2. Double-click it or open it in any modern browser
3. It fetches live data directly from the NWS API

### Option 2 – Live URL
Once GitHub Pages is enabled on this repo, the app will be available at:

**https://raynino.github.io/myrtle-beach-jog-weather/**

## Data source
National Weather Service API – gridpoint ILM/57,47 (Myrtle Beach area).

No API key required. Please be respectful of the free public service.

---
Built for personal use in Myrtle Beach, SC.
