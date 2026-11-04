# Blank template: build your own world

Fill in the CAPS blanks with any place: a hotel, a zoo, a shipyard, your own business. Paste it into Claude (Opus 5.5 gives the best first build). `talad/` was made from this template.

```
Build a single-file interactive web app (HTML, CSS and JS) using Three.js from a CDN: a live 3D [WHAT IT RUNS] dashboard called "[NAME]" that feels like a strategy game.

WORLD: a low-poly isometric [PLACE] built entirely in code, no external models. [8 TO 12 LANDMARKS, BUILDINGS AND VEHICLES]. Clean toy-like clay look, soft shadows, one accent colour ([HEX]) on [BACKGROUND].

LIFE: [THE MAIN LOOP, STEP BY STEP]. [OTHER THINGS THAT MOVE]. Everything gives way so nothing ever overlaps.

INTERACTION: drag to pan, right-drag to rotate, scroll or pinch to zoom. Click any [OBJECTS]: the camera glides to it and follows if it moves, a ring and label mark it, and a glass panel shows live stats. An area switcher flies between [4 TO 5 AREAS].

DASHBOARD: frosted glass panels: top bar (logo, search, area switcher, weather menu, live clock, alerts, day/night toggle, user), 3 KPI cards ([KPI 1], [KPI 2], [KPI 3]), a right detail panel, a bottom-left [PROCESS] tracker ([6 STEPS]) and a tabbed table ([3 TABS]). Realistic data: [UNITS].

EXTRAS: seasons ([4 WEATHER MODES]); animated day/night; works on mobile.
```

## Follow-ups that level it up
- "Add a cinematic mode where the camera slowly glides between the most interesting areas."
- "Some vehicles still overlap at junctions. Fix the give-way logic so they queue instead."
- "Make it run smoothly on a mid-range phone. Use instancing and cut draw calls."

Template and follow-ups from the free World Prompt Pack by [@sanjai.builds](https://www.instagram.com/sanjai.builds/).
