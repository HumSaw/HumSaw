# HumSaw

I build inspectable developer tools and deterministic software.

My current focus is the hidden configuration around coding agents: what enters the context window, which instructions apply, and what can break before CI. The tools below are local-first, automation-friendly, and explicit about their limits.

## Developer tools

| Project | What it answers | Proof |
| --- | --- | --- |
| **[ctxbudget](https://github.com/HumSaw/ctxbudget)** | How much context does the agent configuration consume before the first prompt? | TypeScript CLI · five coding agents · CI budget gate |
| **[RuleTrace](https://github.com/HumSaw/ruletrace)** | Which AI coding instructions apply, in what order, and where do they conflict? | Zero-dependency CLI · local-only · structured output |
| **[dev-checkup](https://github.com/HumSaw/dev-checkup)** | Which common repository failures can be caught with one command? | Ten checks · zero dependencies · stable JSON output |

```bash
npx ctxbudget
npx ruletrace .
npm install -g github:HumSaw/dev-checkup && dev-checkup all
```

Each repository includes tests, CI, an MIT license, a security policy, and documented limitations. Registry install commands are shown only where the package is actually published.

## Selected systems work

- **[Admiral](https://github.com/HumSaw/battleship-math-model)** — constrained fleet inference and bounded expectimax in a browser, with a [live demo](https://admiral-weld.vercel.app).
- **[FurnGen](https://github.com/HumSaw/furngen)** — seeded procedural furniture generation and validation for Autodesk 3ds Max.
- **[Atelier](https://github.com/HumSaw/atelier-crm)** — an offline-first desktop CRM backed by local SQLite.

## Engineering principles

- deterministic, inspectable behavior over opaque heuristics
- useful defaults without accounts, telemetry, or subscriptions
- domain logic separated from UI and framework code
- reproducible tests and honest documentation
- explicit security boundaries and trade-offs

The best way to reach me about a project is through its GitHub issues.
