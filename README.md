
<!-- PROJECT LOGO -->
<br />
<div align="center">
  <img src="https://via.placeholder.com/120x30/0a0a0a/C8FF00?text=FIT+PRO" alt="FitPro Logo" width="120" />
  <h1 align="center">FitPro — Premium Fitness & Personal Training</h1>
  <p align="center">
    Dark luxury landing page for gym owners, personal trainers & fitness studios.
    <br />
    <a href="https://your-username.github.io/fitpro-landing"><strong>🔗 Live Demo »</strong></a>
    ·
    <a href="https://github.com/your-username/fitpro-landing/issues">🐞 Report Bug</a>
    ·
    <a href="#contact">📩 Contact</a>
  </p>
</div>

---

## ✨ About The Project

[![Product Screen Shot][product-screenshot]](https://your-username.github.io/fitpro-landing)

**FitPro** is a production‑ready React single‑page website designed to be sold to fitness professionals.  
It ditches generic gym clichés and embraces a **dark editorial aesthetic** — think Nike meets high‑end magazine.

The entire site is contained in **one HTML file**, ready to run with zero build tools and easily deployable to any static hosting.

### 🎨 Built for impact
- Massive `Bebas Neue` headlines with electric lime accents
- Smooth scroll‑triggered animations via IntersectionObserver
- Parallax hero effect on mouse move
- Animated stat counters that count up when visible
- Fully responsive from mobile to large desktop

---

## 🛠 Tech Stack

![React](https://img.shields.io/badge/React-18-20232a?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-3-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![Framer Motion](https://img.shields.io/badge/Framer_Motion-10-0055FF?style=for-the-badge&logo=framer&logoColor=white)
![React Router](https://img.shields.io/badge/React_Router-6-CA4245?style=for-the-badge&logo=react-router&logoColor=white)

- **React 18** (functional components + hooks)
- **Tailwind CSS** via CDN
- **Framer Motion** for animations
- **React Router v6** (wrapped, ready for multi‑page expansion)
- **Custom hooks** for intersection observer & counters
- **Pure CSS variables** – change the entire color scheme in one place

---

## 🚀 Quick Start

No `npm install`, no `create-react-app`. Just open the file.

1. Clone the repo
   ```bash
   git clone https://github.com/DizzyZ7/fitpro-landing.git
```

1. Open index.html in your browser
   ```bash
   cd fitpro-landing
   open index.html   # or double-click it
   ```

Or deploy instantly with GitHub Pages:

· Go to repository Settings > Pages
· Source: main branch, folder / (root)
· Save – your site is live in 60 seconds 🚀

---

🎛 Customization Guide

The project is built to be white‑labelled in minutes.

🎨 Colors

Edit the CSS variables at the top of the <style> block:

```css
:root {
  --bg: #0a0a0a;
  --surface: #141414;
  --accent: #C8FF00;          /* lime */
  --accent-secondary: #FF3B00; /* red */
  --text: #F2F2F2;
  --muted: #6B6B6B;
  --border: #2A2A2A;
}
```

🖼 Images

All placeholders use the class placeholder-img.
To add real photos, replace the corresponding <div> with an <img> tag and remove the placeholder class.

✍️ Content

Search for text strings like "TRAIN LIKE IT MATTERS" or "FitPro" to update headlines, programs, and contact info.

🌐 Add a CMS / Backend

· The contact form has a handleSubmit function ready for an API endpoint.
· Text content can be moved to a JSON/JS object and later fetched from Contentful, Sanity, or any headless CMS.

🌍 Internationalization (i18n)

All user‑facing strings are in‑line. You can extract them into a dictionary (e.g., en.json) and use react‑i18next without touching the structure.

---

📂 Project Structure

```
fitpro-landing/
├── index.html          # All components, styles, and logic
└── README.md
```

Because the entire app lives in one file, you can easily:

· Extract sections (HeroSection, PricingSection…) into separate .jsx files
· Integrate Vite or CRA for a full React project
· Keep the single‑file approach for ultra‑fast demos and sales presentations

---

🧠 Scalability Notes (from the code)

Every section is commented with hints for future maintainers:

· ✅ CSS variables — one‑place color swap
· ✅ Placeholder divs — drop‑in real images
· ✅ Component per section — extractable to separate files
· ✅ useState/useEffect ready for API calls — add CMS or backend
· ✅ Strings inline — ready for i18n library
· ✅ React Router wrapper — already supports /about, /programs etc.

---

📬 Contact

Developer / Agency
Dimash Janibekov – TG @dizzypupa – dizzyod.z7@gmail.com

Project Link: https://github.com/DizzyZ7/fitpro-landing

---

⭐ Acknowledgments

· Google Fonts – Bebas Neue & DM Sans
· Tailwind CSS – Utility‑first CSS framework
· Framer Motion – Animation library
· Design inspiration: dark luxury editorials, Nike, and the fitness industry’s best websites

---

<p align="center">
  <b>⚡ Built to impress. Ready to sell. ⚡</b>
</p>
```
