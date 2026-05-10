# Caterham — Scuderia Bandeiras Race Experience

Landing page for the Scuderia Bandeiras × Caterham Motorsport race experience offer.

## Stack

- Single-file HTML (`index.html`) with inline CSS and JS — no build step
- Brand assets in `Brand/` (images, prototype HTML)
- Portuguese (pt-BR) copy throughout

## Development

Open `index.html` directly in a browser — no server required.

For the prototype/brand reference, open `Brand/PROTOTIPO-Caterham-Bandeiras.html`.

## Claude Council

This project uses [Claude Council](https://github.com/hex/claude-council) to consult multiple AI providers in parallel.

### Setup

```bash
# 1. Install the plugin
/plugin marketplace add hex/claude-marketplace
/plugin install claude-council

# 2. Set at least one provider API key
export OPENAI_API_KEY="..."
# or: GEMINI_API_KEY, XAI_API_KEY, PERPLEXITY_API_KEY
# or install the Codex / Gemini CLI (uses your existing subscription)

# 3. Ask anything
/claude-council:ask "Should I use UUID or BIGINT primary keys for a SaaS users table?"
```

### Useful queries for this project

```bash
/claude-council:ask "Best approach for a responsive single-page landing page in pure HTML/CSS?"
/claude-council:ask "How should I optimise WebP images for a motorsport landing page?"
/claude-council:ask "SEO best practices for a pt-BR event landing page?"
```
