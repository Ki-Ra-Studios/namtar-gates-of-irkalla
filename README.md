# NAMTAR   Gates of Irkalla

A dark, atmospheric survival-dodge arcade game built for the browser, themed around **Namtar**, the Mesopotamian herald of the underworld associated with plague, fate, and death.

Play as a lost soul navigating the underworld of Irkalla. Dodge Namtar's roaming plague wisps and miasma, survive his telegraphed curses, collect the sigils of Ea for score, and endure his periodic "awakenings"   boss phases where a ring of curses radiates outward with only narrow gaps to escape through.

## Play

Open [`index.html`](index.html) directly in any modern browser   no build step, no dependencies, no external assets. Works fully offline once loaded.

If GitHub Pages is enabled for this repo, it's also playable at:
`https://ki-ra-studios.github.io/<repo-name>/`

## Controls

- **Desktop:** `WASD` or Arrow Keys to move. `Esc` / `P` to pause. Click-and-drag also works.
- **Mobile:** Drag anywhere on screen to move your soul (virtual joystick). Tap the pause/mute icons in the corner.

## Design

- Single self-contained `index.html`   inline CSS + vanilla JS canvas rendering, no frameworks or build tools.
- Procedural WebAudio sound (ambient drone + SFX)   no audio files.
- Fully responsive: scales from small phones to wide desktop monitors, with safe-area padding for notched devices.
- Local high-score persistence via `localStorage`.

## Tech

Pure HTML5 Canvas + JavaScript. No dependencies, no build process, no package manager required.

---
Built by **Ki-Ra Studios**.
