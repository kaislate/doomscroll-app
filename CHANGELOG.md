# Changelog

All notable changes to **Doom Scroll**. This project is in Beta. Dates are release dates.

## 0.4.3 — 2026-06-10

### Added
- **"What's new" in the update popup** — when an update is available, expand the
  banner to read that version's changelog right there, no browser needed.

### Changed
- The update banner now **spans the content area** and **slides down** into view from
  the top, instead of floating as a small centered pill.

### Fixed
- The **Doom Meter no longer floats over other apps** — it now shows only while Doom
  Scroll is the foreground window (or when the window is pinned), like the main window.

## 0.4.2 — 2026-06-10

### Changed
- **New app icon** 💀 — a skull with a double downward "endless scroll" chevron on
  a deep purple → near-black gradient. The startup splash mark matches.

### Fixed
- The "update available" banner no longer shows a faint square corner over light
  backgrounds (an outer drop-shadow was clipping to the window's square bounds).

## 0.4.1 — 2026-06-10

### Added
- **🌀 Doom Meter** — a floating meter beside the window that fills the more you
  scroll a feed. Per-site (each feed tracks its own doom), persists across
  restarts, and resets daily. The fill ramps green → amber → red and the 💀
  ignites at 100%. It follows the window as you move it, and can be toggled off in
  **Settings → Doom Meter**.

### Fixed
- Floating windows no longer show a faint square corner over the desktop (an outer
  drop-shadow was clipping to the window's square bounds) — corners are cleanly
  rounded over both light and dark backgrounds.

## 0.4.0 — 2026-06-10

### Changed
- **Rebranded Inset → Doom Scroll**, with a new app icon (the feed motif plus an
  endless-scroll chevron). This is a new app identity, so updating from 0.3.0 is a
  one-time fresh install rather than an auto-update.

## 0.3.0 — 2026-06-09 (Beta)

### Added
- **In-app auto-updates** — checks on launch and from Settings, downloads
  cryptographically signed updates, installs, and relaunches.
- Per-site **dark mode** (`Auto` / `Force` native force-dark / `Off`), per-site
  **zoom** and **volume**, and a global **mute**.
- **Multi-site display** (2–4 feeds side by side), **immersive** edge-to-edge mode,
  **frame & window opacity**, **pin on top**, and **lock position & size**.
- **Touch / drag scrolling** and smooth **scroll acceleration** (with nested
  scroll-area handling).
- Curated feeds — **Facebook, X, Reddit, eBay** — with carousel switching, a
  site-name pill, and a startup-site picker.

## 0.1.0 — 2026-06-07 (Alpha)

- Initial alpha: a borderless, chromeless desktop widget nesting a web feed in a
  soft neumorphic frame.
