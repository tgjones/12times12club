# 12×12 Club

A browser-based multiplication and division drill game. Math questions fly toward you in 3D space — type the answer before they reach you.

## How to play

Play it here: https://tgjones.github.io/12times12club/

Or locally, open `index.html` in a browser. No build step, no server required.

Choose a level:

| Level | Operations | Range |
|-------|-----------|-------|
| 0 | Multiply | up to 12×12 |
| 1 | Multiply & divide | up to 12×12 |
| 2 | Multiply | up to 24×24 |

Each session is 144 questions. The target is to finish them all within 5 minutes. Questions speed up as you progress.

**Controls:** type digits to answer, `Backspace` to correct, `← Menu` to quit.

## Stack

- Vanilla HTML/CSS/JS — single file, no dependencies installed
- [Three.js](https://threejs.org/) (loaded via CDN) for 3D rendering
- `Oswald_Bold.json` — bundled font for Three.js `TextGeometry`
