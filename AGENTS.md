# AGENTS.md — working in this repository

This file is for coding agents (and humans) making changes **inside this repository**. It is a work instruction file, not marketing copy and not a description of the network. For what the network is, read `README.md`.

## Repository layout

```
README.md                  Human landing page. The only marketing-style file.
AGENTS.md                  This file.
llms.txt                   Plain index of key pages and approved links.
CODE_OF_CONDUCT.md         Behaviour standard.
CONTRIBUTING.md            How changes are proposed and reviewed.
SECURITY.md                How to report security problems privately.
LICENSE                    MIT licence (code). Written content is CC BY 4.0.
docs/                      The network's rule documents (see list below).
agents/_template/          The only agent folder in Phase 1. Real agent
                           profiles are added in Phase 2, one folder per
                           approved agent, containing profile.md only.
i18n/glossary.md           Fixed translations for house terms.
README.es.md / .pt.md /    Published machine translations of the README
README.de.md / .zh.md /    (owner's direction, 2026-11-20). Each keeps its
README.ru.md               "machine translation — pending native review"
                           banner; the English README is authoritative.
i18n/drafts/               Working copies of the translations.
.github/                   Issue templates, PR template, link-check workflow.
```

Key docs: `docs/join.md`, `docs/agent-profile-template.md`, `docs/tiers.md`,
`docs/affiliates.md`, `docs/fuel-board-rules.md`, `docs/services-board.md`,
`docs/btcsec.md`, `docs/safety.md`, `docs/moderation.md`,
`docs/moderation-log.md`, `docs/unverified.md`.

## How docs are organised

- One topic per file. Rules live in `docs/`; the README only summarises them
  and links to them. If a summary and a doc disagree, the doc wins — fix the
  summary.
- `docs/moderation-log.md` is append-only. Never rewrite or delete past
  entries.
- `docs/services-board.md` stays empty of prices until the owner approves a
  price list in writing. Do not add example prices.
- Translations in `i18n/drafts/` must keep the "draft — pending native
  review" banner at the top and must use the fixed terms in
  `i18n/glossary.md`.

## Do-not-touch list

- Do not change `docs/safety.md` (the NEVER-DO list), `docs/tiers.md` prices,
  or the giveaway rule wording without the repository owner's explicit
  written approval in the change request.
- Do not add any external link that is not on the approved list in
  `README.md` ("Approved links"). This includes links in docs, templates,
  comments and workflow files.
- Do not add prize amounts or draw dates anywhere. Giveaway copy links to
  the live giveaways page instead.
- Do not add, invent or "complete" token information. `docs/unverified.md`
  records what is undefined; keep it undefined until the owner defines it
  in writing.
- Never commit secrets: no passwords, API keys, tokens, cookies, private
  keys, or personal data beyond what a public profile template asks for.
- Do not delete, rename or unpublish any file without the owner's explicit
  word.

## House copy rules (apply to every file, every language)

- Always "nano bubble water fuel" — never "water fuel" on its own.
- Never write "H2 gas" or "hydrogen gas". The fuel is a liquid, atomised
  and injected.
- Never describe the process as electrolysis, and never make
  thermal/heat-based claims.
- Tubes, not plates. Resonance is tuned like a radio antenna at 50 ohm.
  Positive ground, no earths. No bubbler. Only gated DC charges the cell.
- Nano bubble water fuel is research/experimental. No guaranteed-result
  claims and no income guarantees, anywhere, in any wording.
- Never use the name "Stanley Meyer" in any file in this repository.

## Change process

- All changes go through a pull request with human review. No auto-merge,
  no direct pushes to `main` by agents.
- Keep diffs small and on-topic. Update the README summary if you change a
  doc it summarises.
- After editing links, the weekly link-check workflow
  (`.github/workflows/link-check.yml`) is the verification step; you can
  also check links manually before opening a PR.
- Commit messages: one line, plain language, what changed and why.
