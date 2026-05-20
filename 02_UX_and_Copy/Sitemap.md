# HIS HAIR — MVP Shopify Sitemap
### Lean. High-Conversion. Every page earns its place.

---

## Sitemap Architecture

```
HIS HAIR (hishair.co.za)
│
├── / ——————————————————————— HOMEPAGE (The Conversion Engine)
│   ├── Hero: "The Edge You Thought You'd Lost" + CTA → Quiz
│   ├── Proof: "Restoration in Motion" (3 HD videos)
│   ├── The Match Quiz CTA (sticky)
│   ├── How It Works (3 steps, no more)
│   ├── Social Proof (anonymised testimonials)
│   └── Footer → all nav links
│
├── /match ————————————————— THE MATCH QUIZ (Primary Funnel Entry)
│   ├── Step 1: Activity level (Gym / Office-heavy / Mixed)
│   ├── Step 2: Desired density (Natural / Fuller)
│   ├── Step 3: Maintenance preference (Low / Standard)
│   ├── Step 4: Scalp tone (colour swatch selector)
│   ├── Step 5: Budget tier (discreet slider)
│   └── Result → "Your Restoration Profile" → recommended product + consult CTA
│
├── /systems ——————————————— COLLECTION: HAIR SYSTEMS (Shop)
│   ├── Filter: Density / Lace type / Colour
│   ├── Product Card: Photo + one-line spec + price
│   └── → /systems/[product-handle]
│       ├── HD gallery (video primary, stills secondary)
│       ├── Spec table (lace type / base size / density / hair origin)
│       ├── "How to order" 3-step accordion
│       ├── Partner Barber availability in your city
│       └── Add to Cart / Book Consultation
│
├── /maintenance ——————————— COLLECTION: MAINTENANCE CLUB
│   ├── The Maintenance Box (monthly subscription)
│   │   ├── What's inside (adhesives, solvent, scalp care)
│   │   └── Subscribe & Save CTA (Shopify Subscriptions / Recharge)
│   └── À-la-carte adhesives & solvents (one-time purchase)
│
├── /partners —————————————— PARTNER BARBER NETWORK
│   ├── City filter: Sandton / Cape Town / Durban
│   ├── Barber card: Name + photo + services + Book link
│   └── "Become a Partner" CTA → /partners/apply
│
├── /consult ——————————————— VIRTUAL CONSULTATION (Lead Gen)
│   ├── What to expect (3 bullet points max)
│   ├── Calendly embed (or equivalent)
│   └── "Private & confidential" reassurance copy
│
├── /about ————————————————— ABOUT (Trust Builder — minimal)
│   ├── The "Why We Built This" story (300 words max)
│   ├── The standard we work to (craft copy)
│   └── No team photos unless genuinely premium
│
├── /faq ——————————————————— FAQ (Objection Killer)
│   ├── Will it look real?
│   ├── What about swimming / gym / intimacy?
│   ├── How long does it last?
│   ├── What do I tell people?
│   ├── How does delivery work?
│   └── Is this reversible?
│
└── /account ——————————————— CUSTOMER ACCOUNT (post-purchase)
    ├── Order history
    ├── Subscription management
    └── Reorder / match update
```

---

## What Is Deliberately Excluded from MVP

| Excluded | Reason |
|---|---|
| Blog / Content Hub | Sprint 3+ — adds SEO value but dilutes launch focus |
| Before/After gallery page | Integrated into product pages; standalone page = Phase 2 |
| Community / Forum | Phase 3 feature — requires critical mass |
| Size/measurement guide (standalone) | Folded into /match quiz logic |
| Affiliate / Referral programme | Phase 2 |

---

## Navigation Structure (Desktop + Mobile)

**Primary Nav (6 items max):**
`Find My Match` · `Hair Systems` · `Maintenance Club` · `Partner Barbers` · `Consult` · `Account`

**Footer Nav:**
`About` · `FAQ` · `Privacy Policy` · `Shipping & Returns` · `Contact`

---

## Conversion Flow (Primary Path)

```
Homepage Hero
    ↓
"Find My Match" CTA (above the fold)
    ↓
/match Quiz (5 steps)
    ↓
Restoration Profile Result
    ↓
Recommended Product Page
    ↓
Add to Cart OR Book Consultation
    ↓
Checkout (PayStack / Peach Payments)
```

**Secondary Path (for the researcher):**
```
Homepage → Proof Videos → /systems (browse) → Product Page → Consult
```

---

## Page Priority for Design Sprint 1

| Priority | Page | Rationale |
|---|---|---|
| P0 | Homepage | The entire brand lives or dies here |
| P0 | /match quiz | Primary conversion mechanism |
| P1 | Product page template | Revenue-generating page |
| P1 | /consult | High-ticket lead capture |
| P2 | /systems collection | Discovery page |
| P3 | /maintenance | Recurring revenue unlock |
| P3 | /partners | Trust & ecosystem signal |
| P4 | /about, /faq | Supporting pages |
