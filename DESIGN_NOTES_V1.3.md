# VortexEdit Pro Design — 1.3

## Design direction
The 1.3 pass establishes a consistent dark editing workspace rather than changing hue values alone.

- Deep neutral canvas with layered panel surfaces.
- Clearer separation between primary actions, secondary actions, and destructive actions.
- More consistent control sizing, border radii, focus states, and hover feedback.
- Timeline and media surfaces use separate contrast layers to preserve visual grouping.
- Arabic text must remain legible and layouts should preserve RTL behavior without mirroring time-based controls.

## Screen coverage
The reference viewer continues to include all 23 screen concepts. Apply the shared tokens and component rules from `design-system-v1.3.css` to each screen. The implementation in PySide6 remains the source of truth for working behavior.

## Versioning
- 1.2 — baseline reference.
- 1.3 — shared design-system foundation and refreshed reference viewer chrome.
