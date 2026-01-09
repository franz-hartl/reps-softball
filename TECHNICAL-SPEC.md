# R.E.P.S. Technical Spec

## Current Implementation

**Single HTML file with embedded CSS.** No build step. No dependencies.

```
reps-starter-kit/reference/current-site.html
```

Host anywhere. Open in browser. Done.

---

## Stack

- HTML5
- Embedded CSS (no external stylesheets)
- Google Fonts (Crete Round, Nunito)
- No JavaScript required (CSS animations only)

---

## CSS Variables

```css
:root {
  /* Colors */
  --navy: #1a2744;
  --navy-dark: #0f1829;
  --navy-light: #2a3d5c;
  --neon: #39ff14;
  --neon-dim: #2ecc0f;
  --neon-glow: rgba(57, 255, 20, 0.3);
  --pink: #ff0080;
  --white: #ffffff;
  --gray: #a0a8b4;
}
```

---

## External Services

| Service | URL | Purpose |
|---------|-----|---------|
| Swift | book.runswiftapp.com/facilities/reps | Booking system |
| Google Maps | maps.google.com/?q=674+Naugatuck+Ave+Milford+CT | Location link |
| Google Fonts | fonts.googleapis.com | Typography |

---

## Deployment

Host the HTML file anywhere:
- Vercel
- Netlify
- GitHub Pages
- Any static host

No server required. No build step.

---

## Future: React SPA

If expanding to a full React application, see archived specs in `reps-starter-kit/`:
- `TECHNICAL-SPEC.md` — Full React/Vite spec
- `COMPONENT-ARCHITECTURE.md` — Component structure
- `ROUTES.md` — Multi-page routing
