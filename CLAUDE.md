# 2048 Game

Single-file browser game (index.html) — no build tools, no dependencies.

## Structure
- `index.html` — all HTML, CSS, and JS in one file
- Game logic is in an IIFE inside `<script>` tag
- Grid size is dynamic (3/4/5), controlled by `SIZE` variable
- State persisted per difficulty level in localStorage with keys like `2048-3-state`, `2048-4-best`

## Key conventions
- All UI text is in Russian
- Difficulty levels: 3×3 (Легко), 4×4 (Классика), 5×5 (Сложно)
- Undo is single-step only (one undo per move)
