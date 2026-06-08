# ModSleuth Demo

Static, self-contained visualization of LLM dependency graphs recovered
by ModSleuth. No backend required.

## Tabs
- **OLMo 3** / **Nemotron 3 Super** / **DR-Tulu** / **SmolLM3** — per-target
  dependency subgraphs (depth-3 BFS from each seed).
- **Recursive · 4 Open LLMs** — merged graph from recursively investigating
  all four targets.

## Deploy to GitHub Pages
1. Push this folder as `docs/` (or the repo root).
2. In repo settings → Pages, set the source.
3. Fully static — `index.html` fetches `data/*.json` over relative paths.

Node positions for the ecosystem graph are pre-computed, so even the
large graph renders in ~1-2 seconds.
