<div align="center">

# 🎓 Rosebank International — University Website

### A single-page site with a live student &amp; tutor attendance portal

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Google Fonts](https://img.shields.io/badge/Google_Fonts-4285F4?style=for-the-badge&logo=googlefonts&logoColor=white)](https://fonts.google.com/)

[Live sections](#-sections) · [Features](#-features) · [Tech stack](#-tech-stack) · [Getting started](#-getting-started)

</div>

---

## 📖 About

**Rosebank International** is a marketing and portal site for a university offering
accredited qualifications across Commerce, Technology, Health Sciences and Humanities.
It's built as a single, dependency-free `index.html` — no build step, no framework —
and includes a fully working **attendance register** that tutors can use to log which
students attended each day, what topic was covered, and how well the class understood it.

## 🗂 Sections

| Section | What it does |
|---|---|
| **Home / Hero** | Intro banner with quick facts (faculties, intake year, class format, compliance) |
| **About** | Overview of the university's four faculties |
| **Careers** | Open lecturer / tutor / support-staff roles per faculty |
| **Student &amp; Tutor Portal** | Weekly attendance register — add students, tick daily attendance, track class understanding % |
| **Contact** | Campus address, admissions/careers email, phone hours |

## ✨ Features

- 📝 **Live attendance register** — add/remove students, mark Mon–Fri attendance per row
- 📊 **Class understanding meter** — a 0–100% slider-style readout tutors update per session
- 💾 **Persistent storage** — register data is saved via `window.storage` and reloads automatically
- 🖨️ **Print / PDF export** — one click produces a clean, printable attendance sheet
- 📱 **Responsive layout** — collapsible nav and stacked grids below 860px
- ♿ **Accessible by default** — semantic HTML, labelled form fields, visible focus states

## 🛠 Tech stack

- **HTML5** — semantic structure, single file
- **CSS3** — custom properties, CSS Grid/Flexbox, print media queries
- **Vanilla JavaScript** — no frameworks, no build tools
- **Fonts** — [Fraunces](https://fonts.google.com/specimen/Fraunces) &amp; [Inter](https://fonts.google.com/specimen/Inter) via Google Fonts

## 🚀 Getting started

No installation needed — it's a static file.

```bash
# clone the repo
git clone https://github.com/<your-username>/rosebank-international.git
cd rosebank-international

# open it in a browser
start index.html      # Windows
```

Or just double-click `index.html`.

## 📁 Project structure

```
Rosebank International/
├── index.html      # entire site — markup, styles, and script
└── README.md
```

## 📬 Contact

- **Admissions:** admissions@rosebankinternational.ac.za
- **Careers:** careers@rosebankinternational.ac.za
- **Phone:** +27 51 000 0000 (Mon–Fri, 08:00–16:30 SAST)

---

<div align="center">

Built by **Velelo Technology** · © 2026

</div>
