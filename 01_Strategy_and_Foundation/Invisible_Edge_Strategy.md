# HIS HAIR — The Invisible Edge: Homepage Video Strategy

## The Strategic Problem It Solves

A man considering a hair system has one overriding fear: *"It will look fake."* No amount of written copy eliminates this. The only thing that eliminates it is **visual proof at scale, in motion, in realistic conditions.**

The Invisible Edge section exists for one purpose: **to destroy Objection #1 before the user scrolls to the shop.**

---

## Section Placement on Homepage

```
[HERO — Full bleed, headline + CTA]
            ↓
[INVISIBLE EDGE SECTION — Full width, dark background]
            ↓
[HOW IT WORKS — 3 steps]
            ↓
[QUIZ CTA — sticky bar]
```

The section sits **above the fold on scroll** — visible within the first 2 scrolls on mobile. It is the second thing a user sees after the hero.

---

## The Three Videos

Each video is looped, muted, auto-playing, and presented in a 16:9 or 9:16 (mobile) ratio. No play button visible by default — it plays immediately. Sound can be enabled on tap/click.

---

### Video 1: THE SCIENCE — "The Invisible Edge"
**Duration:** 15–20 seconds, looped
**Purpose:** Prove the lace is undetectable at skin level

**Shot list:**
- Macro lens, 4K minimum. Camera starts at 30cm from the hairline and slowly pushes in to 5cm.
- The scalp line is the hero. We see natural skin texture through the HD lace.
- Light source: soft overhead + subtle rim light (mimics office / indoor lighting).
- Hair is styled naturally — not "perfect," not too neat.
- Final frame: extreme close-up where lace is invisible against scalp.

**On-screen text (minimal, sans-serif, white):**
> *"HD lace. Bonded to your scalp. Invisible at 30cm."*

**No voiceover. No music. Let the visual do the work.**

---

### Video 2: THE LIFESTYLE — "A Full Life"
**Duration:** 30–45 seconds, looped
**Purpose:** Prove it holds across high-stakes real-world conditions

**Three scenes, cross-cut:**

**Scene A — The Gym**
- Man (35–45, well-built, naturally handsome — not male-model perfect) doing compound lifts.
- Sweat visible on brow and neck. Hair stays in place.
- Close-up shot of hairline post-workout: still natural.
- Lighting: warm gym fluorescent. Real environment.

**Scene B — The Boardroom**
- Same man (or similar profile) presenting at a glass-wall boardroom. Sandton/CBD aesthetic.
- Overhead corporate lighting — the harshest possible condition.
- Hairline visible from multiple angles: front, side profile, slight overhead.
- He's commanding the room. The hair is an afterthought — because it looks like his.

**Scene C — The Social**
- Evening rooftop or restaurant. Ambient low light.
- Laughing, animated — head movement is natural.
- A hand reaches to run fingers through his hair (this is the money shot — proves it moves naturally).

**On-screen text (cross-faded between scenes):**
> *"Gym."* / *"Boardroom."* / *"Yours."*

---

### Video 3: THE REVEAL — "Before & After in Motion"
**Duration:** 20–30 seconds
**Purpose:** Emotional proof — the transformation

**Shot structure:**
- Opens on a man in a barber chair, a slight tension in his face (the moment of commitment).
- Cut to: Partner barber applying the unit with precision — close-up on craft, not process.
- Cut to: Man looks up at mirror. First reaction — genuine, not performed.
- Final shot: He walks out of the barbershop. Shoulders back. Pace changed.

**No before/after split screen.** That's clinical. Instead: **narrative arc in under 30 seconds.**

**On-screen text (end card only):**
> *"The Edge You Thought You'd Lost."*

---

## Technical Implementation

### Desktop Layout
- Three videos displayed side-by-side in a CSS Grid (1:1:1 ratio).
- Section background: Oxford Blue (`#002147`) — creates contrast that makes the video pop.
- Thin white dividers between panels.
- Below each video: a single line of caption text in Champagne Cream.

### Mobile Layout
- Vertical swipeable carousel (one video per screen).
- Auto-advance every 8 seconds or on swipe.
- Videos compressed to <3MB each for mobile load speed (H.264 / WebM).

### Performance Requirements
- Lazy load: videos load only when section enters viewport.
- Poster image (single frame still) shown while video buffers.
- Total section load impact: <5MB above the fold.
- Host on Vimeo Pro (private) or Cloudflare Stream — **not YouTube** (no competitor ads, no UI chrome).

---

## Production Brief (For Video Shoot Day)

**Casting:**
- 2–3 men aged 32–50. South African. Professional appearance. Not model-polished — believable.
- At least one darker skin tone (melanin-diverse lace matching is a key differentiator).
- No one with obviously fake-looking hair in the talent pool.

**Locations:**
- Gym: A private gym (not Virgin Active branded). Clean, modern, dark palette.
- Boardroom: Rented glass-wall boardroom in Sandton or CBD. R1,500–R3,000/half-day.
- Social: Rooftop bar or upmarket Joburg/CT restaurant in evening light.
- Barber: Actual Partner Barber location — documents the ecosystem simultaneously.

**Equipment minimum:**
- Camera: Sony FX6 or RED Monstro (for macro capability and low-light performance).
- Lens: 50mm macro for Science video. 35mm prime for Lifestyle.
- Lighting: Natural augmented — avoid overly "produced" look.

**Total shoot estimate:** 1 day (Science + Barber) + 1 day (Lifestyle). Budget: R25,000–R55,000 all-in with a capable SA production company.

---

## The Conversion Logic

| User arrives skeptical | → | Sees Science video | → | Objection 1 reduced |
|---|---|---|---|---|
| Objection 1 reduced | → | Sees Lifestyle video | → | Objections 2 & 3 neutralised |
| Objections neutralised | → | Sees Reveal video | → | Emotional connection made |
| Emotional connection | → | CTA: "Find My Match" | → | Quiz entry / conversion |

**The goal is not to make him want hair. He already wants hair. The goal is to make him believe this is the version that won't embarrass him.** These three videos do exactly that.
