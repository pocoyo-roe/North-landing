# North Landing Sauna Designer

A browser-based design tool for planning a sauna at North Landing, Flamborough (East Riding of Yorkshire): decking, steps, a cold plunge, an outdoor shower and the mains water, drain and power runs that feed them.

Open `index.html` in any modern browser. Nothing to install; designs autosave in the browser and can be exported/imported as JSON.

## What it does

- **Plan editor** (metres, 50 mm snap): add decks, cabin or barrel saunas, steps, round or rectangular plunge tubs, shower, benches, changing hut, log store and paving. Drag to move, corner handles to resize, round handle to rotate. Moving a deck carries what's on it.
- **Ground model**: set the slope and the direction it falls. Contours show on the plan, and every height (deck above ground, step rise, plunge rim) is measured from it.
- **Steps calculator**: steps size themselves to the rise from the ground to the deck they meet. Checks riser, going and 2R+G against Part K (private) or Parts K & M (public/commercial), and says how many handrails you need.
- **Decking take-off**: boards, joists, bearers, ground screws, fixings, and the length of edge that needs a 1100 mm guard (drawn in orange on the plan and modelled in 3D).
- **Services**: draw mains water, drain and power runs. Lengths feed the cost schedule. The Water tab works out plunge volume, fill time and annual water use.
- **3D view** with sun shadows for any date and time at the site's latitude.
- **Costs**: an editable, indicative budget with contingency. Copy it out as CSV.
- **Checks**: site-specific issues to brief your designer, Building Control, Yorkshire Water and the planners. Covers guarding, steps, backflow protection for a mains-fed plunge (fluid category 5), pipe cover, plunge water disposal, wood-stove fire safety, wind and salt exposure, and the Heritage Coast / SSSI / SAC / SPA designations around Flamborough Head.
- **Map underlay**: satellite imagery (Esri) or OpenStreetMap, drawn to the same scale as the plan and centred on the site's latitude/longitude (default: North Landing car park, OS grid TA 23868 71935). Use **Move map under design** in the Site tab to slide the real spot under your layout, or switch it with the Map button on the plan. Your browser fetches the tiles, so this needs an internet connection. The Claude artifact viewer blocks external images, so open `index.html` in a normal browser to see the map.
- **Site photo underlay**: load an aerial screenshot or survey, or paste a screenshot with Ctrl+V / ⌘V, then use Measure / calibrate on a known length to scale it.

Prices and regulatory notes are guidance for early design. Confirm them with suppliers, Building Control, Yorkshire Water, East Riding of Yorkshire Council and Natural England.
