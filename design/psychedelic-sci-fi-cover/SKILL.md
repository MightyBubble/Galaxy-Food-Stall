---
name: psychedelic-sci-fi-cover
description: Generate food-planet or surreal game concept images using either 1970s psychedelic poster language or vintage paranoid science-fiction paperback cover language. Use when the user mentions 70s psychedelic art, psychedelic posters, Philip K. Dick-style novel covers, vintage sci-fi paperbacks, surreal food planets, or asks for skill-level image prompt rules in these directions.
---

# Psychedelic Sci-Fi Cover

## Router

Select one mode before generation:

- `seventies-psychedelic-poster`: use for hot 1970s psychedelic poster energy, liquid orbital forms, screenprint color separation, food planets, and playful cosmic abundance.
- `paranoid-sci-fi-paperback`: use for vintage speculative paperback cover energy associated with Philip K. Dick themes: unstable reality, artificial worlds, surveillance, identity fracture, banal objects made cosmic, and uneasy deadpan humor.
- `hybrid`: default production mix for Galaxy Food Stall. Use `paranoid-sci-fi-paperback` for **70%** (mood, staging, negative space, reality fracture, muted paper field) and `seventies-psychedelic-poster` for **30%** (local color heat, one liquid orbital band, organic edible contours). Do **not** invert this into poster-first. Read `../art-bible-hybrid-70-30.md` before generating planets, monsters, food props, or UI concepts.

Do not copy a specific book cover, illustrator, author portrait, publisher mark, title, or typography layout. Use broad era and genre language.

## Default Contract

- `ratio`: 16:9 unless the user requests another ratio.
- `subject`: one surreal food-planet game concept or an ordered set of distinct food planets.
- `composition`: one full-bleed concept image, not a UI screen, not a literal product mockup.
- `text`: no readable title, author name, publisher logo, labels, or fake UI unless explicitly requested. If a cover layout is requested, use abstract title blocks or short invented words only.
- `finish`: printed illustration, visible grain, ink registration error, paper aging, and deliberate poster/paperback flatness. Avoid glossy 3D and modern digital concept-art polish.

## Prompt Workflow

1. Lock the mode and ratio.
2. Lock the food roster and whether the image is one hero planet, many planets, or a cover-like tableau.
3. Read `visual-language.md` for the selected mode. If mode is `hybrid`, also read `../art-bible-hybrid-70-30.md`.
4. Compile a prompt using five compact parts:
   - scene and roster
   - composition and visual hierarchy
   - palette and print process
   - mode-specific symbols and mood
   - hard avoids
5. Generate one image first. Inspect once. Only make a targeted correction if a non-negotiable fails.

## Quality Gate

- The image reads as a designed 1970s print artifact or vintage speculative paperback, not a modern render with retro filters.
- Food planets remain recognizable as food and as planets.
- The composition has one clear poster/cover hierarchy instead of scattered stickers.
- Color is intentional: limited palette, strong contrast, no random rainbow mush.
- Printed texture is structural: halftone, screenprint edges, misregistration, paper grain, ink pooling, and aged stock are visible but do not obscure the subject.
- `paranoid-sci-fi-paperback` mode contains at least one reality-instability device: impossible scale, duplicated object logic, surveillance geometry, synthetic horizon, fractured room/planet relation, or a mundane object made cosmic.
- `hybrid` mode keeps paperback calm as the first read; psychedelic heat stays local; no full mandala / rainbow takeover; no CRT window UI language.
- No direct Philip K. Dick name, real book title, real cover recreation, publisher logo, watermark, unreadable text soup, glossy 3D, photoreal food macro, anime mascot, modern sci-fi HUD, or CRT window interface unless the user asks for it.

## Output

Return the generated image and saved path. If multiple directions are generated, clearly label the mode for each image.
