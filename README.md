# Aakkospeli

A browser game for practicing the Finnish alphabet. The player clicks shuffled letter cards in the correct order from A to Ö, races against a timer, and can save local high scores.

## Features

- Finnish alphabet order: A-Z plus Å, Ä, Ö
- Start screen, reset button, and alphabet cheat sheet
- Timer with tenths of a second
- Completion screen with name entry
- Local hall of fame stored in `localStorage`
- Clear-high-scores confirmation dialog
- No backend and no build step

## Run

Open `index.html` in a browser.

You can also serve it locally:

```bash
python3 -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

## How To Play

1. Press `Aloita peli`.
2. Click the visible letters in Finnish alphabet order.
3. Use `Lunttilappu` if you need to check the full alphabet.
4. Save your time to the local hall of fame after finishing.

## Files

- `index.html` - complete game implementation
- `LICENSE` - project license

## Data

Scores are saved only in the current browser via `localStorage` under `aakkospeliHallOfFame`.
