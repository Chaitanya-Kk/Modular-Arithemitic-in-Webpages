# Modular Arithmetic in Computing  
**A Beautifully Designed 2-Page Educational Website**

---

## Overview

This project is a **two-page, visually stunning educational website** that explores how **Number Theory and Modular Arithmetic** power modern computing — from **web applications** to **computer systems, machine learning, and emerging technologies**.

Built with **pure HTML, CSS, and semantic design**, it features:
- Sleek dark-mode Apple-inspired UI
- Smooth animations and micro-interactions
- Fully responsive layout (mobile to desktop)
- No external dependencies (zero JavaScript, no frameworks)

---

## Pages

| File | Title | Purpose |
|------|-------|--------|
| `index.html` | **How Modular Arithmetic Runs the Web** | Shows 10 number theory concepts in **web applications** (HTTPS, pagination, URL shorteners, etc.) |
| `CS.html` | **How Number Theory & Modular Arithmetic Support Computer Systems, ML, and Emerging Technologies** | Explores the same 10 concepts in **CS fundamentals** and **ML/privacy tech** (federated learning, hashing, crypto-ML) |

Both pages are **visually identical in style**, linked via a **"Continue →"** button.

---

## Features

### Design & UX
- **Gradient hero** with animated title
- **Floating background orbs** for depth
- **Card-based layout** with hover lift + glow
- **Smooth scroll indicator**
- **Staggered fade-in animations**
- **Responsive grid** (1–3 columns)
- **Summary table** with hover states
- **Call-to-action bottom line**

### Content Structure (Each Page)
1. **Hero Section** – Engaging title + subtitle
2. **10 Interactive Cards** – One per number theory concept
3. **Summary Table** – Quick reference
4. **Bottom Line** – Key takeaway
5. **Redirect CTA** – Links to the next page

---

## File Structure

```
modular-arithmetic-website/
│
├── index.html          # Page 1: Web Applications
├── CS.html             # Page 2: CS, ML, Emerging Tech
├── README.md           # This file
└── (optional) assets/  # For images or future assets
```

---

## How to Use

1. **Download** both HTML files
2. Open `index.html` in any browser
3. Click **"Continue to CS.html →"** to navigate
4. Works **offline** — no server needed

> Tip: Host on GitHub Pages, Netlify, or Vercel for free public access.

---

## Customization

### Change Colors
Edit CSS variables in `<style>`:
```css
:root {
    --accent: #0071e3;     /* Main blue */
    --bg-primary: #000000;
    --text-primary: #f5f5f7;
}
```

### Add More Pages
1. Copy `CS.html`
2. Update `<title>`, hero text, and content
3. Link from previous page using:
   ```html
   <div class="redirect-section">
       Now exploring X → <a href="next-page.html">Continue →</a>
   </div>
   ```

---

## Target Audience

Perfect for:
- **Computer Science Students**
- **Discrete Math / Cryptography Courses**
- **ML Engineers** learning privacy-preserving tech
- **Tech Educators** needing visual teaching aids
- **Self-learners** exploring math in real systems

---

## Screenshots

| `index.html` | `CS.html` |
|--------------|-----------|
| ![Web Page](https://drive.google.com/file/d/1gqCm-ZArnwwXLQwOZK4jtrnqyP91ZSIP/view?usp=sharing) | ![CS/ML Page](https://i.imgur.com/example2.png) |

*(Add real screenshots later)*

---

## Tech Stack

| Layer | Technology |
|------|------------|
| Markup | HTML5 |
| Styling | CSS3 (Flexbox, Grid, Animations) |
| Fonts | System UI Stack (`-apple-system`, SF Pro) |
| Icons | SVG inline |
| JS | None (100% static) |

---

## License

**MIT License** – Free to use, modify, and distribute.

> Feel free to use in classrooms, blogs, or personal projects.

---

## Author

**Built with passion for math + design**  
*Your Name or Pseudonym Here*

---

> **"Math isn’t just theory — it’s the invisible engine of the digital world."**

---

**Deploy now. Teach better. Inspire more.**
