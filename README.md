# Patrizio Ricciardelli - Cybersecurity Portfolio

A modern, responsive, single-page cybersecurity portfolio built with HTML, CSS and JavaScript.

## 🚀 Features

- **Modern dark theme** with light mode toggle
- **Responsive design** for desktop, tablet and mobile
- **Smooth scroll navigation** with active section highlighting
- **Animated counters** and skill bars
- **Filterable projects** by category
- **Professional timeline** for work experience
- **MITRE ATT&CK detection cards**
- **Certifications showcase**
- **Interactive terminal hero**
- **Contact form** ready for Formspree integration
- **SEO optimised** with Open Graph meta tags

## 📁 Structure

```
portfolio/
├── index.html          # Main HTML file
├── css/
│   └── style.css       # All styles + responsive + themes
├── js/
│   └── main.js         # Interactivity, animations, filters
└── README.md           # This file
```

## 🛠️ Setup & Customisation

### 1. Replace placeholders

Before publishing, update these placeholders in `index.html`:

| Placeholder | Where to update | What to put |
|---|---|---|
| `Payrick` | TryHackMe badge and link | Your TryHackMe username |
| `your-linkedin` | LinkedIn links | Your LinkedIn profile URL |
| `YOUR_FORM_ID` | Contact form action | Your Formspree form ID |
| `assets/Patrizio_Ricciardelli_CV.pdf` | CV download links | Path to your actual CV |
| `https://pricciardelli.github.io` | Open Graph meta URL | Your actual site URL |

### 2. Add your CV

Place your CV PDF in an `assets/` folder inside `portfolio/`, or update the download links to point to your CV file.

### 3. Deploy

#### Option A: GitHub Pages
1. Create a new repository on GitHub.
2. Upload the contents of the `portfolio/` folder to the repository root.
3. Go to **Settings > Pages** and enable GitHub Pages from the `main` branch.
4. Your site will be live at `https://yourusername.github.io/repository-name`.

#### Option B: Netlify / Vercel
1. Drag and drop the `portfolio/` folder onto Netlify's deploy area.
2. Your site will be live instantly.

## 🎨 Customisation Tips

- **Colours**: Edit the CSS variables at the top of `css/style.css`.
- **Content**: Update text directly in `index.html`.
- **Projects**: Add/remove project cards in the Projects section.
- **Skills**: Adjust percentages in the `data-width` attributes.

## 📱 Preview Locally

You can open `index.html` directly in any modern browser. For the best experience during development, use a local server:

```bash
cd portfolio
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## ⚠️ Notes

- The contact form uses Formspree. Replace `YOUR_FORM_ID` or switch to a `mailto:` link.
- The TryHackMe badge will only display after you replace `Payrick` with your real username.
- The portfolio is designed to be hosted online; some external resources (Font Awesome, Google Fonts) require an internet connection.

---

Built for Patrizio Ricciardelli's cybersecurity career transition.
