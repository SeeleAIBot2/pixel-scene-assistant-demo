# Route A handoff — route_a_温暖村庄广场-白天-16-bit-治愈系-有喷泉和木屋

## What the user can do next
This package is meant for **production-next** work, not just review.

After receiving it, the user should be able to:
1. open the scene in **Tiled**
2. replace placeholder tiles with real assets from **Kenney Assets** or custom art
3. refine tiles / props / palette in **Pixelorama**
4. continue into Godot / Unity / other tile-based workflows

## Which file is for what
- `layout-preview.svg` — quickest visual understanding for human review
- `scene_brief.json` — prompt normalization / scene intent
- `layout_plan.json` — zones, flow, walkable logic
- `tile_theme_selection.json` — tiles/theme/module plan
- `scene_composition.json` — objects, structures, props
- `scene.tiled-project.tmj` — editable Tiled map export
- `tileset-placeholder.png` — immediate placeholder tileset to make the map open visibly
- `asset_source_manifest.json` — real external tool / asset hooks

## Minimum acceptance from the user's perspective
This package is only useful if the user can do at least two of these immediately:
- edit layout/path/blocking
- replace tileset/modules
- continue in Tiled / LDtk / Godot / Unity workflow
