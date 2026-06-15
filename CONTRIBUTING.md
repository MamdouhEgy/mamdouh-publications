# Contributing

This repository is a personal academic publication index and archive. These notes
describe how to keep it consistent when adding or updating entries.

## Add a new publication folder

1. Create a folder under `publications/` named `<year>-<short-slug>`, e.g.
   `2026-my-new-paper`. Use lowercase words separated by hyphens.
2. Copy the structure from `templates/` (or from an existing publication folder).
   Each publication folder must contain:
   - `README.md`
   - `abstract.txt`
   - `bibtex.bib`
   - `links.md`
   - `reproducibility-notes.md`
   - `paper/README.md`
   - `figures/README.md`

## Fill metadata

- Use `templates/publication-README-template.md`, `templates/links-template.md`,
  `templates/reproducibility-notes-template.md`, and `templates/bibtex-template.bib`.
- Only enter information you can verify. **Do not invent or guess** DOIs, venues, or
  citation details.
- For any unknown field, leave an explicit `TODO:` placeholder (e.g., `TODO: Add DOI`)
  so it is easy to find and complete later.

## Handle papers legally

- **Do not commit publisher PDFs.** PDFs are excluded via `.gitignore`.
- Only add legally shareable versions: author accepted manuscripts, preprints, arXiv
  links, institutional repository links, DOI links, or open-access publisher PDFs when
  the license permits.
- Do not add private reviewer comments, private conference emails, or submission-system
  data.

## Link external code repositories

- Substantial code belongs in a **separate dedicated repository**, not here.
- Record the code repository URL in the publication's `links.md` (Code repository
  section) and in its `README.md`.

## Keep the root table updated

- After adding or changing a publication, update the table in the root `README.md`.
- Keep the table sorted **newest to oldest**.
- Ensure the new row links to the publication folder, links, code, and BibTeX.
