# KTH Library Skills

A repository of Claude skills for KTH Library teams.

## Skills

| Skill | Purpose |
|---|---|
| [`kth-lib-bibliometrics`](./kth-lib-bibliometrics/SKILL.md) | Bibliometric analysis, publication/citation counting, and KTH-styled reporting for the library's bibliometrics analyst team. |

## Shared resources

Content reused across multiple skills lives in `shared/`, rather than being
duplicated into each skill folder:

- [`shared/kth-styling/`](./shared/kth-styling/) — KTH visual identity fallback notes (colors, logo, Quarto styling). The live source of truth is [`KTH-Library/kth-quarto`](https://github.com/KTH-Library/kth-quarto); this folder holds only a fallback for when live retrieval isn't possible.
- [`shared/kth-org/`](./shared/kth-org/) — Pointers to relevant KTH GitHub organizations ([`KTH-Library`](https://github.com/KTH-Library), [`KTH-biblioteket`](https://github.com/KTH-biblioteket)).

## Adding a new skill

1. Create a new folder, `kth-lib-<name>/`, with its own `SKILL.md` and any
   `references/` files specific to that skill.
2. If the new skill needs KTH branding or org pointers, reference the
   existing files in `shared/` by relative path rather than copying them.
3. If the new skill introduces content that other skills will also need,
   consider moving it into `shared/` instead of keeping it local.
4. Add a row to the table above.

## Naming convention

Skills in this repo are prefixed `kth-lib-` so they're identifiable whether
browsed here or installed individually.

## Changelog

See [`CHANGELOG.md`](./CHANGELOG.md) for notable changes to skills and
shared resources over time.
