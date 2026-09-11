# LinkedIn article

Generated from [`AgenticDesignPatterns.ipynb`](../AgenticDesignPatterns.ipynb).

**Title:** Agentic Design Patterns

| File | Use |
| --- | --- |
| `linkedin-article.html` | Open in a browser, select all, copy, paste into the LinkedIn editor |
| `linkedin-article.md` | Markdown source, for Medium / Dev.to / a GitHub README |
| `images/00-cover-1920x1080.png` | Article cover image |
| `images/00-share-1200x627.png` | Image for the accompanying feed post |
| `images/*.png` | The 13 diagrams, 1448 px wide, upload these into the article |

## Publishing to LinkedIn

1. Open `linkedin-article.html` in a browser.
2. Select all (Ctrl+A), copy (Ctrl+C).
3. In LinkedIn go to **Write article**, click into the body, paste.
   Headings, bold, bullets, numbered lists and quotes carry across. Images do not.
4. Paste the title separately into the title field.
5. Add the images. They appear in this order, each directly under the paragraph
   that introduces it:

| # | File | Goes after |
| --- | --- | --- |
| 1 | `01-why-agents.png` | "...keep working until the goal is met." |
| 2 | `02-four-pillars.png` | "...properties that separate an agent..." |
| 3 | `04-prompt-chaining.png` | 3.1 Prompt Chaining |
| 4 | `05-routing.png` | 3.2 Routing |
| 5 | `06-parallelization.png` | 3.3 Parallelization |
| 6 | `07-reflection.png` | 3.4 Reflection |
| 7 | `08-tool-use.png` | 3.5 Tool Use |
| 8 | `09-planning.png` | 3.6 Planning |
| 9 | `10-multi-agent-supervisor.png` | 3.7 Multi-Agent Collaboration |
| 10 | `11-group-chat-debate.png` | Variant: Group Chat / Debate |
| 11 | `12-memory.png` | 3.8 Memory |
| 12 | `13-human-in-the-loop.png` | 3.9 Human-in-the-Loop |
| 13 | `14-picking-a-pattern.png` | 4. How to pick one |

Keeping the browser preview open side by side makes this quick, since the HTML
shows each diagram exactly where it belongs.

`03-setup.png` is not used in the article. It is kept for the notebook.

## Notes

- LinkedIn articles do not support tables, so every table from the notebook is a
  bullet list here.
- LinkedIn has no syntax highlighting. Code appears as monospaced blocks, which is
  why the snippets are kept to a few lines each.
- Suggested cover image: `images/00-cover-1920x1080.png` (1920x1080, LinkedIn's
  recommended article cover ratio). Use `images/00-share-1200x627.png` on the
  feed post that announces the article.
- Reading time is roughly 7 minutes at about 1,600 words.

## Hashtags

LinkedIn articles have no separate tag field. Add hashtags at the end of the
article body, and on the feed post that shares it. Three to five is the sweet
spot:

`#AIAgents` `#LangGraph` `#LLM` `#SoftwareArchitecture` `#GenerativeAI`

## Regenerating

The images are rendered from the Mermaid blocks in the notebook. If you change a
diagram there, re-export that PNG so the article stays in sync.
