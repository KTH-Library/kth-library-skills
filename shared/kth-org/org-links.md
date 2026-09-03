# KTH GitHub Organizations — Reference

Shared pointer file for KTH-affiliated GitHub organizations, used across
skills in this repository.

## Primary — check first for existing tools/pipelines

**`github.com/KTH-Library`**
Main organization space. Most of the bibliometrics codebase and related
tooling used by the library's analyst team lives here. When a request
references existing tools, scripts, dashboards, or pipelines, check this
org before assuming something needs to be built from scratch.

Also home to the KTH branding/Quarto assets:
`github.com/KTH-Library/kth-quarto` (see `shared/kth-styling/` for how
skills should use this).

## Secondary — same organization, less directly relevant to analyst work

**`github.com/KTH-biblioteket`**
A sibling GitHub space within the same overall library organization.
Less directly tied to the bibliometrics team's day-to-day work. Reference
only when a request specifically points here or clearly concerns this
space's projects — don't default to searching it.

## Usage note for skill authors

If a new skill in this repo needs to reference either organization, link to
this file from the skill's `SKILL.md` rather than re-describing the orgs
inline, so updates only need to happen in one place.
