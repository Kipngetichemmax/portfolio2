# Portfolio Website

Clean, conversion-focused portfolio for early-career technical builders.

## Structure

```
portfolio/
├── index.html      # Main HTML structure
├── styles.css      # All styling (variables, layout, components, responsive)
├── script.js       # Interactivity (scroll animations, navigation highlighting)
└── README.md       # This file
```

## Features

- **Brutalist + Terminal Aesthetic** — Raw, honest design that signals technical competence
- **Conversion Optimized** — Clear CTAs, fast loading, mobile-first
- **Zero Dependencies** — Pure HTML/CSS/JS, no frameworks
- **Performance First** — Minimal payload, optimized animations
- **Fully Responsive** — Works on all devices

## Customization Guide

### 1. Personal Information

**In `index.html`:**
- Line 9: Update page title
- Line 10: Update meta description
- Line 24: Change `your_name` to your actual name/handle
- Line 37: Update headline
- Line 40: Update subtitle
- Lines 154-174: Replace with your actual projects
- Lines 227-253: Update about text
- Lines 271-283: Update contact links

### 2. Color Scheme

**In `styles.css` (lines 5-15):**
```css
:root {
    --bg: #0a0a0a;           /* Background */
    --fg: #e8e8e8;           /* Text color */
    --accent: #00ff41;       /* Primary accent (green terminal) */
    --border: #333;          /* Border color */
    /* ... adjust as needed */
}
```

### 3. Fonts

**In `index.html` (line 14):**
- Replace Google Fonts link with your preferred fonts
- Update CSS variables in `styles.css` (lines 13-14)

### 4. Add More Projects

Copy the project card template from `index.html` (lines 57-74) and update:
- `project-title`
- `project-type`
- `project-desc`
- `tech-tag` items
- `project-link` href

## Performance Checklist

- [x] Minimal CSS (< 10KB)
- [x] Minimal JS (< 4KB)
- [x] No external dependencies
- [x] Optimized animations (CSS-only where possible)
- [x] Mobile-first responsive design
- [x] Semantic HTML
- [x] Accessible (keyboard navigation, semantic structure)

## Browser Support

- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Deployment

### Quick Deploy Options:

1. **GitHub Pages**
   ```bash
   # Push to GitHub, enable Pages in repo settings
   ```

2. **Netlify**
   ```bash
   # Drag and drop the folder into Netlify
   ```

3. **Vercel**
   ```bash
   # Deploy with: vercel --prod
   ```

4. **Cloudflare Pages**
   ```bash
   # Connect GitHub repo or upload files
   ```

## File Sizes (approx)

- `index.html`: ~6KB
- `styles.css`: ~7KB
- `script.js`: ~2KB
- **Total**: ~15KB (uncompressed)

With gzip compression, total payload is ~5KB.

## Future Enhancements (Optional)

- [ ] Add dark/light theme toggle
- [ ] Blog section with markdown
- [ ] Project detail pages
- [ ] Contact form with backend
- [ ] Analytics integration
- [ ] SEO meta tags
- [ ] Open Graph images

## License

Free to use and modify. No attribution required.

---

Built with intention. No frameworks, just HTML + CSS + JS.
