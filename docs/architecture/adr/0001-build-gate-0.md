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

Owner decisions, 2026-10-25:

1. **Status colours follow the Esk Design System.** The §34 status hues (hold, confirmed, in-house, checked-out, cancelled, no-show, OOO, OOS, dirty, clean, inspected) take their colours from its semantic tokens (success, warning, danger, info, accent, neutral, brand). Status is always shown with an icon or text label as well as colour (design system §2.2 rule 4). The state-to-token table is written when the status components are built.
2. **Token prefix is `esk`.** CSS variables are `--esk-*` and Tailwind tokens use the `esk` namespace. The uploaded file still says "Z System" and `--z-` in its text. It is kept unmodified as the owner's source.
3. **Amharic text uses Tayitu (primary) and Jiret (secondary)** from `packages/ui/src/fonts/`. The design system's own fonts (Plus Jakarta Sans, Inter, JetBrains Mono) stay for Latin text. The Noto Sans Ethiopic fallback from §34 and D-36 stays after Jiret, because the owner did not replace it.

Assumption, open to correction: §48.0 asks whether one system covers every portal or the Public Portal has its own brand. The Esk Design System is written as general-purpose, so one system for all portals is assumed.

Not done yet: mapping the Esk Design System tokens to the Tailwind theme and the shadcn/ui theme variables. That is code work and waits for Questions 2 to 4.

### Q2. Final hostnames

**Open.** The placeholders `platform.domain.com`, `*.domain.com`, `domain.com` and `domain-staging.com` stay in configuration until the owner provides real names or confirms the placeholders stay.

### Q3. Supabase region (D-38) and plan tiers (D-40)

**Open.**

### Q4. Decision gates G-1, G-4 and G-5

**Open.** The §48.1 defaults apply if the owner accepts them. G-2 and G-3 are already decided (D-41 and D-42).

## Consequences

- Until Questions 2 to 4 are answered, no scaffolding is added. That covers the folder skeleton, `.gitkeep` placeholders, `.gitignore`, package manifests, Vite and Vercel configuration, Supabase migrations, Edge Functions and UI code.
