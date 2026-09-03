# Tableful — Design Board

Living review board for the Tableful app's design system. **Always shows the latest design drop** from the design agent, in a Figma-style three-pane view: frame rail · canvas with zoom · inspector with tokens, contrast ratios, and design notes.

## View it

Once GitHub Pages is enabled (Settings → Pages → Deploy from branch → main), the board lives at:

**https://hamlet-tamaz.github.io/tableful-design/**

## The review loop

1. Design agent ships a drop → this board updates.
2. Review frames here (arrow keys to move, zoom bar for detail).
3. Approve via the design session or `design-sync/APPROVALS.md` in the shared project drive.
4. The dev agent implements only approved drops.

Screens are real production renders (headless Chromium against the actual built app), not mockups — what you see is literally what ships.
