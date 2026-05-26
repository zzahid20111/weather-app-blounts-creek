# Blounts Creek Weather Watch

A free, TV-friendly marine/weather dashboard for the Blounts Creek / 27817 area.

The app is a static website: one HTML file, no backend, no database, and no paid API keys.

## What it shows

- Next 12 hours from the National Weather Service hourly forecast
- Wind and gust risk
- Rain and thunderstorm probability
- Active NWS alerts
- NWS marine forecast for AMZ136, Pamlico and Pungo Rivers
- NOAA Bayview / Pamlico River water-level context
- USGS Pamlico River at Washington gage-height context
- Broad Pamlico Sound wave model guidance
- Official links for manual verification

## Free deployment with GitHub Pages

1. Open this repo in GitHub.
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Set branch to `main`.
5. Set folder to `/root`.
6. Save.

The site should publish at:

```text
https://zzahid20111.github.io/weather-app-blounts-creek/
```

GitHub Pages may take a few minutes to publish after the first setup.

## TV use

Open the published URL in the smart TV browser and bookmark it. The page auto-refreshes every 10 minutes.

## Security / privacy

This app intentionally does not include secrets or credentials. It uses public APIs directly from the browser and only labels the area broadly as Blounts Creek / 27817.

Do not commit private information, exact home address, private camera URLs, tokens, or API keys to this public repository.

See `SECURITY.md` for more detail.

## Important safety note

This is decision-support only. For severe weather, flooding, boating, or evacuation decisions, follow National Weather Service alerts, local emergency management, and official marine advisories.
