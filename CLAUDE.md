# CLAUDE.md

## Project: DKSH Drone Mission Dashboard

Live drone mission dashboard — DKSH Bangna site.

- **Live:** https://cart-kart.github.io/DKSH-Drone-Dashboard/
- **Version:** V.1.0 DKSH
- **Main file:** index.html (single-file, all JS/CSS embedded)
- **Template base:** Cart-kart/Drone-Dashboard-Creator

## CI / Branding
- **Primary color:** `#C41230` (DKSH Red)
- **Background:** `#f8f8f8`
- **Logo:** `DKSH_hori_red_rgb.png`

## TODO — fill in before going live
1. `SITE_CONFIG.csvUrl` — published Google Sheet CSV URL
2. `SITE_CONFIG.gasProxyUrl` — GAS proxy exec URL
3. `SITE_CONFIG.batteries.active` — confirmed battery IDs
4. `SITE_CONFIG.drones.active` — drone names at DKSH site
5. `SITE_CONFIG.aisleMap` — aisle number to name mapping
6. `SITE_CONFIG.aislePrefixN/E` — aisle prefix letters
7. `SITE_CONFIG.columns` — verify column indices match DKSH form
8. `SITE_CONFIG.shifts` — adjust to DKSH actual shift hours
9. `SITE_CONFIG.pin` — set PIN before going live

## How to Start Each Session
1. `git pull`
2. Read SITE_CONFIG block in index.html — all TODOs are there
3. Fill in one section at a time as DKSH provides info
