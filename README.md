# O-Z.Ink - Professional Tattoo Portfolio

A stunning, fully responsive tattoo portfolio website featuring:

✨ **Features:**
- 🎨 Dark psychedelic color scheme with vibrant gradients
- 🖱️ Custom tattoo machine cursor (desktop only)
- 📱 Fully mobile-friendly and responsive design
- ✨ Smooth scroll-triggered fade-in animations
- 🎭 Glitch text effects and parallax scrolling
- 🌟 Interactive gallery with hover effects
- ⚡ Floating particle background animations
- 🎯 Modern, professional design that stands out

## Quick Start

Simply open `index.html` in your web browser to view the portfolio.

```bash
# Clone the repository
git clone https://github.com/NextLevel333/o-z.ink.git

# Navigate to the directory
cd o-z.ink

# Open in browser (or use a local server)
open index.html
```

## Using a Local Server (Recommended)

For the best experience, run a local server:

```bash
# Using Python 3
python -m http.server 8000

# Using Node.js
npx serve

# Then visit http://localhost:8000
```

## Customization

### Adding Your Own Images
Replace the placeholder gradients in `index.html` with your actual tattoo images:

```html
<div class="placeholder-image" style="background: url('your-image.jpg') center/cover;">
```

### Changing Colors
Edit the CSS variables in `styles.css`:

```css
:root {
    --primary-purple: #8b5cf6;
    --neon-pink: #ec4899;
    --neon-cyan: #06b6d4;
    /* ... customize your colors */
}
```

### Contact Information
Update the email in `index.html`:

```html
<a href="mailto:your-email@example.com" class="cta-button">Book a Consultation</a>
```

## Browser Support

- ✅ Chrome/Edge (recommended)
- ✅ Firefox
- ✅ Safari
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

## Technologies Used

- HTML5
- CSS3 (Grid, Flexbox, Animations)
- Vanilla JavaScript (ES6+)
- SVG (Custom cursor)

## License

MIT License - See LICENSE file for details

---

Made with 💜 for tattoo artists who want to stand out
