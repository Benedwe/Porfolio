# Benjamin Edward - Personal Portfolio

A modern, responsive portfolio website showcasing skills, projects, and professional experience with smooth animations and email functionality.

## Features

- **Fully Responsive Design**: Works on all device sizes (mobile, tablet, desktop)
- **Smooth Animations**: CSS animations and transitions for enhanced user experience
- **Modern UI**: Clean, professional design with gradient accents
- **Contact Form**: Email functionality using Formspree (no server-side code required)
- **Performance Optimized**: Lightweight and fast-loading
- **Cross-Browser Compatible**: Works on all modern browsers

## Technologies Used

- HTML5
- CSS3 (with animations and responsive design)
- JavaScript (ES6+)
- Font Awesome Icons
- Google Fonts
- Formspree (for contact form handling)

## Getting Started

### Prerequisites

- A modern web browser
- A local server environment (for testing contact form functionality)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/portfolio.git
   ```

2. Navigate to the project directory:
   ```bash
   cd portfolio
   ```

3. Open `index.html` in your browser or serve it using a local server:
   ```bash
   # Using Python 3
   python -m http.server 8000
   
   # Using Node.js (if you have http-server installed)
   npx http-server
   
   # Using PHP
   php -S localhost:8000
   ```

### Project Structure

```
portfolio/
├── index.html          # Main HTML file
├── style.css           # Main stylesheet with animations
├── script.js           # JavaScript functionality
├── thank-you.html      # Thank you page after form submission
├── favicon.ico         # Website favicon
├── images/             # All project images and assets
│   ├── *.png           # Image files
│   ├── *.jpg           # JPEG images
│   └── *.svg           # SVG icons
└── README.md           # This file
```

## Customization

### Updating Contact Form

1. Sign up for a free account at [Formspree](https://formspree.io/)
2. Create a new form and get your unique form endpoint
3. Replace `YOUR_FORM_ID` in the form action attribute in `index.html`:
   ```html
   <form action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
   ```

### Changing Colors

All colors are defined using CSS variables in `style.css`. You can easily customize the color scheme by modifying the `:root` variables:

```css
:root {
    --primary-dark: #1c1918;
    --primary-light: #d7d7d7;
    --accent-color: #ff6b35;
    --text-dark: #333;
    --text-light: #f5f5f5;
}
```

### Adding Projects

To add new projects to the portfolio section:

1. Add new images to the `images/` folder
2. Update the portfolio grid in `index.html`:
   ```html
   <div class="grid-col col7" style="background:url(./images/new-project.png) center / cover no-repeat;"></div>
   ```

## Deployment

### GitHub Pages

1. Push your code to a GitHub repository
2. Go to Repository Settings
3. Scroll to "GitHub Pages" section
4. Select "main" branch and "/ (root)" folder
5. Click "Save"

### Other Hosting Options

- Netlify
- Vercel
- Firebase Hosting
- Any static site hosting service

## Email Functionality

The contact form uses Formspree to handle form submissions without requiring server-side code. All messages are sent directly to the configured email address without exposing it to users.

To set up:
1. Replace `YOUR_FORM_ID` in the form action with your actual Formspree form ID
2. Configure your email address in the Formspree dashboard

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Contributing

1. Fork the repository
2. Create a new branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a pull request

## License

This project is open source and available under the [MIT License](LICENSE).

## Author

**Benjamin Edward**
- Website: [Your Portfolio URL]
- GitHub: [@Benedwe](https://github.com/Benedwe)
- LinkedIn: [Your LinkedIn Profile]

## Acknowledgments

- [Font Awesome](https://fontawesome.com/) for icons
- [Google Fonts](https://fonts.google.com/) for typography
- [Formspree](https://formspree.io/) for form handling