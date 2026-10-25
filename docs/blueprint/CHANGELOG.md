# Blueprint changelog

Versioned record of the master blueprint and the documents imported with it. Newest entries first.

## v2 — 2026-10-25 (design system decisions)

- Confirmed one design system for all portals. Hostnames (Q2) and Supabase region and plan tiers (Q3) are to be provided by the owner.

- Recorded owner decisions in `0001-build-gate-0.md`: status colours follow the Esk Design System, the token prefix is `esk`, and Amharic text uses Tayitu (primary) and Jiret (secondary).

## v2 — 2026-10-25 (design system replaced)

- Replaced `docs/design-system/DESIGN.md` (Vibrant Retail Commerce) with `docs/design-system/Esk_Design_System.md` (Esk Design System v2.0.0). `0001-build-gate-0.md` is updated to match.

## v2 — 2026-10-25

- Imported `engida-hms-master-blueprint-v2.md` as `docs/blueprint/engida-hms-master-blueprint-v2.md`.
- Imported the owner design system as `docs/design-system/DESIGN.md`. Build Gate 0, question 1, is recorded as "yes" in `docs/architecture/adr/0001-build-gate-0.md`.
- Imported the Tayitu (primary) and Jiret (secondary) Ethiopic fonts into `packages/ui/src/fonts/`.
- Recorded the Build Gate 0 answers in `docs/architecture/adr/0001-build-gate-0.md`. Question 1 is answered. Questions 2 to 4 are open.
- Held the §45 repository skeleton until Gate 0 questions 2 to 4 are answered. No folders, placeholders or configuration were added.
