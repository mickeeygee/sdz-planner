# SDZ Planner

A browser tool for sketching small-arms, rocket, mortar, artillery, TOW, tank-gun and demolition **surface danger zones** (range fans) on a map and exporting them as KML for Google Earth.

**This is a planning aid. It is not an approved SDZ.** The numbers come from a *draft* revision of DA PAM 385-63 and have not been checked against the signed edition. Any SDZ used for live fire still needs approval from your range control / range safety office.

## Use it
Open the page, choose a weapon and ammunition, place a firing line on the map (click, type lat/lon or MGRS, or use GPS), set the direction and limits of fire, and download or share the KML.

- Works on a phone. GPS and the phone share sheet need the https address.
- Your ranges are saved in your own browser only. Nothing is sent to any server. (Map pictures load from Esri World Imagery and OpenStreetMap.)
- Azimuths are true north.

## What is and is not covered
Covered: chapters 4 to 10, 12, 14 and 15 of the pamphlet for the systems listed in the weapon menu. Not covered: Javelin, MLRS / GMLRS / Excalibur, helicopter and missile fires, and several figure-only items.

See [CHANGELOG.md](CHANGELOG.md) for what changed in each version.

Built with Leaflet (BSD-2-Clause) and polygon-clipping (MIT).
