# Personal Homepage

This repository hosts my academic personal website.

The site is built with the [**al-folio**](https://github.com/alshedivat/al-folio) Jekyll theme. Many thanks to the al-folio authors and contributors for the template.

## Updating content

* **News section (homepage):** edit `_data/news.yml`.
* **Selected papers (homepage):** edit `_bibliography/papers.bib` and set `selected=true` for entries to show.
* **`text-color-box`:** reusable block with light blue background and centered bold heading. Defined in `_sass/_layout.scss`; used in `_pages/about.md` (Misc) and `_pages/research.md` (Research Overview). Wrap content in `<div class="text-color-box" markdown="1">...</div>` to reuse.
