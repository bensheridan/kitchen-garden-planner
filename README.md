# Kitchen Garden Planner

A single-page planner for growing vegetables and herbs (basil, tomatoes, chillies, leafy greens) in a VIVOSUN VGrow smart grow box, instead of the cannabis-style stages the stock app assumes.

## What it does

- **Set your VGrow to**: light schedule and level, duct and circulation fan settings, and (for coco) drip targets, worked out from what's growing. The values line up with the VIVOSUN app's plan editor, and a "Copy settings" button copies them as a list.
- **DWC or coco**: pH, EC, water temperature or daily watering for the current setup, plus a reservoir-change or tank-refill reminder.
- **Plants in the box**: each plant's day count, stage, progress to harvest and to-dos.
- **Plant library**: 21 herbs, leafy greens and fruiting plants with per-stage light, intensity and EC, plus your own custom plants.
- **Water log**: pH, EC and water temperature readings with in-range checks, advice and trend charts.

## Running it

Open `index.html` in a browser. There's no build step and no dependencies beyond Google Fonts.

Data is stored in the browser's `localStorage`. When the page runs as a claude.ai artifact it uses the artifact's per-user database instead, so plants and readings follow you between devices.

## Notes

Growing figures are typical hydroponic ranges for a 100 W full-spectrum LED box (46 × 46 cm, about 92 cm grow height). Your nutrient's own dosing chart comes first.

This project doesn't talk to VIVOSUN's servers or the grow box. Enter the settings in the VIVOSUN app yourself.
