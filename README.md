# WATCHCON desktop wallpaper

OSINT-style live wallpaper in one HTML file. It shows earthquakes (USGS), disaster alerts (GDACS),
exchange rates (ECB via Frankfurter) and weather (Open-Meteo), fetched once a day. No API keys, no tracking.

## Versions

| Version | Address | Made for |
|---|---|---|
| Default | https://wonwoowilliamkim.github.io/desktop-wallpaper-watchcon/ | Irvine home, Windows laptop in Lively Wallpaper |
| Seoul | https://wonwoowilliamkim.github.io/desktop-wallpaper-watchcon/?p=seoul | Seoul home, MacBook in Plash |

The version is picked by the `?p=` part of the address; the settings live in `PROFILES` near the top of the script in `index.html`.

## Mac setup (Plash)

1. Install **Plash** (free) from the Mac App Store. Older macOS versions can get an older build from https://sindresorhus.com/plash.
2. In Plash, add a website and paste the Seoul address above.
3. In Plash's settings, choose the display it shows on. No reload interval is needed: the page refreshes its own data once a day.
4. Outside Browsing Mode, clicks go through to the desktop. Turn on Browsing Mode to hover over the map (try the ♥).

If the Dock is set to hide automatically, or desktop icons sit under the panels, the layout numbers in the `seoul` profile (`--taskbar`, `--shell-top`, ...) can be adjusted.
