# Agent Guidance for my-first-app

## Project overview
- Simple browser-based side-scrolling action game.
- Implemented entirely in `index.html` with inline CSS and JavaScript.
- No build tools, package manager, or external dependencies.
- The app is launched by opening `index.html` in a browser.

## Key files
- `index.html` — game UI, rendering canvas, input handling, game loop, and score persistence.
- `README.md` — brief project description and controls.

## What to know before editing
- Keep changes simple and client-side.
- Preserve the single-page structure unless the task explicitly calls for refactoring into separate files.
- The text content is Japanese; maintain or update UI text carefully.
- The game state is stored in `localStorage` under `sideScrollBest`.

## Running and verifying changes
- Open `index.html` in a browser.
- Verify gameplay using:
  - Space or Arrow Up to jump
  - Click/tap the canvas to jump
  - Enter or restart button to reset after game over
- Confirm the score and best score update correctly.

## When to ask for more info
- If asked to add new features, consider whether the game should remain a single-file demo or be refactored.
- If asked to improve visuals or UX, focus on responsive canvas sizing, clear HUD, and accessible controls.
