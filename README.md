# Apple Site

A single-file, Apple Store–style page — `apple.html`. No build step, no dependencies, no network calls. Open it in a browser and it works.

```bash
open apple.html
```

## Features

- **Swipe to unlock** — one gesture reveals every section; sections fade in progressively.
- **Liquid glass UI** — reusable glass system (blur + saturate + brightness, inset highlights, animated sheen sweep) across the nav bar, cards, and stage.
- **Home View** — a 3D-tilted device lineup (Watch, iPad, Vision Pro, HomePod, iPhone) plus a 25-app home screen grid with working app icons.
- **Devices** — pre-order list for MacBook Pro 14", iMac, Mac mini, and Mac Studio, each with a CSS illustration. Pre-orders persist to `localStorage`.
- **Products** — click-through product sheets with tips and facts per device.
- **Review** — write feedback, submit, get a "Thank you for your feedback." confirmation. Stored locally in the browser.
- **Premium** — 5-question trivia quiz. A perfect score unlocks a hidden pro-specs section with detailed technical tables.
- **Apple Events feed**, **Did You Know** facts, **History** timeline, and an **Apple Park** section.

## Mobile

Built mobile-first and verified for zero horizontal overflow at 320, 360, 390, 402, and 430px. The glass nav collapses to a 4-column grid, and the device lineup shrinks per breakpoint. The Apple Watch face is sized in `em` off a single width basis, so its elements scale in exact proportion and can never overlap at any size.

## Tech

Plain HTML, CSS, and vanilla JS in one file. No frameworks, no bundler, no external assets. Design tokens follow Apple's site conventions — `--bg:#fff`, `--fg:#1d1d1f`, `--muted:#6e6e73`, `--accent:#0071e3`.

## Note

This is a fan-made page for learning purposes. It is not affiliated with or endorsed by Apple Inc. Product names and specs are illustrative.
