# Aniko Eye Cart 8

A premium optical retail showroom website built with modern web technologies. This project features a responsive design, dark/light mode toggle, multi-language support, and an elegant user interface for showcasing optical products and services.

## 🌟 Features

- **Responsive Design**: Fully responsive layout that works on all devices
- **Dark/Light Mode**: Toggle between dark and light themes
- **Multi-language Support**: English and Hindi language options
- **Modern UI/UX**: Clean, professional design with smooth animations
- **Premium Branding**: Sophisticated optical retail presentation
- **Interactive Elements**: Engaging user interface components
- **Accessibility**: Built with accessibility best practices

## 🛠️ Technologies Used

- **HTML5**: Semantic markup structure
- **CSS3**: Modern styling with CSS variables, flexbox, and grid
- **JavaScript**: Interactive functionality and theme switching
- **Font Awesome**: Icon library for UI elements
- **Google Fonts**: Poppins and Montserrat font families
- **Leaflet**: Map integration for location services

## 📁 Project Structure

```
/Aniko-Eye-Cart
│
├── index.html              ← Main landing page
├── styles.css              ← Main stylesheet with dark/light theme support
├── Readme.md               ← Project documentation
│
└── /images
    └── man_holding_eyeglasses.jpg  ← Hero section image
```

## 🚀 Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- A web server (optional, for local development)

### Installation

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd Aniko-Eye-Cart
   ```

2. Open the project:
   - Simply open `index.html` in your web browser, or
   - Serve the files using a local web server:
     ```bash
     # Using Python
     python -m http.server 8000
     
     # Using Node.js (if you have http-server installed)
     npx http-server
     
     # Using PHP
     php -S localhost:8000
     ```

3. View the website:
   - Direct file: Open `index.html` in your browser
   - Local server: Navigate to `http://localhost:8000`

## 🎨 Design Features

### Color Scheme
- **Primary**: Blue (#2563eb)
- **Secondary**: Sky Blue (#0ea5e9)
- **Accent**: Amber (#f59e0b)
- **Light Theme**: Clean whites and light blues
- **Dark Theme**: Modern dark grays and blues

### Typography
- **Primary Font**: Poppins (300, 400, 500, 600, 700)
- **Accent Font**: Montserrat (700, 800)

### Layout Components
- Header with logo and utility controls
- Hero section with compelling visuals
- Feature sections
- Responsive navigation
- Footer with contact information
- Testimonials section

## 🎯 Browser Compatibility

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 📱 Responsive Breakpoints

- **Desktop**: 1200px and above
- **Tablet**: 768px - 1199px
- **Mobile**: Below 768px

## 🔧 Customization

### Changing Colors
Edit the CSS variables in `styles.css`:
```css
:root {
  --primary: #your-color;
  --secondary: #your-color;
  /* ... other variables */
}
```

### Adding New Sections
1. Add HTML structure in `index.html`
2. Style with CSS in `styles.css`
3. Add JavaScript functionality if needed

### Language Support
To add a new language:
1. Add the language option in the dropdown
2. Create translation objects in JavaScript
3. Update the language switching function

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🤝 Contributing

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📞 Contact

For questions or support, please contact the development team.

## 🙏 Acknowledgments

- Font Awesome for icons
- Google Fonts for typography
- Leaflet for map integration
- All contributors and testers

---

*Built with ❤️ for premium optical retail experiences*
