# HumSaw

I build developer tools, desktop software, simulation engines, procedural systems, and focused web applications.

My strongest work sits where product engineering meets explicit models: developer tooling, native OS integration, constrained search, deterministic simulation, self-learning agents, procedural generation, and offline-first software. I primarily use TypeScript, Next.js, React, Electron, Node.js, and MAXScript.

## Selected work

### [ctxbudget](https://github.com/HumSaw/ctxbudget)

A CLI that shows how much fixed context a coding-agent setup consumes before the first prompt. It scans instructions, rules, skills and agent config for Claude Code, Codex, Cursor, Copilot and Gemini, with optional MCP tool-schema measurement and CI budget checks.

TypeScript · CLI · MCP · developer tooling

### [YT Live Wallpaper](https://github.com/HumSaw/yt-live-wallpaper)

A cross-platform Electron application that turns YouTube videos or local media into desktop wallpapers. It supports multi-monitor setups, crossfades, playlists, automatic pausing during fullscreen applications, and OS-specific desktop integration on Windows, macOS, and Linux.

Electron · Node.js · native OS integration

### [Admiral — Battleship Mathematical Scoring Model](https://github.com/HumSaw/battleship-math-model)

A browser-based Battleship advisor built around constrained fleet enumeration, weighted Sequential Importance Sampling, two-ply lookahead, and bounded expectimax. The engine runs in a Web Worker; the interface supports 10 languages and RTL layouts.

[Live demo](https://admiral-weld.vercel.app) · TypeScript · Next.js · Vitest

### [FurnGen](https://github.com/HumSaw/furngen)

A seeded procedural furniture generator for Autodesk 3ds Max. It creates furniture and coordinated room sets with reproducible geometry, renderer-aware materials, and built-in model validation.

MAXScript · procedural geometry · static analysis

### [Atelier](https://github.com/HumSaw/atelier-crm)

An offline-first desktop CRM for interior designers and 3D artists. Contacts, projects, reminders, templates, and financial records stay in a local SQLite database.

Electron · Next.js · SQLite · Drizzle

### [Chronicle of Erdalion](https://github.com/HumSaw/erdalion-simulation)

An evolutionary fantasy-world simulation in which ten factions maintain independent Q-learning policies and adapt through war, diplomacy, trade, raids, and dynastic marriages.

TypeScript · Q-learning · emergent simulation

### [Evervale Kingdom](https://github.com/HumSaw/evervale-kingdom)

A browser strategy game with deterministic battles, seeded enemy generation, six-resource economy, build and training queues, and versioned persistent saves.

TypeScript · Next.js · Zustand

## Engineering priorities

- deterministic, inspectable behavior instead of opaque heuristics
- domain logic separated from UI and framework code
- reproducible tests and simulations
- honest documentation with explicit limits and trade-offs
- software that remains useful without an account or subscription
