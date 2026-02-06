# 🏎️ CarVerse X — The Ultimate Car Universe

A sleek, modern car encyclopedia web application built with vanilla HTML, CSS, and JavaScript. Browse luxury cars, hypercars, EVs, and classics — all in one place.

## 📍 Live Site

Visit: [Info-Cars](https://manan936.github.io/Info-Cars/)

---

## ✨ Features

- **Home Page**: Hero section with featured machines and smooth animations
- **All Cars Catalogue**: Browse a curated collection of luxury and performance vehicles
- **Brand Listings**: Organized by manufacturer
- **Car Details Pages**: Individual pages with specs, top speed, acceleration, engine info
- **Contact Form**: Get in touch (demo-enabled with form validation)
- **About & Help Pages**: Information and support sections
- **Responsive Design**: Fully mobile, tablet, and desktop optimized
- **Glass-Morphism UI**: Modern frosted-glass aesthetic with smooth fade-in animations
- **Dark Mode**: Sleek dark theme throughout

---

## 📁 Project Structure

```
infocars/
│
├── index.html              (Home / Hero with featured cars)
├── cars.html               (All cars catalogue)
├── brands.html             (Brand-wise listing)
├── car-details.html        (Individual car detail page)
├── about.html              (About CarVerse X)
├── help.html               (FAQ & support)
├── contact.html            (Contact form)
│
├── css/
│   ├── main.css            (Core styles: navbar, cards, layout, utilities)
│   ├── cars.css            (Cars-specific styling)
│   └── animations.css      (Fade-in & utility animations)
│
├── js/
│   ├── main.js             (Form handling, nav active state, utilities)
│   └── cars.js             (Car dataset, rendering functions, detail pages)
│
├── assets/
│   ├── images/             (Add car images here)
│   └── icons/              (SVG icons — optional)
│
└── README.md               (This file)
```

---

## 🚀 Quick Start

### 1. Clone the Repository

```bash
git clone https://github.com/Manan936/Info-Cars.git
cd Info-Cars
```

### 2. Open Locally

**Option A: Direct browser**

```
Double-click index.html
```

**Option B: Live Server (VS Code)**

- Install "Live Server" extension
- Right-click `index.html` → "Open with Live Server"

**Option C: Python HTTP Server**

```bash
python -m http.server 8000
# Then visit http://localhost:8000
```

### 3. Explore the Site

- Home: Featured cars and hero section
- Cars: Full catalogue with links to details
- Brands: Brand listings
- Car Details: Click any car card to see full specs
- Contact: Fill and submit the contact form
- About & Help: Learn more about the site

---

## 🎨 Customization

### Add Your Own Cars

Edit `js/cars.js` and update the `demoCars` array:

```javascript
const demoCars = [
  {
    id: 1,
    brand: "Your Brand",
    name: "Model Name",
    price: "₹ X.XX Cr",
    img: "https://image-url.jpg",
    description: "Short description.",
    stats: { topSpeed: "300 km/h", zeroToHundred: "3.5s", engine: "V8" },
  },
  // Add more cars...
];
```

### Customize Colors

Update `css/main.css` root variables:

```css
:root {
  --primary: #ff2e2e; /* Accent color */
  --dark: #0f0f0f; /* Dark background */
  --light: #ffffff; /* Light text */
  --gray: #cccccc;
}
```

### Change Hero Background

In `css/main.css`, update `.hero`:

```css
.hero {
  background: url("YOUR_IMAGE_URL") center/cover;
}
```

---

## 🔧 Technologies

- **HTML5** – Semantic markup
- **CSS3** – Flexbox, Grid, Glass-morphism, animations
- **JavaScript (Vanilla)** – No frameworks or dependencies
- **Responsive Design** – Mobile-first approach

---

## 📱 Browser Support

- ✅ Chrome/Edge (Latest)
- ✅ Firefox (Latest)
- ✅ Safari (Latest)
- ⚠️ IE11 (Limited support)

---

## ✅ Completed Implementation

- [x] Full project structure created (HTML, CSS, JS, assets)
- [x] Standardized HTML templates across all pages
- [x] Implemented car catalogue rendering with demo data
- [x] Created car details page with query parameter support
- [x] Built responsive CSS with glass-morphism design
- [x] Added smooth fade-in animations
- [x] Contact form with demo submission handling
- [x] Active navigation link highlighting
- [x] Mobile responsive design
- [x] Comprehensive README documentation

---

## 🐛 Future Enhancements

- [ ] Replace demo data with real API/database
- [ ] Implement backend for contact form submissions
- [ ] Add search and filter functionality
- [ ] Implement car comparison feature
- [ ] Add image lazy-loading
- [ ] Improve accessibility (WCAG 2.1 AA)
- [ ] Add dark/light theme toggle
- [ ] Performance optimization (minification, caching)

---

## 📝 License

Open-source project. Feel free to use, modify, and share!

---

## 👤 Author

**Manan936**  
GitHub: [Manan936](https://github.com/Manan936)

**Project Status:** ✅ Complete & Production-Ready

---

**Last Updated:** February 6, 2026
