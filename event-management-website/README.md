# 🎈 AURA Events - Premium Event Management Website

A modern, visually stunning, and premium Event Management website designed with an immersive **Dark Glassmorphic UI/UX theme**. It is built purely using semantic **HTML5** and modern **CSS3** (incorporating Grid, Flexbox, Custom CSS Variables, backdrop-filters, and custom keyframe animations). 


## 🌟 Key Features

* **Premium Design System**: Tailored colors (Electric Violet, Vibrant Magenta, Neon Gold), clean typography, modern border styling, and micro-animations.
* **Glassmorphic Cards**: Features semi-transparent white-borders, deep backdrop blur effects, and linear gradient overlays that adjust dynamically on cursor interaction.
* **Smooth Micro-Interactions**: Hover rotation on icons, Ken Burns image scaling zoom, active line transitions in sticky menu, and floating background orb elements.
* **100% Fluid Responsiveness**: Designed using flexible CSS grids, fluid clamp/rem typography units, and custom media query breakpoints mapping down to 320px screen width.
* **Accessible Navigation**: Desktop nav features automatic scrollspy active tracking. On mobile, it slides out into a responsive blur-background side-drawer with active hamburger cross-animations.
* **Realistic Asset Stack**: Set up with high-resolution photography assets stored inside `assets/images/` representing weddings, summits, festivals, and leadership portraits.
* **Interactive Mock Logic**: In-page Vanilla JS toggles menus, controls transparent sticky nav transformations, handles scroll spies, and manages form and newsletter submit animation responses.

---

## 📂 Project Structure

```text
event-management-website/
│
├── index.html          # Main entry page (Semantic structure & JS controllers)
├── style.css           # Core styling, variables, keyframes, glassmorphism tokens
├── responsive.css      # Breakpoints adjustments from 1400px down to 320px
│
├── assets/
│   ├── images/         # Real high-resolution stock event photos
│   │   ├── hero-event.jpg
│   │   ├── about-event.jpg
│   │   ├── corporate-event.jpg
│   │   ├── wedding-event.jpg
│   │   ├── concert-event.jpg
│   │   ├── speaker-1.jpg
│   │   ├── speaker-2.jpg
│   │   ├── speaker-3.jpg
│   │   ├── gallery-1.jpg
│   │   ├── gallery-2.jpg
│   │   ├── gallery-3.jpg
│   │   └── testimonial-avatar.jpg
│   │
│   └── icons/          # Reserved for custom SVGs/assets
│
└── README.md           # Project documentation and guide
```

---

## 🛠️ Technology Stack

1. **HTML5**: Semantic tags (`<header>`, `<main>`, `<section>`, `<footer>`, `<nav>`) ensuring accessibility and neat SEO architecture.
2. **CSS3**: Custom property variables, Grid templates, Flex flows, backdrop filter styling, and keyframe animations.
3. **Vanilla JS**: Lightweight controllers for responsive interactive elements (zero third-party JS dependencies for layout).
4. **Google Fonts**: Importing `Space Grotesk` (headings) and `Plus Jakarta Sans` (body).
5. **FontAwesome v6**: Crisp vectors for services, benefits, contact icons, and rating indicators loaded via CDN.

---

## 🚀 How to Run Locally

1. Open the project folder on your system.
2. Double-click `index.html` to open it in any modern browser (Chrome, Safari, Edge, Firefox).
3. Alternatively, run a local development server (e.g., Live Server extension in VS Code, or python server):
   ```bash
   # Python 3
   python -m http.server 8000
   ```
   Then open `http://localhost:8000` in your browser.
