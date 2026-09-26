# Positional Encoding in Transformers

A single-page interactive explainer on **why Transformers need positional encoding**, **how sinusoidal encoding works**, and **why modern LLMs have moved to RoPE (Rotary Positional Encoding)** — presented three different ways in one page.

## 🔗 Live version

Once GitHub Pages is enabled for this repo (Settings → Pages → Deploy from branch → `main` / root), this will be live at:

```
https://<your-username>.github.io/<repo-name>/positional-encoding.html
```

Until then, you can open `positional-encoding.html` directly in any browser — no build step, no dependencies.

## What's inside

One HTML file, three tabs:

| Tab | What it is |
|---|---|
| **The Story** | A narrative analogy — "The Tokens Who Forgot Their Place" — for people who want the intuition first |
| **Study Map** | A visual, skimmable overview: the end-to-end flow, six annotated stages, and a sinusoidal-vs-RoPE comparison table |
| **Technical Walkthrough** | The full reasoning trail with formulas — the attention equation, the sinusoidal PE formula, a worked example, and the RoPE rotation math |

Switching tabs is instant (client-side JS, no reload).

## Why

Positional encoding is usually explained one way — formula first, intuition never. This page tries all three entry points, so a reader can start wherever they learn best and go deeper from there.

## Tech

Just HTML, CSS and vanilla JS in a single file. No build tools, no frameworks, nothing to install. Fork it, edit it, or lift sections into your own notes.

## Credits

Written and built with [Claude](https://claude.com).
