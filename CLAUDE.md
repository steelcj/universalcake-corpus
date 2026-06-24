# CLAUDE.md — universalcake-corpus

## Project overview

This is the document corpus for **Universal Cake**, a framework for evaluating technology in human terms across seven interdependent dimensions: accessibility, sustainability, interoperability, transparency, resilience, human well-being, and knowledge preservation. Accessibility is upstream of everything else.

The project is authored by **Christopher Steel**, founder of Universal Cake, based in Verdun, Quebec, Canada. AI assistance from Claude (Anthropic) is credited in all documents.

## License

All documents are licensed under **CC BY-SA 4.0**. See `LICENSE.md` at the repository root.

## Document conventions

### Naming
- Kebab-case filenames with semantic versioning: `description-vX.Y.Z.md`
- The `universal-cake--` prefix has been dropped — directory structure provides context
- Semantic versioning in both filename and document metadata header
- New versions create new files — do not overwrite previous versions
- Previous versions are kept in `versions/` subdirectories within each section

### Metadata
- **Articles and guides** use inline metadata below the title:
  ```
  Version: X.Y.Z
  Status: Draft
  License: CC BY-SA 4.0
  ```
- **Marp presentation decks** use YAML frontmatter with: marp, theme, paginate, title, author, date, version, status, license

### Style
- Plain language for general audiences
- APA 7 citations where applicable
- CC BY-SA 4.0 on all documents
- AI assistance attribution in the license footer
- No emojis

## Project structure

```
.
├── CLAUDE.md
├── LICENSE.md
│
├── core/                                  # The framework document itself
│   ├── an-introduction-v0.3.2.md          # Current version
│   └── versions/                          # v0.1.0 through v0.3.1
│
├── analysis/                              # Systems thinking and Meadows work
│   ├── digital-sovereignty-v0.1.1.md      # Meadows analysis of digital sovereignty
│   ├── systems-thinking-assessment-v0.1.0.md
│   ├── meadows-framework-mapping-v0.2.0.md
│   ├── vocabulary-cascades.md
│   ├── startup-cascade-draft-v0.1.0.md
│   ├── loops/                             # Feedback loop details
│   │   ├── accessibility-reinforcing-v0.1.0.md
│   │   ├── language-infrastructure-reinforcing-v0.1.0.md
│   │   └── balancing-v0.1.0.md
│   ├── detail/                            # Meadows report components
│   │   ├── stocks-v0.1.0.md
│   │   ├── flows-v0.1.0.md
│   │   ├── delays-v0.1.0.md
│   │   ├── leverage-points-v0.1.0.md
│   │   └── system-traps-v0.1.0.md
│   └── versions/
│
├── articles/                              # Standalone web-ready articles
│   ├── the-80-20-lie-v0.1.0.md
│   ├── you-dont-own-what-you-cant-rebuild-v0.1.0.md
│   ├── innovation-lives-at-the-edge-v0.1.0.md
│   ├── language-is-infrastructure-v0.1.0.md
│   └── the-cascade-priority-v0.1.0.md
│
├── website/                               # Pages for universalcake.com
│   ├── landing-page-v0.1.0.md
│   ├── faq-v0.1.0.md
│   ├── glossary-v0.1.0.md
│   └── self-assessment-checklist-v0.1.0.md
│
├── decks/                                 # Marp presentation decks
│   ├── ats-2026-pitch-deck-v0.1.1.md
│   ├── accessibility-and-sovereignty-v0.1.0.md
│   └── versions/
│
├── accelerator/                           # ATS 2026 application materials
│   ├── application.md
│   └── one-pager-v0.1.0.md
│
├── research/                              # Reference materials and data
│   ├── vendor-lock-in/                    # Vendor lock-in analysis documents
│   ├── quebec-spend/                      # Quebec public spend on Microsoft & Amazon
│   ├── website-evaluations/               # PageSpeed and performance audits
│   ├── movement-building.md
│   └── my-virtuous-tornado.md
│
├── guides/                                # Plain language guides
│   ├── git-guide-v0.1.1.md
│   └── versions/
│
├── indexes/                               # Document indexes
│   ├── web-ready-document-index-v0.1.0.md
│   └── tech-tuesday-article-index-v0.1.0.md
│
├── nutshelled/                            # Condensed summaries
│   └── nutshelled.md
│
└── archive/                               # Superseded files and exact duplicates
```

## Key sources referenced across documents

- Steel, C. (2026). *Universal Cake -- An Introduction* (v0.3.2)
- Chartier, R. (2025–2026). *State of Mind* [LinkedIn newsletter series]
- Meadows, D. H. (2008). *Thinking in Systems: A Primer*
- Meadows, D. H. (1999). *Leverage Points: Places to Intervene in a System*
- Treviranus, J. (2019). *Inclusive Design: The Bell Curve, the Starburst and the Virtuous Tornado*
- Buckup, S. (2009). *The Price of Exclusion* (ILO)
- Zheng, Y., & Walsham, G. (2021). *Inequality of what?* Information and Organization
- Odum, E. P. (1953). *Fundamentals of Ecology*

## Key framework concepts

- **Accessibility is upstream** — without the door, the rest of the house is irrelevant
- **Language is infrastructure** — load-bearing, not cosmetic
- **Innovation lives at the edge** — the ecotone effect and the Virtuous Tornado
- **Sovereignty is a prerequisite for accessibility** — if someone else controls the platform, someone else decides who gets in
- **The cascade priority** — sustain the people first, then open the doors, then build what they produce together
- **The rebuildability test** — if this system disappeared tomorrow, could you recreate its essential function?
- **Compounded digital exclusion** — when every product ignores the same 20%, the same people lose everything

## Working with this project

- When producing new documents, draw from existing corpus material — do not introduce new claims without discussion
- The current canonical version of the introduction is **v0.3.2** at `core/an-introduction-v0.3.2.md`
- The digital sovereignty analysis current version is **v0.1.1** at `analysis/digital-sovereignty-v0.1.1.md`
- The Meadows framework mapping current version is **v0.2.0** at `analysis/meadows-framework-mapping-v0.2.0.md`
- Web-ready documents are indexed in `indexes/web-ready-document-index-v0.1.0.md`
- Presentation decks use Marp format and can be rendered with `marp` CLI or Marp for VS Code
- The `archive/` directory contains exact duplicates and files superseded by newer versions — do not use these as source material
