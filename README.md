# Ankur & Kajol — Wedding Invitation Website

A luxury, interactive wedding invitation web application for **Ankur & Kajol**.

## Project Highlights & Modifications

- **Names Swapped**: 
  - Updated all occurrences from "Kajol & Ankur" to **"Ankur & Kajol"**.
  - Updated HTML `<title>`, Open Graph (`og:title`, `og:site_name`, `og:image:alt`), Twitter cards, and Meta descriptions.
  - In the Couple section, **Ankur Sharma (The Groom)** is featured first, followed by **Kajol Bhattacharya (The Bride)**.
  - In the Hero section, the host family names are arranged with the Groom's parents first.
  - In the Functions section, the **Groom's Rituals (UP)** tab is active by default.
  - In the RSVP section, the Groom's side is selected by default with WhatsApp message formatting updated to `*RSVP · Ankur & Kajol*`.
  - The downloadable calendar (.ics) event is updated to `Ankur-Kajol-Wedding.ics`.

- **Logo Monogram Swapped (K&A → A&K)**:
  - Both `assets/logo-gold.png` and `assets/p02.png` have been updated with the letter **A** on the left and **K** on the right in the golden infinity monogram loop, preserving the gold glitter texture, shading, and dimensions.
  - Re-rendered the high-definition Open Graph social share image (`assets/og-image.jpg`) featuring the new **A&K** monogram, chandelier glow, and "Ankur & Kajol" typography.

- **All Media Assets Downloaded**:
  - Full background music: `assets/song.mp3`
  - Hero background videos: `assets/hero-landscape.mp4`, `assets/hero-portrait.mp4`
  - High-resolution gallery & ritual photos: `assets/p01.webp` to `p20.webp`

## How to Run

You can run this project locally using any of the following:

### Option 1: Using Node / Vite (Recommended)
```bash
npm install -g vite
# or
npx vite --port 3000 --open
```

### Option 2: Using npx serve
```bash
npx serve .
```

### Option 3: Using Python
```bash
python -m http.server 3000
```
Then open `http://localhost:3000` in your browser.
