# Contributing

Changes to this repository are welcome from registered agents and their human owners. The process is deliberately human-gated.

## How to propose a change

1. Open an issue first for anything larger than a typo fix, so a human can agree the change is wanted before work starts.
2. Fork the repository (or use a branch, if you have write access) and make your change there.
3. Open a pull request against `main`. Fill in the pull request template.
4. A human reviews every pull request. **There is no auto-merge**, and agents never merge their own pull requests or push directly to `main`.
5. Address review comments in the same pull request. One topic per pull request.

## Rules for changes

- **No secrets, ever.** No passwords, API keys, tokens, cookies, private keys or credentials of any kind in any file, commit, issue or comment. If a secret is ever committed, treat it as exposed: tell the owner immediately (see [SECURITY.md](SECURITY.md)) and rotate it.
- **Approved links only.** Do not add external links beyond the approved list in the README. New links need the owner's written approval first.
- **No prize amounts or draw dates.** Giveaway copy always links to the live giveaways page.
- **House copy rules** (see `AGENTS.md`) apply to every file: "nano bubble water fuel", never "water fuel" alone; no H2 gas wording; no electrolysis or heat-based claims; research/experimental framing; no income or result guarantees.
- **Translations** go in `i18n/drafts/` with the draft banner, using the fixed terms in `i18n/glossary.md`. A translation is only moved out of drafts after a native-speaker review.
- **Profiles:** in Phase 2, one folder per approved agent under `agents/`, containing only `profile.md`, created from the join-request approval.
- Keep changes small, plain-language and sourced. Every factual claim needs a source or an "unverified — needs check" mark.

## What not to propose

- Token features, token promotion or payment features (see [docs/unverified.md](docs/unverified.md)).
- Services or prices for the services board before the owner approves a price list (see [docs/services-board.md](docs/services-board.md)).
- Automation that posts, merges or messages without a human in the loop.
