# 📱  NovaByte - Responsive Web Layout -  DecodeLabs Frontend Project 2

> *"Design is not just what it looks like. Design is how it works — on every screen, at every size."*
> — DecodeLabs Engineering Mandate

![Project Badge](https://img.shields.io/badge/DecodeLabs-Project%202-6c63ff?style=flat-square)
![Status](https://img.shields.io/badge/Status-Completed-43e97b?style=flat-square)
![HTML](https://img.shields.io/badge/HTML5-Semantic-e34f26?style=flat-square&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-Grid%20%26%20Flexbox-1572b6?style=flat-square&logo=css3&logoColor=white)
![Responsive](https://img.shields.io/badge/Responsive-Mobile--First-6c63ff?style=flat-square)

---

## 📌 Project Description

A fully responsive, accessible, and professionally designed **agency landing page** built from scratch using only **HTML5 and CSS3**, no frameworks, no JavaScript, no shortcuts.

This is **Project 2** of the DecodeLabs Frontend Development internship track (Batch 2026). The goal is to prove mastery of responsive design principles,  fluid layouts, CSS media queries, and mobile-first architecture, before moving into dynamic JavaScript logic.

**Live Demo →** [https://nikinii3.github.io/decodelabs-p2-novabyte-responsive-layout/]

---

## 🗂 Project Structure

```
novabyte-responsive-layout/
│
├── index.html              # Main HTML file — semantic structure & SVG icon library
├── styles.css              # External stylesheet — all styling lives here
├── README.md               # You are reading this
│
├── images/                 # Project screenshot previews
│   ├── soundWave.png
│   └── terrabotanica.png
│
├── projects/               # Individual project pages
│   ├── datapulse.html
│   ├── lunashop.html
│   ├── soundWave.html
│   └── terraBotanice.html
│
└── videos/                 # Project walkthrough demos
    ├── dataPulse.mp4
    └── lunarShop.mp4 
```

---

## ✨ Features

- **Mobile-First Architecture**: base styles target 320px; complexity is added upward via `min-width` media queries, never subtracted
- **CSS Grid** for macro page layout: section structure, multi-column grids, footer columns
- **Flexbox** for micro component alignment: navbar, cards, buttons, author rows
- **Fluid Typography with `clamp()`**: font sizes scale smoothly across all screen widths without a single media query
- **Native Popover API Navigation**: zero-JavaScript hamburger menu with slide-in animation and `::backdrop` dimming
- **Custom Inline SVG Icon System**: every icon is a hand-drawn `<symbol>`, reused with `<use>`, no icon font, no emoji, no external library
- **CSS Custom Properties**: every color, size, and spacing value is a design token; theming the entire site takes one edit
- **WCAG Accessibility**: semantic landmarks, `aria-label` on all icon-only controls, `alt` text, 44×44px minimum touch targets, zoom unrestricted
- **Animated hero section**: gradient orbs, fade-up entrances, pulse dot, all pure CSS
- **Seamless marquee strip**: infinite scrolling ticker using CSS `@keyframes` only

---

## 📄 Sections

| Section | Description |
|---|---|
| **Navbar** | Sticky top bar - collapses to hamburger on mobile, full links on desktop |
| **Hero** | Full-viewport intro with animated gradient orbs, headline, stats, and CTA buttons |
| **Marquee** | Infinite scrolling strip of tech keywords — pure CSS animation |
| **Services** | 6 service cards in a 1 → 2 → 3 column responsive grid |
| **About** | Split layout with live-syntax code window visual on desktop |
| **Work** | Portfolio grid - featured card spans 2 columns on desktop |
| **Testimonials** | 3 client review cards in a 1 → 2 → 3 column responsive grid |
| **CTA** | Centered call-to-action with radial glow background |
| **Footer** | 4-column responsive footer grid with social links |

---

## 📐 Responsive Breakpoints

| Name | Width | Layout Changes |
|---|---|---|
| **Mobile** (base) | `0px +` | 1-column grid, hamburger nav visible |
| **Tablet** | `768px +` | 2-column grid, full nav links visible |
| **Desktop** | `1024px +` | 3-column grid, featured card spans 2 cols |
| **Wide** | `1280px +` | Fluid side padding with `clamp()` |

---

## 🚀 How to Run

This is a **pure static project** - no installation, no build tools, no terminal commands needed.

**Option 1 - Open directly in browser**
```
1. Download or clone this repository
2. Open the project folder
3. Double-click index.html
4. It opens in your default browser instantly
```

**Option 2 - Clone via Git**
```bash
git clone https://github.com/YOUR_USERNAME/novabyte-responsive-layout.git
cd novabyte-responsive-layout
open index.html        # macOS
start index.html       # Windows
xdg-open index.html    # Linux
```

**Option 3 - Live Server (recommended for development)**
```
1. Open the folder in VS Code
2. Install the "Live Server" extension by Ritwick Dey
3. Right-click index.html → "Open with Live Server"
4. Browser opens at http://127.0.0.1:5500 and auto-refreshes on every save
```

---

## ☁️ Deployment (GitHub Pages)

```bash
# 1. Push your code to GitHub
git add .
git commit -m "feat: responsive web layout — Project 2"
git push origin main

# 2. Go to your repo on GitHub
# Settings → Pages → Source: Deploy from branch → main → / (root) → Save

# 3. Your site goes live at:
# https://YOUR_USERNAME.github.io/novabyte-responsive-layout
```

---

## ✅ Quality Checklist

| Standard | Status |
|---|---|
| Viewport meta tag | ✅ `width=device-width, initial-scale=1` |
| Mobile-first base CSS | ✅ All base styles target 320px |
| CSS Grid — macro layout | ✅ All section grids use Grid |
| Flexbox — micro layout | ✅ All components use Flexbox |
| Fluid units (`%`, `rem`, `vw`) | ✅ Zero hard-coded px layout values |
| `clamp()` fluid typography | ✅ All font sizes use clamp() |
| Hamburger navigation | ✅ Native Popover API, zero JS |
| Accessible touch targets | ✅ Min 44×44px on all controls |
| Zoom not restricted | ✅ `user-scalable` not set to `no` |
| Semantic HTML5 landmarks | ✅ header, nav, main, footer, article |
| Custom SVG icon system | ✅ No emoji, no icon font |
| `aria-label` on icon buttons | ✅ Confirmed |
| `:focus-visible` outlines | ✅ Confirmed |
| `prefers-reduced-motion` | ✅ All animations respect this |
| External CSS only | ✅ Zero inline styles |

---

## 🛠 Built With

- **HTML5** - semantic structure, SVG symbol library, Popover API
- **CSS3** - custom properties, Grid, Flexbox, `clamp()`, animations, media queries
- **Google Fonts** - Syne (display) + DM Sans (body)
- **Git & GitHub**- version control with structured commit history

---

## 📁 Commit History Approach

This project follows a **professional commit discipline** — every section was committed separately in structure-before-style order.

```
feat(css):  add footer styles and social links
feat(html): add footer structure
feat(css):  add CTA section styles
feat(html): add CTA section structure
feat(css):  add testimonials section styles
feat(html): add testimonials section structure
feat(css):  add work/portfolio grid styles
feat(html): add work section with project cards
feat(css):  add about section split layout styles
feat(html): add about section with code window visual
feat(css):  add services grid styles
feat(html): add services section structure
feat(css):  add marquee strip styles and animation
feat(html): add marquee strip
feat(css):  add hero section styles with gradient orbs
feat(html): add hero section structure
feat(css):  add navbar and mobile popover menu styles
feat(html): add navbar and SVG icon symbol library
feat:       add CSS tokens, reset, base and animations
Initial commit
```

---

## Screenshots 
<img width="2856" height="1561" alt="homepage" src="https://github.com/user-attachments/assets/88f5ef9f-9336-4caa-8ff5-cef0d0689308" />

<img width="2854" height="1559" alt="services" src="https://github.com/user-attachments/assets/1cd945c4-0802-4660-9a53-e3da69970a5a" />

<img width="2852" height="1562" alt="approach" src="https://github.com/user-attachments/assets/02562cba-e160-4742-91d7-077db0aae085" />

<img width="2852" height="1561" alt="displayProjects" src="https://github.com/user-attachments/assets/4f06318e-026e-4973-9d3d-63c87a753d2c" />

<img width="2847" height="1564" alt="project1" src="https://github.com/user-attachments/assets/95eb21ac-f975-400c-8aa5-4fc2661a29df" />

<img width="2849" height="1557" alt="project2" src="https://github.com/user-attachments/assets/2a53261d-73e0-455f-bebc-bd77430248c1" />

<img width="2852" height="1564" alt="project3" src="https://github.com/user-attachments/assets/b8c71cd3-7f12-4389-b74c-bd75318c73a4" />

<img width="2856" height="1562" alt="project4" src="https://github.com/user-attachments/assets/bdfd9d92-c16d-4bf7-a43b-2a97a0d81680" />

<img width="2878" height="1566" alt="Testimonials" src="https://github.com/user-attachments/assets/895f46a2-ce69-4ba9-8111-aa2f7e697a68" />

<img width="2854" height="1541" alt="letsbuild" src="https://github.com/user-attachments/assets/8b07859c-4cbb-4881-87b6-1d0f9af1afea" />

---

## 👩‍💻 Author

**Nikini Madugoda**
Frontend Developer Intern · DecodeLabs Batch 2026

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077b5?style=flat-square&logo=linkedin)](https://www.linkedin.com/in/nikini-madugoda)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-181717?style=flat-square&logo=github)](https://github.com/Nikinii3)

---

## 📜 License

This project was built as part of the **DecodeLabs Industrial Training Program**.
© 2026 [Your Name] · All rights reserved.
