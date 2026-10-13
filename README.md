# Alembic

A screen-reader-first text alchemy game. Start with four elements — Fire,
Water, Earth, and Air — and combine them two at a time to discover 82 elements,
chasing 20 milestone goals. No drag-and-drop, no timers, no fail states. Just
buttons, a cauldron, and the satisfying "aha" of a new discovery.

## Play

The game is a single self-contained HTML file. No build step, no account. Your
catalog saves automatically in your browser and restores when you come back.

**[Play Alembic](https://alembic.lanie.work)** (alpha)

You can also open `index.html` directly in any browser.

## Features

- **Screen-reader first.** Every interaction is a button you activate with one
  keypress. All state changes announce through ARIA live regions. Works with
  NVDA, JAWS, VoiceOver, and Orca.
- **Linear layout.** Heading, cauldron, goals, catalog, hint — no spatial grids,
  no drag-and-drop, no visual information required to play.
- **Discover, don't grind.** Combine two elements to make a new one, then chase
  milestone goals like Life, Human, House, Computer, and Phoenix.
- **Hints that don't spoil it.** "Get a hint" reveals the *pair* to try, never
  the result — so the discovery still feels earned.
- **Flavor text.** Every element has a short line of flavor, read aloud the
  moment you discover it. Toggle it on or off in Options.
- **Keyboard shortcuts.** Alt + C to combine, Alt + X to clear, Alt + H for a
  hint, Alt + S to search. These work even in a screen reader's browse mode.
- **Automatic save.** Progress persists in your browser and restores on reload.
- **Reset with a safety check.** Wiping progress needs two confirming clicks.

## How to play

1. Activate an element to add it to your cauldron.
2. Add a second element.
3. Choose Combine. A new element joins your catalog, or nothing happens.
4. Check the Goals section for the big discoveries to chase.
5. Stuck? "Get a hint" points you toward the next one without giving it away.

## Status

Alpha. The core game is complete — 82 elements, 20 milestone goals, automatic
saving, and flavor text. Themed worlds and optional sound are planned.

## License

MIT. See LICENSE.
