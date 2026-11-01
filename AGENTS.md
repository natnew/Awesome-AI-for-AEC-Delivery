# AGENTS.md

## Project Overview

An "awesome list": a curated Markdown catalogue of AI tools, datasets, research and standards for the Architecture, Engineering & Construction (AEC) lifecycle. The whole project is one file, `README.md`. There is no code, build, package manager or test suite.

Structure of `README.md`: taxonomy overview → BIM Primer → Contents → five layers (Foundations, Data & Interoperability, AI Paradigms, Lifecycle Applications, Trust & Governance) plus Datasets, Papers, Communities, Contributing, License.

## Commands

No setup is needed. Useful checks before committing:

- Preview rendering: view `README.md` in a Markdown viewer (it contains a Mermaid diagram).
- Find duplicates: `grep -n "<resource name or domain>" README.md`
- Check a link: `curl -sIL -o /dev/null -w "%{http_code}\n" <url>`

## Editing Rules

- Read [CONTRIBUTING.md](CONTRIBUTING.md) first; it is the source of truth for scope and entry format.
- Entry format: `- <icon> [Name](url) - One-sentence description ending with a full stop.` Icons: 🟢 open source, 💼 commercial, 📄 paper, 📊 dataset, 🎓 learning. Copy the style of neighbouring entries.
- Add to the most specific existing section. Keep that section's ordering.
- If you add or rename a heading, update the **Contents** section and any anchor links (including the Paradigm × Lifecycle table).
- One resource per PR. Do not bulk-reformat unrelated lines.
- Never invent resources, URLs, versions or claims. Only add entries you have verified exist and are maintained; fetch the URL to confirm.
- Keep a neutral, factual tone: no hype or "best". Do not mix British and American spelling within an entry.
- Treat AEC claims with care: it is a regulated, safety-critical field. Do not imply AI replaces professional accountability.
- Update the "Last reviewed" line at the bottom only when doing a deliberate review.

## Pull Requests

- Title: `Add <Name> to <Section>` (or `Fix: <what>` / `Docs: <what>`).
- Disclose any affiliation with an added resource.
- Work on the assigned branch; open the PR as a draft.

## Licence

CC0 1.0. Contributions are dedicated to the public domain.
