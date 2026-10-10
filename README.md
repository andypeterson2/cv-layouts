# cv-layouts

Layout bundles for the LaTeX résumé editor. Each folder is one layout; its zip is attached to a release so the editor can install it from a URL.

- `awesome-cv-inline-skills` — Awesome CV with each skill group set as one full-width paragraph (bold label, colon, then the list), so a PDF parser reads every group as one run of text.

To build a zip: `zip -qrX <id>.zip <id> -x '.*'`

`awesome-cv-inline-skills/class/CVSans-*.otf` are Source Sans 3 (Adobe, SIL Open Font License 1.1, see `CVSans-OFL.txt`), renamed because the space and hyphen glyphs map to U+0020 and U+002D only.
