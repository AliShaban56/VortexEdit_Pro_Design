# Workspace Rebuild 1.4 — Design Reference

The user supplied two new screenshots (5.png, 6.png) and asked for a complete rebuild with three selectable workspaces.

- **Premiere-style:** professional NLE layout; neutral graphite; compact media bin; effect controls; large monitor; multitrack timeline.
- **CapCut-style:** creator-first tool discovery; larger controls; quick properties; prominent aspect and social video affordances.
- **Vortex classic:** preserve the spatial concept in supplied screenshots: inspector left, preview center, media drawer and tool rail right.

The new WORKSPACE_REBUILD_1.4.html is an interactive concept board with these three profile directions and the two original screenshots embedded as image references. The PySide6 implementation must remain behaviorally real: these are workspace profiles over the same project/controller/render pipeline, not mock screens.

Audit findings from supplied screenshots:
1. Preview canvas dominates the screen while conveying no useful empty-state action.
2. Inspector and media drawer are narrow and poorly balanced against the preview.
3. Settings page shows low-contrast fields and inconsistent alignment.
4. Timeline needs user-adjustable height and clear track grouping.
5. Arabic text should flow RTL while video coordinates and timeline time remain LTR.
