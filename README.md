# 2048

A browser implementation of the 2048 game in vanilla HTML/CSS/JavaScript —
no frameworks, no build step.

The game is played on a 4×4 grid: arrow keys slide the tiles, adjacent tiles
with the same value merge, and a new 2 or 4 tile spawns each turn. Reach 2048
to win.

## Play it

Open `index.html` in a browser — that's it.

```bash
git clone https://github.com/nityamittal/2048-Game
cd 2048-Game && open index.html
```

## Files

- `index.html` — board markup
- `script.js` — game logic (movement, merging, spawning, win/lose detection)
- `style.css` — board and tile styling

## License

MIT — see [LICENSE](LICENSE).
