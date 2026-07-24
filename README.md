# Courtside Travel

Landing page for **Courtside Travel** — *Sports travel, elevated.* A studio that
designs European football weekends around the match you choose: tickets, hotel,
restaurants, and an itinerary built so you experience the city, not just the stadium.

The site is a single, self-contained `index.html` (all CSS and JS inline) with a
folder of optimized image assets. No build step — open the file or serve the folder.

## Run it

Open `index.html` directly in a browser, or serve the folder:

```bash
python3 -m http.server 4321
# then visit http://localhost:4321
```

## Structure

```
index.html                 The whole site (inline CSS + JS)
assets/
  brand/                   CT monogram (alpha-keyed PNG, used as a CSS mask)
  collage/                 Hero collage photography (c1–c9, 900px + 480px srcset)
  leagues/                 Circular league portraits (Champions, Premier, LaLiga, Serie A)
Stadiums/                  Source stadium photography
Hero images/               Source hero photography
Brand Kit copy.png         Brand palette and type reference
CLAUDEwebdesign copy.md    Design standards for the build
```

## Design notes

- **Language:** Spanish (`es`).
- **Palette:** Ivory `#F5F2EA` · Charcoal `#111111` · Court Green `#234038` · Champagne Gold `#C8A96B`.
- **Type:** Cormorant Garamond (display) + Inter (body).
- **Signature:** a scroll-lit manifesto whose words light from ghost to Court Green as you read.
- Responsive down to 375px, keyboard-focus states throughout, and `prefers-reduced-motion` respected.

## Contact form

The intake form composes a `mailto:` to `hola@courtsidetravel.com` — no backend.
Swap that address (and the placeholder is `hola@`) when the real inbox is live.
