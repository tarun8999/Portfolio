# 🧑‍💻 N. Tharun Kumar Reddy — Personal Portfolio

A clean, responsive, dark-themed personal portfolio website built with pure **HTML & CSS** — no frameworks, no dependencies, just one file.

🔗 **Live Demo:** [github.com/tarun8999](https://github.com/tarun8999)

---

## 📸 Preview

> A dark navy portfolio with cyan & indigo accents, animated terminal hero card, smooth scroll sections, and a live Jotform-powered contact form.

---

## 📁 Project Structure

```
portfolio/
├── index.html       # Full portfolio — HTML + CSS + JS in one file
└── README.md        # You're reading this
```

> Rename `portfolio.html` → `index.html` before pushing so GitHub Pages serves it correctly.

---

## ✨ Features

- **Responsive design** — works on mobile, tablet, and desktop
- **Animated terminal card** in the hero section with a blinking cursor
- **Smooth scroll navigation** with a fixed frosted-glass navbar
- **6 skill cards** — Frontend, Java/C, Git, Data Analytics, UI/UX, DSA
- **Projects section** — Portfolio Website, Hackathon Project, GitHub Contributions
- **Live contact form** powered by [Jotform](https://jotform.com) — submissions go straight to email
- **Success message** shown after form submission (no page redirect)
- **Glow orb effects** and hover micro-animations
- **Prefers-reduced-motion** support for accessibility
- **Zero external JS dependencies** — Google Fonts only

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| Structure | HTML5 |
| Styling | CSS3 (CSS Variables, Grid, Flexbox) |
| Fonts | Syne (display) · Inter (body) via Google Fonts |
| Form Backend | Jotform |
| Hosting | GitHub Pages |

---

## 🚀 How to Deploy on GitHub Pages

### Step 1 — Rename the file
```bash
mv portfolio.html index.html
```

### Step 2 — Push to GitHub
```bash
git init
git add .
git commit -m "Initial commit: portfolio website"
git branch -M main
git remote add origin https://github.com/tarun8999/portfolio.git
git push -u origin main
```

### Step 3 — Enable GitHub Pages
1. Go to your repository on GitHub
2. Click **Settings** → **Pages**
3. Under **Source**, select `main` branch → `/ (root)`
4. Click **Save**
5. Your site will be live at `https://tarun8999.github.io/portfolio/` in ~60 seconds

---

## 📬 Contact Form Setup

The contact form posts submissions to **Jotform** (Form ID: `261722695409060`).

To receive email notifications for every submission:
1. Log in to [jotform.com](https://jotform.com)
2. Open **Contact - N. Tharun Kumar Reddy** form
3. Go to **Settings → Emails → Add Notification**
4. Set recipient to `ntharunkumarr@gmail.com`
5. Save — every form fill will ping your inbox instantly

---

## 🎨 Colour Palette

| Name | Hex | Usage |
|---|---|---|
| Background | `#0B0F1A` | Page background |
| Surface | `#111827` | Cards, sections |
| Border | `#1E2A3A` | Card borders, dividers |
| Accent (Cyan) | `#38BDF8` | Primary highlights, buttons |
| Accent (Indigo) | `#818CF8` | Secondary highlights, gradient |
| Text | `#E2E8F0` | Body text |
| Muted | `#64748B` | Descriptions, labels |

---

## 📌 Sections

| Section | Description |
|---|---|
| **Hero** | Name, tagline, terminal card, CTA buttons |
| **About** | Bio, stats (3+ years, 10+ projects, 5+ tech), detail cards |
| **Skills** | 6 skill cards with tags |
| **Projects** | 3 project entries in a timeline layout |
| **Contact** | Links (email, LinkedIn, GitHub) + live Jotform form |

---

## 👤 Author

**N. Tharun Kumar Reddy**
B.Tech CSE Student | Developer
📍 Andhra Pradesh, India

- 📧 [ntharunkumarr@gmail.com](mailto:ntharunkumarr@gmail.com)
- 💼 [LinkedIn](https://www.linkedin.com/in/tharun-kumar-reddy-baa2a9335/)
- 🐙 [GitHub](https://github.com/tarun8999)

---

## 📄 License

This project is open source and available under the [MIT License](https://opensource.org/licenses/MIT).
Feel free to use it as a template — just update the name, details, and form ID with your own.
