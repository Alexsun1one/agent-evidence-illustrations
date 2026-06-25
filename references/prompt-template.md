# Prompt Template

Use this template for one image at a time.

```text
Generate one standalone 16:9 horizontal Chinese article illustration.

Visual DNA:
Pure white background. Sparse black hand-drawn line art with slightly wobbly pen lines. Lots of empty white space. Dry product-engineering sketch feeling. A few red/orange/blue handwritten Chinese annotations. No gradients, no shadows, no paper texture, no 3D, no polished vector stock style, no PPT infographic look, no cute mascot poster, no complex architecture diagram, no realistic UI screenshot.

Recurring visual system:
Use anonymous audit-office evidence workers and physical proof objects. The workers have rectangular stamp-like heads or archive-box heads, mostly white fill with black outlines, tiny square eyes or inspection slits, hanging ID tags, thin gloved arms, and one tool such as a red stamp, blue trace spool, orange routing string, permission key, sealed envelope, or paper tray. They must perform the core conceptual action, not decorate the scene. Do not use a solid black blob mascot, round cute body, generic robot, or Xiaohei-like character.

Theme:
{image topic}

Core claim:
{one sentence explaining what the image proves}

Composition pattern:
{Claim Weighing / Boundary Gate / Trace Path / Agent Handoff / Before-After Evidence / Failure Leak / Decision Brief / Moat Bridge / Memory Ledger}

Physical metaphor:
{specific audit-office object and action: stamp, tray, ledger, sealed envelope, trace ribbon, replay tape, permission key, transparent evidence sleeve, boundary gate}

Composition:
{where the workers are, what they do, what objects appear, how the viewer's eye moves}

Chinese labels:
{label 1} / {label 2} / {label 3} / {label 4} / {optional label 5}

Color use:
Black for main line art and worker outlines. Orange for routing strings, handoffs, or state transitions. Red as stamp ink for warnings, failed checks, unsupported claims, or final verdict. Blue for trace ribbons, replay tapes, system state, feedback, or secondary context.

Constraints:
One image explains only one core idea. Keep the main subject around 40%-60% of the canvas. Preserve at least 35% blank white space. Use at most 5-8 short Chinese labels, preferably as stamps, tags, tray labels, seals, or sticky notes. Do not write a title in the top-left corner. Do not write the composition pattern name on the image. Do not make it a formal flowchart, course slide, dense explainer, AI robot poster, cute mascot art, or commercial illustration. Make it clear but not literal, strange but clean, proof-like but human.
```

## Image Edit Prompts

Remove a wrong title:

```text
Edit the provided image. Remove only the handwritten text "{text_to_remove}" and any underline around it. Fill that area with clean white background matching the surrounding blank space. Preserve every other object, worker, label, line style, composition, aspect ratio, and image quality. Do not add new text.
```

Make the worker central:

```text
Regenerate the image with the same core meaning and simple layout, but make the evidence worker perform the central proof action directly. The worker should have a rectangular stamp-like head or archive-box head, a small ID tag, and a precise audit-office tool. The worker should weigh, stamp, seal, sort, guard, patch, replay, or hand off the key object. Keep the white background, sparse black hand-drawn line art, and limited red/orange/blue Chinese labels.
```

Reduce PPT feeling:

```text
Regenerate this as a physical proof metaphor rather than a formal diagram. Replace boxes and standard arrows with audit-office objects such as a stamp, paper tray, ledger, sealed envelope, trace ribbon, replay tape, permission key, transparent evidence sleeve, or boundary gate. Keep it sparse, hand-drawn, white-background, and article-ready.
```
