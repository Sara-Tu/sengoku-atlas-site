# Sengoku Atlas — built site

<https://sara-tu.github.io/sengoku-atlas-site/>

**This repository holds generated output only.** Every file here except this README is
the result of `npm run build` in a separate, private source repository. Nothing here is
edited by hand, so a pull request against it would be overwritten by the next release.

An interactive map of Sengoku-period Japan: which house held which province between
1560 and 1582, the castles and battles of those years, and the sources behind each claim.

## Sources and licences

The site carries its own attribution page — the **出處** tab, also reachable from the
「完整出處」 link in the map's bottom-right corner. It lists, per file, the artists and
licences of the eight house crests, plus the province boundary data (CODH / ROIS-DS,
CC BY-NC 4.0), the base map tiles (国土地理院), Wikidata, the seven ja.wikipedia articles
used for castle coordinates, and the copyright notices of Leaflet and topojson-client.

This is a non-commercial project, as the CC BY-NC 4.0 boundary data requires. Modified
SVGs are released under the same licence as the originals.

## Not indexed

`robots.txt` disallows crawling and the page carries `noindex`. The site is reachable by
anyone with the link, but is not meant to be found through a search engine.
