# Arcade

Original browser puzzle games in vanilla HTML, CSS and JavaScript. No dependencies, no build step.

| Game | Idea |
|---|---|
| [Tidebound](games/tidebound/) | Collect pearls while the sea rises one row every three moves. Random rounds. |
| [Mirror Mole](games/mirror-mole/) | One key press moves two moles with mirrored sideways motion. Four levels verified solvable with a BFS solver. |

Live site: `https://HarithaKongi.github.io/never-existed-arcade/`

## Structure

```
index.html            landing page
games/tidebound/      one folder per game, each self-contained
games/mirror-mole/
```

To add a game, create `games/HarithaKongi/index.html` and add a card to the root `index.html`.

## Run locally

Open `index.html` in a browser. Controls: arrow keys or WASD, or the on-screen pad.

## Deploy

Settings > Pages > Deploy from a branch > `main` / root.

## Highlights

- Game rules and state written from scratch
- Random level generation and verified level design
- Keyboard and touch input, responsive layout, light and dark themes
- Accessibility basics: focus outlines, aria labels, live status text
