---
name: notion-pixel-rpg-decor
description: Create cohesive Notion page-cover and icon sets in a bright, chunky 16-bit handheld JRPG overworld style. Use when a user wants themed Notion decoration with top-down tilemaps, chibi sprites, large visible pixels, or matching game-inventory icons. Do not use for generic pixel art that is not intended as a coordinated Notion asset set.
---

# Notion Pixel RPG Decor

Create a coordinated Notion decoration kit that looks like one real retro handheld RPG rather than unrelated pixel illustrations.

## Default Deliverable

Unless the user specifies otherwise, produce:

- 5 page-cover banners as 1500 × 600 PNG files.
- 10 page icons as 280 × 280 transparent PNG files.
- One icon contact sheet for review.
- A short Markdown manifest mapping filenames to suggested page uses.
- A ZIP containing the final assets.

Place project-bound deliverables in the workspace output directory. Do not leave final assets only in an image generator's default storage.

## Visual Language

Treat these as invariants unless the user overrides them:

- Top-down or three-quarter top-down 2D overworld view.
- Tile-based map construction with repeated grass, path, water, hedge, tree, fence, flower, or building tiles.
- Deliberately large square pixels and chunky pixel clusters.
- Cute 2-to-3-head-tall chibi character sprites with readable silhouettes.
- Bright, high-key, limited palette with only two or three shading levels per object.
- Crisp hard edges and nearest-neighbor appearance.
- Simple game sprites rather than detailed anime illustration or painterly concept art.
- No anti-aliasing, soft focus, photorealism, smooth vector edges, tiny high-resolution pixel details, or dark cinematic grading.

When a reference image is supplied, use it only as a style reference. Preserve its visual grammar without copying characters, creatures, logos, map layouts, or other protected identity elements.

## Banner Design

- Build each banner as a playable-looking overworld scene, not a conventional cinematic landscape.
- Keep the principal character sprites and important props inside the central 55–60% horizontally and central 45% vertically because Notion crops covers responsively.
- Extend decorative tilemap scenery to both edges.
- Make primary sprites slightly larger than ordinary map NPCs so they remain legible in a shallow banner.
- Maintain recurring character clothing, equipment, and palette across the series when the banners tell a continuous story.
- Avoid embedded text, logos, and UI frames.

## Icon Design

- Treat icons as inventory-item sprites from the same game.
- Use one centered object with a simple silhouette and generous transparent padding.
- Fill roughly 65–72% of the square canvas.
- Keep color count and shading limited; preserve visible pixel blocks.
- Use a genuinely transparent background with clean alpha. Do not add a badge, tile, circle, shadow panel, or decorative scene unless requested.
- Prefer objects that remain recognizable at 24–32 px.

## Workflow

1. Infer a coherent theme, palette, recurring characters, and page categories from the request. Ask only when a missing choice would materially change the result.
2. If the user provides a visual reference, inspect it and describe the style in neutral visual terms before generation when requested.
3. Read [references/prompt-recipes.md](references/prompt-recipes.md) before generating assets.
4. Generate each distinct banner and icon with a separate prompt. Use the built-in image-generation path unless the user explicitly requests another method.
5. Inspect outputs for subject accuracy, continuity, legibility, large-pixel treatment, bright palette, and clean transparency.
6. Crop banners centrally to 2.5:1 and resize to 1500 × 600. Resize icons to 280 × 280 while preserving alpha. Use nearest-neighbor resizing when it better preserves chunky pixels.
7. Verify every icon has an alpha range containing both transparent and opaque pixels. Confirm all final dimensions.
8. Create a contact sheet, manifest, and ZIP, then report the final paths and summarize the prompt family used.

## Quality Bar

Regenerate or correct an asset when any of these occur:

- It looks like a smooth digital illustration with a pixel filter.
- Character proportions are not chibi or differ substantially across a continuous set.
- Important subjects fall outside the Notion-safe central area.
- Icons have opaque backgrounds, excessive detail, illegible silhouettes, or inconsistent palettes.
- A banner contains text, trademarks, watermarks, or unintended extra foreground characters.
