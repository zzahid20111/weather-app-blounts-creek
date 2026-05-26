# Security Notes

This project is intentionally designed as a static, read-only weather dashboard.

## What is intentionally not included

- No API keys
- No passwords
- No server-side code
- No database
- No user accounts
- No payment or billing configuration
- No public write-capable endpoints
- No exact home address

## Data sources

The dashboard fetches public weather and water data directly from official/public APIs in the browser:

- National Weather Service API
- NOAA Tides and Currents API
- USGS Water Services
- Open-Meteo Marine API

## Public repo warning

This repository is public. Do not commit secrets, tokens, private addresses, private camera URLs, or personal credentials.

## Recommended GitHub settings

For better protection:

1. Go to Settings → Branches.
2. Add a branch protection rule for `main`.
3. Enable pull request review before merging.
4. Block force pushes.
5. Block branch deletion.

## Safety disclaimer

This app is decision-support only. For severe weather, flooding, evacuation, and boating decisions, rely on National Weather Service alerts, local emergency management, and official marine advisories.
