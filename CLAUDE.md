# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

Karwan AI is an autonomous AI employee for small businesses. "Karwan" means "caravan" in Dari and Pashto — it never stops moving. The product handles tasks like managing emails, replying to clients, and following up on leads automatically, 24/7.

Key design principle: **outcome-focused, not feature-focused**. Users tell it what they want to achieve, and it figures out how to get it done.

## Architecture

- **Single-file website:** `index.html` with embedded CSS and JavaScript
- **No build system, no framework, no dependencies**
- Fonts loaded from Google Fonts: Inter (Latin), Noto Nastaliq Urdu (Dari/Pashto)

## Design Tokens

- Background: sky blue gradient `#C8D9E8` → `#D6E4F0`
- Cards: white, `border-radius: 32px`, soft shadows
- Primary button: black pill, white text
- Accent: `#F5A623` (amber)
- Tier colors: Bronze `#CD7F32`, Silver `#A8A9AD`, Gold `#FFD700`, Platinum `#E5E4E2`

## Cultural Elements

All Dari/Pashto text uses `dir="rtl"` and `font-family: 'Noto Nastaliq Urdu'`. These are moments of cultural pride woven throughout the page — hero watermark, soul line, How It Works quote, Why Karwan pill, Final CTA, and footer tagline.

## Key Files

- `index.html` — the entire website
- `specs.md` — detailed specifications
- `about.md` — brand story and background
