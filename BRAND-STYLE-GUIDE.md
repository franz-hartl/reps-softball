# R.E.P.S. Brand Style Guide

## Brand Overview

**Full Name:** R.E.P.S. — Ripple Effect of Preparation & Sacrifice

**Positioning:** This isn't a baseball facility that also does softball. It's a softball facility.

**Tagline:** Indoor Softball Training · Milford, CT

---

## Core Values

**Preparation.** There are no shortcuts. Getting better takes reps—real ones.

**Sacrifice.** Time, effort, early mornings, late nights. Development requires commitment.

**The Ripple Effect.** Growth spreads. One player raises the next. Younger players watch older players.

**Development Over Everything.** We care about making players better. The wins follow.

**All Are Welcome Who Want to Get Better.** You don't need to be elite. You need to want it.

---

## Brand Personality

If R.E.P.S. were a person:
- A coach who **believes in her** before she believes in herself
- Someone who **loves the game** and wants to share it
- **Warm but not soft**—cares enough to push her
- **Patient with the process**—knows development takes time
- The person who **shows up early** and stays late

**We are NOT:** Exclusive. Elite-only. Transactional. A baseball facility that also does softball.

---

## Voice & Tone

### Voice (Always)

- **Warm, not soft** — We care deeply, but caring means pushing
- **Confident, not boastful** — We know what we're doing, but don't brag
- **Community, not transactional** — She's joining something, not just renting a lane
- **Direct, not blunt** — Respect their time, stay human
- **Coach speak, not marketing speak** — Say it like a coach would

### Tone by Context

| Context | Tone | Example |
|---------|------|---------|
| Hero | Clear, direct | "She wants to get better. This is where that happens." |
| About | Confident, warm | "Nine state championships. Hall of Fame coaches. A place for the next generation." |
| Booking | Efficient, friendly | "Book online anytime. Swipe in. Get to work." |
| Social | Real, celebratory | "Saturday morning. Six lanes full. This is what it's about." |

### Writing Rules

**Do:**
- Use short sentences
- Say "your daughter" or "her"—not "your player" or "your athlete"
- Be specific ("6 lanes" not "multiple training areas")
- Say "get to work" not "train"

**Don't:**
- Use corporate speak or jargon
- Lean on exclamation points
- Make promises ("feel like she belongs")—just describe what's real
- Say "state-of-the-art" or "maximize potential" or "take your game to the next level"

---

## Visual Identity

### Logo / Wordmark

The R.E.P.S. wordmark uses **Crete Round** typeface with periods between letters.

```
R.E.P.S.
```

**Header version:** White letters, pink dots (animated)
**Hero version:** White letters, pink dots (animated)

- Always use full wordmark with periods
- Never stretch, rotate, or alter proportions

### Typography

**Primary (Headlines):**
- **Crete Round** — Wordmark, headlines
- Letter-spacing: 0.08em

**Secondary (Body):**
- **Nunito** — Body copy, navigation, buttons
- Weights: 400, 500, 600, 700
- Line height: 1.6 for body text

### Color Palette

```css
:root {
  /* Primary */
  --navy: #1a2744;
  --navy-dark: #0f1829;
  --navy-light: #2a3d5c;

  /* Accents */
  --neon: #39ff14;        /* Primary accent, Book button */
  --pink: #ff0080;        /* Secondary accent, Register button, dots */

  /* Neutrals */
  --white: #ffffff;
  --gray: #8892a0;
}
```

**Usage Rules:**
- Navy dominates backgrounds
- Green = system actions (Book button)
- Pink = human actions (Register button, call to action)
- Pink dots animate through green flash

### Button Styles

**Register (Pink):** Primary action for new users → calls phone
```css
background: var(--pink);
color: var(--white);
```

**Book (Green):** Action for existing users → booking system
```css
background: var(--neon);
color: var(--navy-dark);
```

Both buttons: Sharp corners, uppercase, 700 weight.

---

## The R.E.P.S. Test

Before publishing, ask:

1. **Is it about her, not us?**
2. **Does it sound like a coach, not a marketer?**
3. **Is it welcoming to anyone who wants to get better?**
4. **Would a busy parent get it in 3 seconds?**
5. **Does it feel like community, not transaction?**
