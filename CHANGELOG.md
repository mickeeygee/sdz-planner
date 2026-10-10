# Changelog

SDZ Planner is a planning aid, not an approved SDZ. Data comes from a draft revision of DA PAM 385-63.

## 2026-10-10 (later): Field-ready phone design

**Phone layout**
- One compact header row: range picker, rename button, new-range button and an amber DRAFT DATA badge.
- Weapon summary line and action buttons (Add, Undo, GPS, Share KML, More) sit directly under it, slightly shorter than before.
- Tabs (Weapon, Position, Aim, Ranges, Info) are now pills with a solid active state.
- The calculated values (Distance X, dispersion, ricochet) sit in one card.
- Landscape: the side panel is about 42% of the screen (was 50%), with a tighter header and tabs.

**Naming ranges**
- Tap the pencil beside the range picker to name a range (for example "North Lane" instead of "Range 2"). Press Enter when done.
- Tapping + to add a range opens the name box straight away.
- Names also appear on the map labels and in the KML.
- New unnamed ranges skip any "Range N" number already used.

**Map**
- Zoom, layers, my-location, fit and the scale bar have solid backings so they stay readable over bright or dark imagery.
- When a range has left and right limits of fire, each fan edge is labelled with its azimuth (for example 035°).

**Fixes**
- On a phone, tapping a field opened the keyboard, which made the screen shorter and flipped the app into the landscape side-panel layout. The app now ignores keyboard-caused resizes.

## 2026-10-10 (earlier): First public version

- 136 weapon entries from DA PAM 385-63 (draft): small arms, rockets, mortars, artillery, TOW, tank guns, demolition, non-lethal and C-RAM.
- Firing line with draggable end points, lat/lon or MGRS entry, azimuth and left/right limits of fire.
- Multiple ranges per project, with autosave and project save/open.
- KML export for Google Earth, and the phone share sheet.
- Live GPS dot and "use my location" for firing line ends.
- Back blast areas, and Light / Dark / Auto theme.

## Not built yet

Javelin, MLRS / GMLRS / Excalibur, helicopter and missile fires, and several figure-only items. Not yet tested on real phones in direct sun.
