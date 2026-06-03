# agent-skills

A collection of [Agent Skills](https://github.com/vercel-labs/skills) for the Angular ecosystem.

## Skills

| Skill | Description |
| --- | --- |
| [`ngrx-signals`](skills/ngrx-signals) | Build and review Angular state management with NgRx **SignalStore** (`@ngrx/signals`) — `signalStore`/`signalState`, `withState`/`withComputed`/`withMethods`, `patchState`, `rxMethod`/`signalMethod`, entities, the Events plugin, custom features, testing, `@ngrx/operators`, and the `@angular-architects/ngrx-toolkit` extensions. |
| [`primeng`](skills/primeng) | Build and review Angular UIs with **PrimeNG** (v21) — a focused reference for all 90+ components and directives, plus `providePrimeNG` setup, `@primeuix/themes` theming/design tokens, dark mode, passthrough (`pt`)/unstyled, Tailwind integration, PrimeIcons, and the Message/Confirmation/Dialog services. |

## Install

These skills follow the `skills/*/SKILL.md` convention and install with the [`skills`](https://www.npmjs.com/package/skills) CLI:

```sh
# install every skill in this repo
npx skills add BeGj/agent-skills

# or just one skill
npx skills add https://github.com/BeGj/agent-skills/tree/main/skills/ngrx-signals
```

The CLI supports Claude Code, Cursor, Codex, OpenCode, and others (`-a <agent>` to target a specific one).

## What's inside a skill

Each skill is a directory with a `SKILL.md` router (YAML frontmatter + task dispatch) and a `references/` folder of focused, distilled topic guides — not raw documentation dumps.

## Source & license

The `ngrx-signals` content is distilled from the official [ngrx.io](https://ngrx.io/guide/signals) documentation (the [`ngrx/platform`](https://github.com/ngrx/platform) repo) and the [`@angular-architects/ngrx-toolkit`](https://ngrx-toolkit.angulararchitects.io/) docs, both MIT-licensed. Released under the [MIT License](LICENSE).
