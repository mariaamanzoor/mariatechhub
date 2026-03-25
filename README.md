# 🚀 Maria Tech Hub

> A modern, full-featured tech services website — built for GitHub Pages deployment.

![Maria Tech Hub](https://img.shields.io/badge/Maria%20Tech%20Hub-Live-4f8ef7?style=for-the-badge)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

## ✨ Features

- 🎨 **Modern Dark UI** — sleek gradient design with animated blobs
- 🖱️ **Custom Cursor** — smooth tracking cursor with follower effect
- 📱 **Fully Responsive** — mobile, tablet & desktop ready
- ⚡ **Scroll Animations** — reveal-on-scroll for all sections
- 📊 **Counter Animations** — animated stats section
- 🎭 **Portfolio Filter** — filter projects by category
- ✉️ **Contact Form** — with validation and success feedback
- 🔠 **Typing Effect** — animated hero subtitle
- 🌐 **Marquee Ticker** — scrolling services banner
- ♿ **Accessible** — semantic HTML, ARIA labels, keyboard nav

## 📁 File Structure

```
maria-tech-hub/
├── index.html          # Main HTML file
├── css/
│   ├── style.css       # Main stylesheet
│   └── animations.css  # Animation effects
├── js/
│   └── main.js         # All JavaScript
├── images/             # Add your images here
├── assets/             # Fonts, icons, etc.
└── README.md
```

## 🚀 Deploy to GitHub Pages

1. **Fork / clone** this repository
2. Go to **Settings → Pages**
3. Under *Source*, select **main branch → / (root)**
4. Click **Save** — your site will be live at `https://yourusername.github.io/maria-tech-hub/`

## 🛠️ Customize

### Update Contact Info
In `index.html`, find the contact section and update:
```html
<span>hello@mariatechhub.com</span>
<span>+1 (000) 000-0000</span>
<span>linkedin.com/in/mariatechhub</span>
```

### Add Your Photo
Replace the placeholder in the About section:
```html
<div class="about-img-placeholder">
  <img src="images/maria.jpg" alt="Maria" />
</div>
```

### Update Social Links
Find `.social-links` in the contact section and update `href` values.

### Change Colors
Edit CSS variables in `css/style.css`:
```css
:root {
  --accent:  #4f8ef7;   /* Primary blue */
  --accent2: #7c5cfc;   /* Purple */
  --accent3: #00e5b0;   /* Teal */
}
```

### Connect a Real Form
Replace the form handler in `js/main.js` with [Formspree](https://formspree.io):
```js
const response = await fetch('https://formspree.io/f/YOUR_ID', {
  method: 'POST',
  body: new FormData(contactForm),
  headers: { 'Accept': 'application/json' }
});
```

## 📦 Dependencies (CDN — no install needed)

| Library | Purpose |
|---------|---------|
| Google Fonts (Syne + Inter) | Typography |
| Font Awesome 6.5 | Icons |

## 🧑‍💻 Codespace Quick Start

```bash
# Open in browser
npx serve .

# Or simply open index.html in Live Server (VS Code extension)
```

## 📄 License

MIT — free to use and customise.

---

Made with ❤️ by **Maria Tech Hub**
