# LaslesVPN Landing Page 🌐

![Project Banner](./screenshots/banner.png)

> A fully responsive landing page built with pure HTML5 and SCSS, featuring CSS-only interactions and mobile-optimized layouts.

[![Live Demo](https://img.shields.io/badge/demo-live-success)](YOUR_DEMO_LINK)
[![HTML](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS](https://img.shields.io/badge/SCSS-CC6699?logo=sass&logoColor=white)](https://sass-lang.com/)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

---

## 📸 Screenshots

### Desktop
![Desktop View](./screenshots/desktop.png)

### Tablet
![Tablet View](./screenshots/tablet.png)

### Mobile
![Mobile View](./screenshots/mobile.png)

---

## ✨ Features

- 🎯 **Pixel-perfect design** - Recreated from [Figma community design](FIGMA_LINK)
- 📱 **Fully responsive** - Optimized for mobile, tablet, and desktop
- 🎨 **CSS-only slider** - No JavaScript required
- ♿ **Accessible** - Semantic HTML5 with proper ARIA labels
- 🎭 **Smooth animations** - Transitions and hover effects
- 🧩 **Modular SCSS** - Clean, organized, and maintainable code

---

## 🛠️ Technologies

- **HTML5** - Semantic markup
- **SCSS** - Modular stylesheets with BEM-inspired naming
- **CSS Grid & Flexbox** - Modern layout techniques
- **CSS Variables** - Centralized design tokens

---

## 🚀 Live Demo

👉 **[View Live Demo](YOUR_DEMO_LINK)**

---

## 💻 Installation & Usage

### Clone the repository
```bash
git clone https://github.com/MostafaGamalBisher/LaslesVPN-landingpage.git
cd LaslesVPN-landingpage
```

### Option 1: Open directly
Simply open `index.html` in your browser.

### Option 2: Compile SCSS (if making changes)
```bash
# Install dependencies
npm install -g sass

# Watch for changes
sass --watch assets/scss/main.scss:assets/css/main.css
```

### Option 3: Local server
```bash
# Using Python
python -m http.server 8000

# Using Node
npx serve
```

---

## 📁 Project Structure

LaslesVPN-landingpage/
├── index.html
├── assets/
│   ├── css/
│   │   └── main.css          # Compiled CSS
│   ├── scss/
│   │   ├── main.scss         # Main SCSS file
│   │   ├── _variables.scss   # CSS variables
│   │   ├── _global.scss      # Global styles
│   │   ├── _header.scss      # Header section
│   │   ├── _about.scss       # Hero/About section
│   │   ├── _features.scss    # Features section
│   │   ├── _pricing.scss     # Pricing cards
│   │   ├── _testimonials.scss
│   │   ├── _testimonials_slider.scss
│   │   ├── _help.scss        # Footer
│   │   ├── _responsive.scss  # Tablet/Desktop
│   │   └── _responsive_mobile.scss
│   ├── images/
│   └── icons/
├── screenshots/              # Project screenshots
└── README.md

---

## 🎨 Design Decisions

### Responsive Strategy
- **Mobile:** 0-743px (single column, optimized layouts)
- **Tablet:** 744px-1024px (two columns, adjusted spacing)
- **Desktop:** 1025px-1439px (full layout, standard spacing)
- **Large Desktop:** 1440px+ (max-width container)

### CSS-Only Slider
Used radio inputs + CSS `:checked` pseudo-class for testimonial slider:
- No JavaScript required
- Smooth transitions with CSS
- Keyboard accessible

### Modular SCSS
Separated concerns into individual files:
- Easy to maintain
- Clear code organization
- Reusable components

---

## 🎓 What I Learned

This project helped me practice and improve:

1. **Responsive Design Patterns**
   - Breakpoint strategy
   - Mobile layout optimization
   - Flexible grids

2. **Advanced CSS Techniques**
   - CSS Grid mastery
   - Flexbox layouts
   - CSS-only interactions
   - Pseudo-elements & pseudo-classes

3. **Code Organization**
   - Modular SCSS architecture
   - BEM-inspired naming
   - Variable-driven design

4. **Problem Solving**
   - Creative layout solutions for mobile
   - CSS-only slider implementation
   - Cross-browser compatibility

---

## 🐛 Known Issues / Future Improvements

- [ ] Add burger menu for mobile navigation
- [ ] Implement mobile-first approach (currently desktop-first)
- [ ] Add CSS design token system
- [ ] Improve accessibility (more ARIA labels)
- [ ] Add smooth scroll behavior
- [ ] Optimize images for web

---

## 📝 Credits

- **Design:** [LaslesVPN - Figma Community](FIGMA_LINK)
- **Developer:** [Mostafa Gamal Bisher](https://github.com/MostafaGamalBisher)
- **Icons & Images:** From original Figma design

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 🤝 Contributing

This is a learning project, but suggestions and feedback are welcome!

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 💬 Contact

Mostafa Gamal Bisher - [mgb.self.esteem@gmail.com](mailto:mgb.self.esteem@gmail.com)

Project Link: [https://github.com/MostafaGamalBisher/LaslesVPN-landingpage](https://github.com/MostafaGamalBisher/LaslesVPN-landingpage)

---

## 🌟 Show your support

Give a ⭐️ if you like this project!

---

**Note:** This is a practice/learning project recreated from a Figma community design for educational purposes.
