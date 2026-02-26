# Karwan AI — Single-Page Website Specs

## Purpose

Marketing and landing page for Karwan AI. Single HTML file with embedded CSS and JavaScript. No build system, no framework — just one `index.html` that looks like a $10,000 agency build.

The site communicates one idea: **Karwan AI is an AI employee that works for your small business 24/7, so you don't have to hire someone.**

Tone: direct, confident, simple. No jargon. Speak like you're talking to a busy, skeptical small business owner.

---

## Tech Stack

- **Single file:** `index.html` with embedded `<style>` and `<script>`
- **Fonts:** Google Fonts — Inter (Latin), Noto Nastaliq Urdu (Dari/Pashto)
- **No dependencies.** No build step. Open in browser and it works.

---

## Design System

**Overall aesthetic:** Light, airy, modern SaaS — NOT dark.

- Page background: soft sky blue gradient (`#C8D9E8` to `#D6E4F0`)
- Content cards: white floating containers, `border-radius: 32px`, soft `box-shadow`
- Typography: Inter for Latin, Noto Nastaliq Urdu for Dari/Pashto (RTL, `dir="rtl"`)
- Buttons: Primary = black pill, white text. Secondary = white pill with border
- Accent color: warm amber `#F5A623`
- Spacing: generous padding, sections breathe, nothing cramped

**Tier card colors:**
- Bronze: `#CD7F32`
- Silver: `#A8A9AD`
- Gold: `#FFD700` (shimmer on hover)
- Platinum: `#E5E4E2` (animated gradient border)

---

## Brand Details

- Name: **Karwan AI** · **کاروان**
- Dari/Pashto meaning: کاروان = caravan — never stops
- Accent: `#F5A623` (icons, badges, highlights)
- Tone: cultural pride + modern professionalism

---

## Dari/Pashto Moments

1. **Hero watermark** — "کاروان" giant ghost text, `opacity: 0.06`
2. **Hero soul line** — "کاروان هیڅکله نه درېږي" + gray italic translation: "The caravan never stops"
3. **How It Works quote** — "کاروان د منزل پروا نه کوي، یوازې مخ په وړاندې ځي" + translation: "The caravan does not worry about the destination — it only moves forward"
4. **Why Karwan pill** — "ولې کاروان؟" (Why Karwan?)
5. **Final CTA** — "Your caravan never stops. · ستاسو کاروان هیڅکله نه درېږي"
6. **Footer tagline** — "Nonstop AI for your business · د خپل سوداګرۍ لپاره بې‌وقفه هوش مصنوعي"

All Dari/Pashto uses `dir="rtl"` and Noto Nastaliq Urdu font.

---

## Sections

### 1. Navigation (inside hero card)
- Logo: "⬡ Karwan AI · کاروان"
- Links: Services, How It Works, Pricing, About
- CTA: "Get Started" (black pill)
- Mobile: hamburger menu

### 2. Hero (large white floating card)
- Badge: "Always On — Your AI Employee Never Sleeps"
- Headline: "Your Business Never Stops. Neither Does Karwan."
- Dari soul line + translation
- Subtext about what Karwan does
- CTAs: "Get Started" + "See Our Services"
- CSS dashboard mockup with stat cards + activity graph
- Giant "کاروان" watermark behind (opacity 0.06)

### 3. Services (4 tier cards in 2x2 grid)
- Bronze (3,000 AFN): Foundation setup
- Silver (5,000 AFN): Multi-channel assistant
- Gold (12,000 AFN): Autonomous employee — "Most Popular"
- Platinum (20,000 AFN): 24/7 cloud executive
- Each card: tier badge, Dari label, description, deliverables, price, CTA
- Left border accent in tier color

### 4. How It Works (3 steps + dotted line)
- Tell Karwan Your Goal
- Karwan Builds the Workflow
- It Executes — Nonstop
- Dari quote after steps

### 5. Why Karwan is Different
- Side-by-side comparison: "Other Tools" vs "Karwan AI"
- Pill label: "ولې کاروان؟"

### 6. Social Proof (3 testimonials)
- Ahmad R., Sara M., David K.

### 7. Final CTA
- Bilingual closing line
- Email waitlist form with JS success state

### 8. Footer
- Logo, bilingual tagline, links, copyright

---

## Functional Requirements

- Smooth scroll navigation
- Intersection Observer scroll-fade-in on all cards
- Email capture with JS success state (no backend)
- Mobile responsive with hamburger menu
- Card hover: `translateY(-4px)` + stronger shadow
- RTL rendering on all Dari/Pashto elements
- Tier cards: left border in tier color
- Gold card: shimmer animation on hover
- Platinum card: animated gradient border

---

## Copy Tone

Direct. Human. Confident. No buzzwords.
Dari/Pashto = cultural pride, not decoration.
An Afghan founder should feel seen. Any small business owner should feel understood.
Speak to the person doing everything alone, drowning in emails, watching leads go cold.
Karwan is the employee they could never afford — until now.
