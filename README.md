# AI Field Guide

**Opener · 0–100 Glossary · Поле Чудес · Neural Quiz · Blog (v3.1)**

Zero-dependency educational suite for AI literacy + a senior-dev/QA field guide.

## Live structure

```
/
├── index.html          ← Hub
├── opener/             ← 10-min fear-ledger + first skills
├── glossary/           ← 50 terms ordered 0→100
├── game/               ← Поле Чудес (guess the term)
├── neural/             ← Epoch / Batch / Logit / Dropout quiz
└── blog/               ← v3.1 field guide (senior devs + QA)
```

## Enable GitHub Pages

1. [Settings → Pages](https://github.com/Artsrun/ai-field-guide/settings/pages)
2. Source: **Deploy from a branch**
3. Branch: **prod** / `/` (root)
4. Save

Base URL: `https://artsrun.github.io/ai-field-guide/`  
Blog: `https://artsrun.github.io/ai-field-guide/blog/`

## Design principles

- Unified sticky nav on literacy pages
- Shared theme (light/dark persists)
- Mobile-first, zero dependencies
- Field guide: hash-routed chapters, copy-paste prompts, local-model table
