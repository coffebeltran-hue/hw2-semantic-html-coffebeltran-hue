[ai-bitacora.md](https://github.com/user-attachments/files/30921209/ai-bitacora.md)
# AI Usage Log — WebDining Project

## Purpose

This log documents the specific changes made to the WebDining project files with the assistance of an AI tool (Claude). It is intended to provide transparency about which parts of the project received AI support and what that support consisted of.

## Changes Made

### 1. Converted styling approach from CSS to semantic HTML

The original page relied on CSS-based structure for layout and presentation. With AI assistance, the markup was reworked to use semantic HTML5 elements (`header`, `nav`, `main`, `section`, `article`, `footer`) instead of relying on styling alone to convey structure.

### 2. Added semantic markup

Semantic tags were added throughout the page to properly convey the meaning and hierarchy of the content:
- `<header>`, `<nav>`, `<main>`, and `<footer>` for overall page structure.
- `<section>` elements with descriptive `id`s to group related content (e.g., problem, solution, users, login, team).
- `<article>` elements for self-contained content blocks (feature descriptions, team member profiles).
- A consistent heading hierarchy (`h1` → `h2` → `h3`) with no skipped levels.
- Proper `<label for="">` associations and `autocomplete` attributes on form fields.

### 3. Updated navigation links

The navigation script/links were updated so that internal anchor links and the "Home" link correctly point to the live project page:
`https://dsaw-2026-2.github.io/hw1-team-readme-and-project-kickoff-jeronimoqume-cloud/`

This ensures the "About the Team" page and the main page navigate consistently to the correct destinations.

## Notes

All other content — including the project description, feature list, team descriptions, and overall page design — was authored by the project team. AI assistance was limited to the structural and navigation changes described above.
