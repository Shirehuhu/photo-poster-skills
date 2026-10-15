---
name: gc-minimal-zine-poster-v0-3
description: "Generate or analyze minimal paper-texture zine posters with large negative space, one small visual event, experimental editorial type and a clear color accent. Use for 极简杂志, photo-based posters, theme-to-image work, reference-system analysis or prompt-only requests."
---

# Minimal Zine Poster v0.3.1

Upstream: LiamGvchi/gc-minimal-zine-poster. Preserve LICENSE and the callable name.

Locally modified/condensed by Shirehuhu on 2026-10-14; see NOTICE for provenance. The original MIT license remains unchanged.

## Route and load

Choose the smallest requested mode:
- Generate (default): content/photo → one visual relation → recipe → prompt → raster → inspection.
- Photo Input: generation subflow when a supplied image affects the output.
- Reference Analysis: inspect actual references and extract rules; no generation unless requested.
- Prompt-only: only when explicitly requested; never imply an image was generated.
- Analyze + Generate: extract the reference system first, then create a new composition.

Read references/style-system.md for every mode; references/prompt-compiler.md and references/variation-engine.md for Generate/Prompt-only; references/reference-analysis.md for analysis; references/quality-gate.md before delivery. Load only applicable references.

## Photo contract

Inspect every image before describing its dimensions, ratios, subject, text or visual traits. Use metadata for exact size claims. Assign each image:
- edit target: its recognizable subject must appear;
- style reference: only requested grammar/color/material/mood, not exact identity, subject, wording or composition;
- supporting insert: one specified recognizable fragment/person/object.

“把这张照片做海报” or an attached photo plus “做一张” defaults to edit target. “参考风格/配色/构图” means style reference. Ask only if materially different roles remain equally plausible.

Record preservation:
- High: identity, facial structure, body proportions, relevant pose, markings, geometry/component count, silhouette and recognizable colors, except explicitly permitted changes. Default for identifiable people, pets, characters, artworks and products; prefer photographic/printed fragments over redrawing.
- Medium: main subject and defining features survive while crop/scale/palette/material/layout may change.
- Low: reference-only, not an excuse to discard an edit target.

List what must remain, what may change and what new elements are allowed. Pass the actual image to the built-in image editing tool, not only a textual description; consult imagegen for current reference-input mechanics. Naturally resolve color before treatment within the permitted preservation scope. Protect complete principal subjects rather than force them into an occupancy percentage.

Reference-only text, brands, watermarks, signatures, exact dates/locations and exact layouts are sample residue, not reusable content. User-supplied exact poster wording is allowed when requested. Report unreadable/missing files rather than inventing analysis. Do not archive or share private sources elsewhere.

## Generation

1. Reduce the content to one imageable relation/metaphor. Do not illustrate every point of an article or fill the canvas with a whole scene.
2. Choose a source-compatible recipe: layout, focal-element structure, typography, paper/material, accent and optional marks. Preserve declared photo invariants.
3. Compile four concise paragraphs using the applicable compiler. Name concrete visible focal/color carriers, their size/position, exact hue/material/share, exact text and relevant exclusions. Avoid ambiguous composition jargon that could become an unintended object or nautical icon.
4. Generate with the actual source/reference when supplied. Inspect the actual raster at full and thumbnail scales against quality-gate.md and photo invariants.
5. If preservation, source separation, recipe, accent or style fails, tighten only the failed decisions and regenerate once. Preserve successful regions. If still unsuccessful, state the remaining limit without claiming preservation succeeded.

Across adjacent outputs vary layout family, focal-element form and typography distribution, not just coordinates. Use only visible/current-batch prior outputs as variation evidence. For batches of four or more, use at least three layout families; do not repeat adjacent layout/focal pairs. At least 60% should carry the main hue through a subject, fragment, block or type rather than a tiny dot/hairline. Remove decoration, then secondary text, before weakening the subject or accent.

## Analysis

Inspect every usable reference; separate observed traits from interpretation. Distinguish repeated fixed rules, safe variables and sample residue. A single image cannot establish collection-wide frequency; percentages are estimates unless measured. Return the evidence, reusable prompt, variation options, avoids and confidence/limitations specified in reference-analysis.md. If generation is also requested, use a new recipe without copying a reference composition.

## Delivery

Generate mode returns the raster/path, exact final prompt used, one compact recipe, a short interpretation note, and photo role/preservation details when applicable. Prompt-only returns the four-paragraph prompt, recipe and relevant negatives without generation claims. Analysis returns the extracted system, not an unrequested image.

Use the requested ratio (default 3:5 portrait) and at least 2K long edge, with proportional resizing only; disclose enlargement rather than claiming native recovered detail. Save each source separately, preserving originals, prior outputs and the original basename; use output folders instead of unsolicited suffixes. Original/result comparison requires a separate current confirmation of content/layout/ratio/text; the internal collage is not a comparison request.

A successful poster stays sparse, flat, paper-native and poetic with one clear visual event, not an ad, generic collage template or full-bleed scene. Preserve all reference files, examples/evaluations and license needed by the supported modes.
