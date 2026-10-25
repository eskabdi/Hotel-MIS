# ADR-0001: Build Gate 0 answers

- **Status:** Partially answered. Question 1 is recorded. Questions 2 to 4 are open.
- **Date:** 2026-10-25
- **Source:** Blueprint §48.0 (Build Gate 0) and §34 (design system defaults)

## Context

Blueprint §48.0 requires the building agent to ask the owner four questions before any scaffolding, code generation or UI work. The answers are recorded in this file.

## Decision

### Q1. Is a UI/UX design system being provided?

**Answer: Yes (owner upload).**

| Asset | Location |
| --- | --- |
| Design system v2.0.0: tokens and component specifications (`name: Esk Design System`) | `docs/design-system/Esk_Design_System.md` |
| Tayitu, primary Ethiopic font | `packages/ui/src/fonts/Tayitu.ttf` |
| Jiret, secondary Ethiopic font | `packages/ui/src/fonts/Jiret.ttf` |

Consequences under §48.0:

- The Esk Design System visual tokens supersede the §34 defaults for palette, Latin typography, spacing, radii, iconography and motion.
- These are not overridden: WCAG 2.1 AA contrast and focus rules (§44); Ethiopic support with Tayitu, Jiret and the Noto Sans Ethiopic fallback; Arabic numerals in Ethiopian-calendar contexts; the `<Money/>`, `<StayDate/>` and `<EthTime/>` rendering contracts; and status-colour semantics.

Open conflicts for the owner. Not yet decided:

1. The §34 status hues (hold, confirmed, in-house, checked-out, cancelled, no-show, OOO, OOS, dirty, clean, inspected) are not defined in the Esk Design System. It has success, warning, danger, info and accent only. They must be remapped to its palette, not removed. The owner must approve the mapping.
2. The file's title and CSS prefix say "Z System" and `--z-`, while its name says Esk. The owner must confirm the token prefix.
3. Its typography lists Plus Jakarta Sans, Inter and JetBrains Mono, with no Ethiopic family. Tayitu, Jiret and the Noto Sans Ethiopic fallback must be added to the font stacks (§34, D-36).
4. §48.0 asks whether one system covers every portal or the Public Portal has its own brand. The Esk Design System is written as general-purpose, so one system for all portals is assumed until the owner says otherwise.

Not done yet: mapping the Esk Design System tokens to the Tailwind theme and the shadcn/ui theme variables. That is code work and waits for Questions 2 to 4.

### Q2. Final hostnames

**Open.** The placeholders `platform.domain.com`, `*.domain.com`, `domain.com` and `domain-staging.com` stay in configuration until the owner provides real names or confirms the placeholders stay.

### Q3. Supabase region (D-38) and plan tiers (D-40)

**Open.**

### Q4. Decision gates G-1, G-4 and G-5

**Open.** The §48.1 defaults apply if the owner accepts them. G-2 and G-3 are already decided (D-41 and D-42).

## Consequences

- Until Questions 2 to 4 are answered, no scaffolding is added. That covers the folder skeleton, `.gitkeep` placeholders, `.gitignore`, package manifests, Vite and Vercel configuration, Supabase migrations, Edge Functions and UI code.
