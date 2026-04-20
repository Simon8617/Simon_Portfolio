# Ogbodo Simon Onyedikachi — Portfolio Website
### SUNAGE-TECH CONCEPT | ICT Professional | CAC Registered

---

## 🗂 Files

```
simon-portfolio/
├── index.html          ← Complete single-file portfolio (HTML + CSS + JS all-in-one)
├── images/
│   ├── passport.jpg    ← ⬅ ADD YOUR PASSPORT PHOTO HERE
│   ├── cover.jpg       ← ⬅ ADD YOUR HERO/COVER PHOTO HERE
│   └── sunagetech-logo.png ← ⬅ ADD YOUR BUSINESS LOGO HERE
└── README.md
```

> **All CSS and JavaScript are embedded inside `index.html`** — no separate files needed.

---

## 🖼 Adding Your Photos

Put these images in the `images/` folder:

| File | What it is | Recommended Size |
|---|---|---|
| `passport.jpg` | Your profile photo | 300×380px portrait |
| `cover.jpg` | Hero background | 1600×900px landscape |
| `sunagetech-logo.png` | Business logo (PNG, transparent bg) | 400×400px |

---

## 🌐 GitHub Pages Deployment

1. Create a new GitHub repository
2. Upload `index.html` and the `images/` folder
3. Go to **Settings → Pages → Source: Deploy from branch → main → / (root)**
4. Click **Save** — your site is live at `https://yourusername.github.io/repo-name/`

---

## ✏️ Updating Content

Everything is in `index.html`. Use Ctrl+F to find these markers:

| What | Search for |
|---|---|
| Hero text / name | `id="hero"` |
| Personal info table | `id="about"` |
| Education entries | `id="education"` |
| Work experience | `id="experience"` |
| Certifications | `id="certifications"` |
| Skill percentages | `data-w="88"` (change the number) |
| Business info | `id="business"` |
| ID Card details | `id="idcard"` |
| Contact info | `id="contact"` |

---

## 🎨 Changing the Theme Color

In `index.html`, find `:root` near the top of the `<style>` tag:

```css
:root {
  --gold: #c8902a;   /* Change this to any color */
}
```

---

## 📞 Contact

- **Email:** simonogbodo7@gmail.com
- **Phone:** 08139426978
- **Business:** SUNAGE-TECH CONCEPT (CAC Registered)
- **Location:** Enugu State, Nigeria

*© 2025 Ogbodo Simon Onyedikachi & SUNAGE-TECH CONCEPT*
