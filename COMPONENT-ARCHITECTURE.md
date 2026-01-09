# R.E.P.S. Component Architecture

## Future Reference

> **Note:** The current site is a single HTML file. This document is preserved for potential future React implementation.

---

## Current Structure (HTML)

```
current-site.html
├── <header>
│   ├── Logo (R.E.P.S. with animated dots)
│   └── CTA buttons (Register, Book)
│
├── <main>
│   ├── <section class="hero">
│   │   ├── Hero content (tagline, wordmark, headline, sub-copy)
│   │   └── Pricing card
│   │
│   └── <section class="about-section">
│       ├── Headline + copy
│       ├── Info grid (3 cards)
│       ├── Contact block
│       └── Membership note
│
└── <footer>
    ├── Logo
    ├── Social links
    └── Copyright
```

---

## For Future React Build

See `reps-starter-kit/COMPONENT-ARCHITECTURE.md` for full component specs including:

- Button variants (primary, ghost, register)
- Logo component with animation
- PricingCard with data structure
- TeamMember cards
- Section headers with accent text
- Wave dividers
