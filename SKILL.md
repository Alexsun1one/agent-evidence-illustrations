---
name: agent-evidence-illustrations
description: Generate Chinese article illustrations for AI, product, engineering, agent workflow, trust, audit, architecture, and decision-making content. Use when the user asks for article illustration planning, shot lists, generated images, visual metaphors, evidence-chain diagrams, system-boundary drawings, agent collaboration illustrations, white-background hand-drawn explainers, or edits to remove/fix text in generated article figures.
---

# Agent Evidence Illustrations

## Core

Design 16:9 white-background article illustrations that turn abstract AI/product/engineering claims into memorable evidence-chain drawings. The goal is not a PPT infographic, cute mascot art, or generic AI illustration; the goal is a clear visual proof object: one claim, one mechanism, one strange but legible physical metaphor.

Default visual language: sparse black hand-drawn line art, white space, a small recurring cast of "evidence workers" and physical proof objects, with very few red/orange/blue handwritten Chinese labels. The worker characters must perform the conceptual action: sorting evidence, guarding a boundary, weighing claims, sealing a trace, handing off a task, replaying a log, or repairing a workflow.

## Read References As Needed

Load only the reference needed for the current task:

- `references/style-dna.md`: visual rules, palette, density, hard bans.
- `references/evidence-workers-ip.md`: recurring character and object system.
- `references/composition-patterns.md`: shot types and metaphor recipes.
- `references/prompt-template.md`: image generation and image edit templates.
- `references/qa-checklist.md`: checks after planning or generation.

## Workflow

### 1. Extract The Claim

Read the article, Markdown, screenshot text, concept, or user notes. Identify:

- the central claim
- the strongest evidence or mechanism
- the hidden boundary or failure mode
- the before/after state
- the one moment a reader should remember

Do not average across the article. Prefer a few high-signal visual anchors over many decorative images.

### 2. Plan A Shot List

If the user asks for planning, pairing suggestions, or "where should this article have images", output a compact shot list. For each image include:

- placement after section/paragraph
- topic
- core claim
- composition pattern
- physical metaphor
- evidence worker action
- suggested Chinese labels

Default to 3-6 images. Short posts can use 1-2. Long essays should still rarely exceed 8 unless the user asks for a visual essay.

### 3. Generate Images

If the user asks to generate, make one image per call. Do not make a multi-panel bundle unless the shot itself is a small comic sequence.

Every generation prompt must include:

- 16:9 horizontal Chinese article illustration
- pure white background
- sparse black hand-drawn line art
- evidence worker or proof object doing the core action
- at most 5-8 short handwritten Chinese labels
- red only for risk/result, orange for main path, blue for system/feedback state
- no top-left title, no formal diagram label, no PPT look

### 4. Edit Or Repair

For image edits, preserve composition and style. Remove wrong titles, simplify labels, clean artifacts, or make the evidence worker perform the core action more clearly. Do not add new explanatory clutter.

### 5. Save And Report

When working in a repository or article folder, save final images under:

```text
assets/<article-slug>-evidence-illustrations/
```

Name files in order:

```text
01-claim-name.png
02-boundary-name.png
```

Report only the useful delivery details: image count, purpose of each image, file paths, and any image that should be regenerated.
