# 2048 Game

Single-file browser game (index.html) — no build tools, no dependencies.

## Structure
- `index.html` — all HTML, CSS, and JS in one file
- Game logic is in an IIFE inside `<script>` tag
- Grid size is dynamic (4/5/6/8), controlled by `SIZE` variable
- State persisted per difficulty level in localStorage with keys like `2048-4-state`, `2048-4-best`

## Key conventions
- All UI text is in Russian
- Difficulty levels: 4×4 (Сложно), 5×5 (Средне), 6×6 (Просто), 8×8 (Легко)
- Undo is single-step only (one undo per move)
- Timer counts up from game start, pauses with P key
- Enter starts a new game
