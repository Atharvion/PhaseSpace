# PhaseSpace
A personal reading archive for people who hoard links. Paste any URL — papers, videos, articles, GitHub repos — and it gets saved, categorized, and displayed in a clean dark interface. No accounts, no servers, no tracking. Everything lives in your browser's localStorage.

## What it does

- **paste links** → auto-fetches title, thumbnail, and description
- **auto-classifies** into Physics, Mathematics, Computer Science, Philosophy, Economics, Art — with subcategories like Condensed Matter, Machine Learning, Game Theory, etc.
- **search** across everything
- **mark read**, add notes, edit titles
- **export/import** JSON backups

## Classifier

The auto-classifier uses Claude (Haiku via the Anthropic API) to read page content and assign categories. It works reasonably well for arXiv papers and things with descriptive titles, but honestly it's still pretty rough — opaque DOIs, paywalled pages, and weirdly titled YouTube videos will end up miscategorised fairly often. Working on it.

In the meantime it's easy to fix manually: every card has a **MOVE** button that lets you reassign it to any category and subcategory in two clicks. Just treat auto-classify as a first guess.
