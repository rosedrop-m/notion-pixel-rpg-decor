# Prompt Recipes

Use these as adaptable scaffolds. Replace bracketed fields with the user's theme and keep only relevant details.

## Banner Prompt

```text
Use case: illustration-story
Asset type: Notion page cover banner, final crop 1500x600 (2.5:1)
Input image: [optional style reference only; preserve visual grammar without copying characters, creatures, logos, or map layout]
Primary request: [one specific scene from the themed journey]
Subject continuity: [recurring chibi characters, clothing, equipment, colors, and required prop count]
Style/medium: authentic retro 16-bit handheld JRPG overworld screenshot, top-down three-quarter view, tile-based map design, deliberately large visible square pixels, chunky pixel clusters, simplified game sprites, repeating environment tiles, crisp hard edges
Composition/framing: wide horizontal overworld map; principal sprites clearly readable within the central 55% horizontal and central 45% vertical safe zone; scenery continues to both edges; make main sprites slightly larger than ordinary map NPCs
Lighting/mood: bright, cheerful, wholesome adventure
Color palette: high-key limited palette using [theme colors], two or three shading levels per object, minimal dark colors
Constraints: no text, letters, logos, watermark, photorealism, gradients, anti-aliasing, soft painting, tiny high-resolution pixel details, dark cinematic grading, or unintended foreground characters
```

For a multi-banner journey, vary the environment and action while repeating the same `Subject continuity`, `Style/medium`, and `Color palette` lines verbatim.

## Icon Prompt

```text
Use case: stylized-concept
Asset type: Notion page icon, final 280x280 transparent PNG
Input image: [optional style reference only]
Primary request: [one simple page-category object]
Style/medium: authentic 16-bit handheld JRPG inventory item sprite, deliberately large visible square pixels, chunky pixel clusters, crisp hard edges, simple readable silhouette, two or three shading levels
Composition/framing: exactly one centered item sprite, front or slightly top-down view, fills about 68% of the square canvas, generous transparent padding
Color palette: bright high-key limited palette matching the banners — [theme colors], minimal dark outline
Background: genuinely transparent with clean alpha; no tile, circle, badge, or shadow panel
Constraints: no words, letters, numbers, logos, watermark, photorealism, gradients, anti-aliasing, soft painting, or tiny details
```

## Useful Style Shorthand

```text
Bright top-down 16-bit handheld JRPG tilemap, chunky large pixels, cute chibi character sprites, limited high-key game palette, crisp hard pixel edges, authentic retro adventure game screenshot.
```

Do not rely on shorthand alone for final generation. Include composition, continuity, palette, transparency, and negative constraints appropriate to the asset.
