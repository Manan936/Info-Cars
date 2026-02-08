# CarVerse X — The Ultimate Car Universe

A premium, modern car information and showcase platform built with HTML5, CSS3, and vanilla JavaScript. Explore hypercars, classics, electric beasts, and legendary machines in one interactive universe.

## 🌐 Live Site

Experience CarVerse X at: https://manan936.github.io/Info-Cars/

---

## ✨ Key Features

- **Home Page** – Stunning hero section with featured cars and call-to-action
- **Complete Car Catalogue** – Browse extensive collection of hypercars and performance vehicles
- **Brand Directory** – Explore cars organized by iconic manufacturers
- **Dynamic Car Details** – View specs, images, and descriptions for each vehicle (powered by JavaScript)
- **Brand Pages** – Dedicated pages for major car brands with detailed information
- **Modern Navigation** – Sticky navbar with dropdown menu for easy browsing
- **Responsive Design** – Fully optimized for desktop, tablet, and mobile devices
- **Dark Theme UI** – Premium dark-mode interface with red accent colors
- **About & Help Sections** – Learn more about the platform and get support
- **Contact Page** – Get in touch with the team

---

## 📁 Project Structure

```
Info-Cars/
│
├── index.html              (Home / Hero with featured cars)
├── cars.html               (Complete cars catalogue grid)
├── car-details.html        (Dynamic car detail page with specs)
├── brands.html             (Brand directory and overview)
├── brand-cars.html         (Brand-specific car listings)
├── brands-cars.html        (Alternative brand view)
├── about.html              (About CarVerse X platform)
├── help.html               (FAQ & support documentation)
├── contact.html            (Contact form)
│
├── css/
│   ├── main.css            (Core styles: navbar, layout, dark theme, utilities)
│   ├── cars.css            (Cars grid & brand page styles)
│   └── cars-details.css    (Car details page styles & specs layout)
│
├── js/
│   └── cars.js             (Car database & dynamic content rendering)
│
└── README.md               (This file)
```

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/Manan936/Info-Cars.git
cd Info-Cars
```

### 2. Open the Project

**Option A: Direct Browser**

- Simply double-click `index.html` to open in your default browser

**Option B: VS Code Live Server**

- Install the "Live Server" extension in VS Code
- Right-click `index.html` → Select "Open with Live Server"
- Automatically opens at `http://localhost:5500`

**Option C: Python HTTP Server**

```powershell
python -m http.server 8000
# Visit http://localhost:8000 in your browser
```

**Option D: Node.js http-server**

```powershell
npx http-server
# Serves on http://localhost:8080
```

---

## 🎨 Design & Customization

### Color Scheme (Dark Theme)

Edit the CSS variables in `css/main.css`:

```css
:root {
  --bg-dark: #0b0b0d; /* Main background */
  --bg-card: #151518; /* Card background */
  --bg-card-soft: #1c1c21; /* Soft card background */
  --text-main: #ffffff; /* Primary text */
  --text-muted: #b5b5b5; /* Secondary text */
  --text-soft: #8e8e93; /* Tertiary text */
  --accent: #e10600; /* Red accent color */
  --border-soft: #26262c; /* Subtle borders */
}
```

### Adding New Cars

Edit `js/cars.js` and add entries to the `cars` object:

```javascript
const cars = {
  "your-car-id": {
    name: "Car Name",
    image: "URL_to_image",
    tagline: "Short description",
    specs: {
      Brand: "Brand Name",
      Engine: "Engine specs",
      Power: "Horsepower",
      Speed: "Top speed",
      Drive: "Drivetrain",
    },
    description: "Detailed description of the car",
  },
};
```

### Customizing Content

- **Homepage**: Edit `index.html` to modify hero section and featured cars
- **Page Styling**: Update `css/main.css` for global styles, `css/cars.css` for car pages
- **Navigation**: Modify navbar structure in any HTML file's header section
- **Brand Information**: Update content in `brands.html` and brand-specific pages

---

## 🔧 Technologies Used

- **HTML5** – Semantic markup and structured content
- **CSS3** – Flexbox, Grid, animations, dark theme styling
- **JavaScript (Vanilla)** – Dynamic car data rendering, URL parameters, interactive features
- **Responsive Design** – Mobile-first approach with media queries
- **External Images** – Unsplash & Pixabay integration for car photography

---

## 📱 Browser Compatibility

- Chrome/Edge (Latest)
- Firefox (Latest)
- Safari (Latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

---

## 🤝 Contributing

Feel free to fork this repository and submit pull requests for:

- New car entries
- UI/UX improvements
- Bug fixes
- Feature additions

---

## 📄 License

This project is open source and available under the MIT License.

---

**Made with ❤️ by [Manan936](https://github.com/Manan936)**

## 📱 Browser Support

- Chrome/Edge (Latest)
- Firefox (Latest)
- Safari (Latest)

---

## 🐛 Future Enhancements (Suggestions)

- Add a small JavaScript layer to render dynamic car data
- Replace demo/static content with a JSON dataset or API
- Implement backend handling for the contact form
- Add search and filter functionality on `cars.html`
- Improve accessibility (WCAG 2.1 AA)

---

## 📝 License

Open-source project — use and modify as you like.

---

## 👤 Author

**Manan936**  
GitHub: [Manan936](https://github.com/Manan936)

**Project Status:** Static demo / In development

---

**Last Updated:** February 8, 2026
