# AGENTS.md

## Scope

This repository is a public, presentation-only asset host for AnkiWeb deck listings.

## Allowed Content

- rendered PNG or JPEG screenshots that show shareable deck cards
- a short README and per-image provenance notes
- only material that is safe to make public

## Prohibited Content

- APKGs, source decks, collection databases, media exports, or build inputs
- private collection/deck paths, source deck IDs, credentials, `.env` files, or 1Password references
- AnkiWeb release configuration or automation that belongs in the private source project

## Git Hygiene

- Treat every file here as publicly visible.
- Keep filenames stable once used by an AnkiWeb description.
- Sign commits with GPG and push meaningful updates promptly.

## Publication safety

Follow `docs/PUBLICATION_PROCESS.md`. Install the shared frozen local hooks before
public pushes and keep the pinned quiet publication check required on main.
Keep detailed audit findings outside Git; unsupported formats block publication.
