# The Fifth Science — Wiki

A personal, LLM-assisted wiki for Exurb1a's 2018 short-story collection *The Fifth Science* — a 13-story cycle set in a shared future-history universe that spans roughly 500 years on the in-universe **A.L. (Anno Logicae)** calendar, anchored around the rise of the **Galactic Human Empire** and the conjecture that consciousness is a fundamental force of nature alongside the four classical ones (hence *the fifth*).

Published at **https://gogoliri.github.io/the-fifth-science-wiki/**.

## What's in here

The wiki is organised by page type:

- **Stories** — one page per chapter, with summary, entities introduced, themes, and connections to other stories.
- **Characters** — major and minor figures across the book's 500-year timespan.
- **Places** — worlds, systems, and locations.
- **Ships** — voidships, generation ships, and Ribbondash vessels.
- **Factions** — empires, republics, and polities.
- **Technologies** — in-universe science and engineering (Fidon, Ribbondash, Nootics, etc.).
- **Concepts** — philosophical and scientific ideas (panpsychism, the fifth science, mentalic ontology).
- **Events** — named historical events and eras.

Every page cross-links to every other via wiki-style `[[links]]`, and the site is built with [Quartz 4](https://quartz.jzhao.xyz/) so you get backlinks, a graph view, full-text search, and an Obsidian-compatible source.

## Structure

```
content/          The wiki pages — Markdown with YAML frontmatter, Obsidian-flavoured
quartz/           Quartz 4 site generator source
quartz.config.ts  Site configuration (title, base URL, ignore patterns)
```

`content/` is also a valid Obsidian vault — open it directly in Obsidian to edit the wiki locally, and Quartz will build the published site from the same files.

## Build locally

```bash
npm install
npx quartz build --serve
```

Then visit http://localhost:8080.

## Scope and spoilers

Everything in the book is fair game. The wiki is a reference, not a review — it assumes you've read the chapter you're looking at.

## What's *not* in here

The full source text of the book is **not** committed to this repository — it's copyrighted material. The wiki pages cite chapters by name and include brief, fair-use quotations where they illuminate a concept, but the raw chapter text lives only on the maintainer's local machine during the ingest workflow.

## Credits

- *The Fifth Science* © Exurb1a, 2018. Buy the book — it's good.
- Built on [Quartz 4](https://github.com/jackyzha0/quartz) by Jacky Zhao (MIT-licensed; see `LICENSE.txt`).
