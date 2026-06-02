# Elinam Amudzi — Personal Portfolio

A clean, production-ready personal portfolio website built with vanilla HTML, CSS, and JavaScript. No frameworks. No build tools. Just open `index.html`.

## 🗂 Project Structure

```
elinam-portfolio/
├── index.html              # Main HTML (single page)
├── css/
│   └── style.css           # All styles (CSS variables, responsive)
├── js/
│   └── main.js             # Scroll reveal, nav, mobile menu
├── assets/
│   └── Elinam_Amudzi_CV.docx   # Downloadable CV
└── README.md
```

## 🚀 Getting Started

### Option 1 — Open directly
Just open `index.html` in any modern browser. No server needed.

### Option 2 — Serve locally
```bash
# Python
python -m http.server 8080

# Node.js (npx)
npx serve .
```
Then visit `http://localhost:8080`

## 🌐 Deploying

### GitHub Pages
1. Push this repo to GitHub
2. Go to **Settings → Pages**
3. Set source to `main` branch, `/ (root)` folder
4. Your site will be live at `https://<username>.github.io/<repo-name>`

### Netlify (drag & drop)
1. Go to [netlify.com/drop](https://app.netlify.com/drop)
2. Drag the entire project folder onto the page
3. Done — live URL in seconds

### Vercel
```bash
npx vercel
```

## ✏️ Customising

| What to change | Where |
|---|---|
| Name, title, summary | `index.html` → `.hero` section |
| Work experience | `index.html` → `.timeline` section |
| Skills | `index.html` → `.skills` section |
| Certifications | `index.html` → `.certs` section |
| Contact info | `index.html` → `.contact` section |
| Colours & fonts | `css/style.css` → `:root` variables |
| CV file | Replace `assets/Elinam_Amudzi_CV.docx` |

### Colour palette (CSS variables)
```css
--cream:   #F5F0E8   /* background */
--ink:     #1A1A14   /* text */
--terra:   #C4561A   /* accent (terracotta) */
--forest:  #1D3D2F   /* hero / experience bg */
--gold:    #D4A843   /* highlight */
--muted:   #7A7568   /* secondary text */
```

## 📋 CV / Resume

The `assets/Elinam_Amudzi_CV.docx` file is linked from both the hero download button and the contact section. Replace with an updated version whenever needed — keep the same filename or update the `href` attributes in `index.html`.

## 🛠 Tech Stack

- **HTML5** — semantic, accessible markup
- **CSS3** — custom properties, Grid, Flexbox, CSS animations
- **Vanilla JS** — IntersectionObserver for scroll reveals, no dependencies
- **Google Fonts** — Bebas Neue, DM Serif Display, DM Sans

## 📄 License

Personal use. All content © Elinam Amudzi.
