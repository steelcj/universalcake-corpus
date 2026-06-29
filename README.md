# universalcake-corpus

The document corpus for **Universal Cake**, a framework for evaluating technology in human terms.

Universal Cake asks a different question than the industry default. Instead of "does it work?" it asks "does it work in a way that supports the humans who depend on it?" It evaluates technology across seven interdependent dimensions — with accessibility upstream of everything else.

> Technology that **builds, replenishes, and bridges** rather than **extracts, consumes, and diminishes.**

---

## The seven dimensions

| Dimension | What it asks |
|-----------|-------------|
| **Accessibility** | Can people actually use this — in their language, on their device, with their abilities? |
| **Sustainability** | Can this last without burning out its maintainers or its users? |
| **Interoperability** | Can your data move freely? Can you leave? |
| **Transparency** | Can you understand what the system is doing? |
| **Resilience** | Can this survive disruption — a company closing, a policy change? |
| **Human well-being** | Does this support or undermine the people who depend on it? |
| **Knowledge preservation** | Will your information still be readable in twenty years? |

Accessibility is not one dimension among seven. It is the door to the house. Without it, nothing else matters.

---

## Repository structure

```
core/              The framework document (An Introduction, current: v0.3.2)
analysis/          Systems thinking, Meadows framework, sovereignty analysis, feedback loops
articles/          Standalone web-ready articles
website/           Pages for universalcake.com
decks/             Marp presentation decks
accelerator/       ATS 2026 application materials
research/          Reference materials, vendor lock-in analysis, Quebec spend data
guides/            Plain language guides
indexes/           Document indexes
nutshelled/        Condensed summaries
archive/           Superseded files and duplicates
```

Each section contains a `versions/` subdirectory for previous document versions where applicable.

---

## Key concepts

- **Accessibility is upstream** — without the door, the rest of the house is irrelevant
- **Language is infrastructure** — load-bearing, not cosmetic
- **Innovation lives at the edge** — the ecotone effect and the Virtuous Tornado (Treviranus, 2019)
- **Sovereignty is a prerequisite for accessibility** — if someone else controls the platform, someone else decides who gets in
- **The cascade priority** — sustain the people first, then open the doors, then build what they produce together
- **The rebuildability test** — if this system disappeared tomorrow, could you recreate its essential function?
- **Compounded digital exclusion** — when every digital product ignores the same 20%, the same people lose everything, only it happens much faster

---

## Versioning and conventions

### Versioning

Documents use [semantic versioning](https://semver.org/) in both the filename and the document metadata header:

```
the-cascade-priority-v0.1.0.md
```

**New versions create new files.** Do not overwrite a previous version — copy the file, bump the version in the filename and metadata, and edit the new copy. Move the previous version into the `versions/` subdirectory within its section.

- **Patch** (v0.1.0 → v0.1.1): Corrections, typos, minor clarifications that do not change the argument
- **Minor** (v0.1.1 → v0.2.0): New sections, restructured content, expanded arguments
- **Major** (v0.2.0 → v1.0.0): Published release or fundamental rewrite

### Naming

- Kebab-case filenames: `description-vX.Y.Z.md`
- No `universal-cake--` prefix — the directory structure provides context
- Place new documents in the appropriate directory (`articles/`, `website/`, `decks/`, etc.)

### Document metadata

Articles and guides use inline metadata below the title:

```markdown
# Document Title

Version: 0.1.0
Status: Draft
License: CC BY-SA 4.0
```

Marp presentation decks use YAML frontmatter:

```yaml
---
marp: true
theme: default
paginate: true
title: "Deck Title"
author: "Christopher Steel, Universal Cake"
date: "2026-06-24"
version: "0.1.0"
status: "Draft"
license: "CC BY-SA 4.0"
---
```

### Style

- Plain language for general audiences
- APA 7 citations where applicable
- AI assistance attribution in the license footer of each document
- All documents are CC BY-SA 4.0

### Committing

- Draw from existing corpus material — do not introduce new claims without discussion
- Commit messages should describe what changed and why
- Presentation decks can be rendered with `marp` CLI or Marp for VS Code

---

## Key sources

- Steel, C. (2026). *Universal Cake -- An Introduction* (v0.3.2)
- Chartier, R. (2025--2026). *State of Mind* [LinkedIn newsletter series]
- Meadows, D. H. (2008). *Thinking in Systems: A Primer*. Chelsea Green.
- Meadows, D. H. (1999). *Leverage Points: Places to Intervene in a System*
- Treviranus, J. (2019). *Inclusive Design: The Bell Curve, the Starburst and the Virtuous Tornado*. IDRC, OCAD University.
- Buckup, S. (2009). *The Price of Exclusion*. International Labour Organization.
- Zheng, Y., & Walsham, G. (2021). Inequality of what? *Information and Organization*, 31(1), 100341.
- Odum, E. P. (1953). *Fundamentals of Ecology*. Saunders.

---

## Author

**Christopher Steel**
Founder, Universal Cake
Verdun, Quebec, Canada

Documents in this repository were produced with AI assistance from Claude (Anthropic).

---

## License

This work is licensed under [Creative Commons Attribution-ShareAlike 4.0 International (CC BY-SA 4.0)](https://creativecommons.org/licenses/by-sa/4.0/). See [LICENSE.md](LICENSE.md) for details.
