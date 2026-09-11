# LinkedIn article

Generated from [`AgenticDesignPatterns.ipynb`](../AgenticDesignPatterns.ipynb).

| File | Use |
| --- | --- |
| `linkedin-article.html` | Open in a browser, select all, copy, paste into the LinkedIn editor |
| `linkedin-article.md` | Markdown source, for Medium / Dev.to / a GitHub README |
| `images/*.png` | The 13 diagrams, 1448 px wide, upload these into the article |

## Publishing to LinkedIn

1. Open `linkedin-article.html` in a browser.
2. Select all (Ctrl+A), copy (Ctrl+C).
3. In LinkedIn go to **Write article**, click into the body, paste.
   Headings, bold, bullets, numbered lists and quotes carry across. Images do not.
4. Each image has a yellow `INSERT IMAGE: images/xx.png` marker above it.
   At each marker use the editor's image button to upload that file, then delete the marker line.
5. Paste the title separately into the title field.

## Notes

- LinkedIn articles do not support tables, so every table from the notebook is a
  bullet list here.
- LinkedIn has no syntax highlighting. Code appears as monospaced blocks, which is
  why the snippets are kept to a few lines each.
- Suggested cover image: `images/02-four-pillars.png`.
- Reading time is roughly 7 minutes at about 1,600 words.

## Regenerating

The images are rendered from the Mermaid blocks in the notebook. If you change a
diagram there, re-export that PNG so the article stays in sync.
