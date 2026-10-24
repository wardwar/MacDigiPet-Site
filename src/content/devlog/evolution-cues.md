---
title: Evolution now follows the original cues
date: 2026-10-13
summary: The evolution sequence is retimed against the source cue table, and 3D partners no longer vanish after display sleep.
---
Evolution returns to idle after animation 12, starts its light on the 106 cue, whitens over 112–205, grows to the new size, tightens flashes from the 214 cue and spins faster into the reveal before a 3 second spotlight.

![Evolution phases](/img/evolution-phases.png)

**Bug fixed:** display sleep and wake left RealityKit views without a surface, so the pet vanished while its shadow and bubbles stayed. Renderers are now rebuilt on wake or display change, and stale pooled views are retired.
