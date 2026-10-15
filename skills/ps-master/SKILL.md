---
name: ps-master
description: "Naturally retouch/edit user photos with identity-preserving, non-destructive output. Use for P图、修图、精修、人像美化、调色、去除杂物、换背景、合成、裁切、扩图 and photo/poster size adaptation. Not Photoshop desktop control or layered PSD production."
metadata:
  version: "1.4.1"
---

# PS 大师

Use the built-in image editing capability, not third-party services/API keys or Adobe automation. Follow the selected style's deliberate illustration/material choices rather than imposing photographic realism on an explicitly illustrated artwork.

## Preflight

- Inspect local target photos with view_image. Identify each input as edit target, style reference or compositing source; ask only about materially ambiguous roles/changes.
- For numbered styles and original/result choice, read [photo-style-workflow.md](references/photo-style-workflow.md). Load only the selected style(s). Current batch/revision answers carry forward; do not repeat settled questions.
- Naturally resolve color/white balance before the requested treatment, preferably in the same pass. Preserve source atmosphere, geometry and all unrequested content.
- Default to natural realistic retouching unless stylization is requested. Never add people, objects, text, makeup, accessories or scenery except as authorized by the chosen task/style.
- Preserve complete principal subjects and recognizable props/pose; adapt whitespace/scale rather than remove them to force a composition.

## Portrait fidelity

For retained photographic people, identity outranks beautification: preserve facial geometry/features/hairline, expression/gaze/apparent age, skin-tone family, body proportions/pose, clothing, perspective, marks, natural asymmetry and believable skin/hair texture.

Normal cleanup may correct exposure/white balance, temporary blemishes, flyaways, background distractions and eye clarity without reshaping or whitening. Do not default to slim face, large eyes, narrow nose, pointed chin, body reshaping or plastic smoothing. For illustration-only reinterpretation, use the selected style's abstraction rules and protect explicitly requested likeness/anatomy.

## Render and check

1. Brief the smallest sufficient change with exact invariants, requested ratio/text and permitted new elements. Read imagegen for current tool/reference mechanics; use actual targets, not just descriptions.
2. Prefer one focused pass. Repeated repainting increases identity/detail drift.
3. Inspect the actual output at full and thumbnail scales; for portraits closely check face, hands/fingers, hairline, teeth/ears, clothing edges and background seams.
4. Confirm requested change, source fidelity, complete subjects, coherent anatomy/perspective/reflections/shadows, legible exact text, style/layout and natural material.
5. Correct observed failures locally without altering successful regions. After two failed correction attempts—or a stricter selected-style limit—report the issue instead of claiming completion.

Reject halos, duplicated/melted details, warped anatomy, invented text, watermark, waxy skin, painted hair, glassy eyes/fake catchlights, repeated fake texture, crunchy sharpening and synthetic blur transitions. Preserve source imperfections when cleanup would invent detail.

## Export and files

Default selected finals to at least 2048 px long edge in the agreed ratio. Use proportional non-generative resizing if needed; disclose enlargement, not native recovered detail. Do not synthesize pores, lashes, strands or weave just to reach 2K.

Honor the user's destination first; otherwise use project-local ps大师/成品. Do not copy/archive a source into ps大师/原图 unless requested. Never overwrite, rename, move or degrade originals or prior outputs.

Keep the source basename (format conversion may change the extension); separate source/style/result/composite by output folders, not unsolicited labels, dates or version suffixes. Use a distinct output folder for a new revision rather than overwriting a collision.

A comparison is an additional separately confirmed file; keep the standalone final. Deliver absolute file links/images, a brief change/preservation note, and any real limitations. Do not auto-open a preview. Keep private photos out of unrelated services, repositories and public sharing. If built-in editing is unavailable, explain the boundary; do not silently switch provider or promise PSD layers.
