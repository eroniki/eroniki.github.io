# Murat Ambarkutuk - Personal Portfolio

A clean, modern, and fully responsive personal portfolio website built with **Bootstrap 5**.

## 🎨 Features

- **Modern Design**: Clean, professional layout with gradient hero section
- **Fully Responsive**: Optimized for all devices (mobile, tablet, desktop)
- **Bootstrap 5**: No proprietary templates, using open-source Bootstrap framework
- **Smooth Animations**: Fade-in effects and hover animations
- **SEO Optimized**: Structured data, meta tags, and semantic HTML
- **Accessible**: ARIA labels, keyboard navigation support
- **Fast Loading**: Minimal dependencies, optimized assets
- **Easy to Customize**: Well-organized code with CSS variables

## 🛠️ Technologies

- **HTML5**: Semantic markup
- **CSS3**: Modern styling with flexbox and grid
- **Bootstrap 5.3.2**: Responsive framework
- **Bootstrap Icons 1.11.3**: Icon library
- **Vanilla JavaScript**: No jQuery dependencies

## 📁 Structure

```
eroniki.github.io/
├── index.html              # Main HTML file
├── assets/
│   ├── css/
│   │   └── style.css      # Custom styles
│   └── js/
│       └── script.js      # Custom JavaScript
├── images/                 # Images and favicons
├── publications/           # Publication files (.bib, .pdf)
├── resume/                 # Resume files
├── manifest.json          # PWA manifest
├── CNAME                  # Custom domain
└── README.md              # This file
```

## 🚀 Local Development

1. Clone the repository:
```bash
git clone https://github.com/eroniki/eroniki.github.io.git
cd eroniki.github.io
```

2. Start a local server:
```bash
python3 -m http.server 8080
```

3. Open your browser:
```
http://localhost:8080
```

## 🎨 Customization

### Colors
Edit the CSS variables in `assets/css/style.css`:
```css
:root {
    --primary-color: #0d6efd;
    --dark-bg: #1a1a1a;
    --light-bg: #f8f9fa;
}
```

### Hero Gradient
Change the gradient in `.hero-section`:
```css
.hero-section {
    background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
}
```

### Content
Edit `index.html` to update sections.

## 📱 Sections

1. **Hero** - Introduction with profile image and social links
2. **About** - Background and education cards
3. **Research** - Research interests in card layout
4. **Projects** - Project timeline with links
5. **Publications** - Academic publications with links
6. **Contact** - Contact information and resume download

## 🌐 Deployment

The site is automatically deployed via GitHub Pages from the `master` branch.

## 🔗 Links

- **Live Site**: [ambarkutuk.com](https://ambarkutuk.com)
- **GitHub**: [github.com/eroniki](https://github.com/eroniki)
- **LinkedIn**: [linkedin.com/in/muratambarkutuk](http://www.linkedin.com/in/muratambarkutuk)

## 📄 License

- **Bootstrap**: MIT License
- **Bootstrap Icons**: MIT License
- **Content**: © 2025 Murat Ambarkutuk. All rights reserved.

---

**Built with ❤️ using Bootstrap**
