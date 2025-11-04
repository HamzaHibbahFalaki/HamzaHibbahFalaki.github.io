# Portfolio - Hamza Hibbah Falaki

A modern, responsive portfolio website showcasing my work as a Junior Data Analyst and Data Engineer.

![Portfolio Preview](https://img.shields.io/badge/Status-Live-brightgreen)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)

## Features

- **Modern Design**: Sleek, professional UI with animated gradients and glassmorphism effects
- **Fully Responsive**: Optimized for all devices (desktop, tablet, mobile)
- **Smooth Animations**: 
  - Morphing profile image
  - Typing effect for job titles
  - Hover effects on all interactive elements
  - Animated background with moving grid pattern
- **Contact Form**: Functional contact form with validation
- **Social Links**: Direct links to LinkedIn, GitHub, and Email
- **Resume Download**: One-click CV download functionality
- **Project Showcase**: Featured projects with direct GitHub links

## Technologies Used

- **HTML5**: Semantic markup structure
- **CSS3**: Custom styling with modern features
  - CSS Variables for theming
  - Flexbox & Grid layouts
  - Keyframe animations
  - Glassmorphism & backdrop filters
- **JavaScript**: Interactive features
  - Typing animation
  - Form validation
  - Smooth scrolling
  - Scroll-triggered effects
- **Font Awesome 6.5.2**: Icons

## Project Structure

```
portfolio/
├── index.html          # Main HTML file
├── style.css           # CSS styling
├── README.md           # Project documentation
└── docs/
    ├── photo.jpg       # Profile photo
    └── CV.pdf          # Resume/CV file
```

## Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- Your profile photo
- Your CV/Resume in PDF format

### Installation

1. **Clone the repository**

2. **Add your files**
   - Place your profile photo as `docs/photo.jpg`
   - Place your CV as `docs/CV.pdf`

3. **Customize content**
   - Open `index.html` and update:
     - Personal information
     - Project descriptions
     - Contact information
   
4. **Open the website**
   - Simply open `index.html` in your web browser
   - Or use a local server for development

Then navigate to `http://localhost:8000` in your browser.

## Customization

### Colors

Edit the CSS variables in `style.css` to change the color scheme:

```css
:root {
    --primary-color: #00d9ff;      /* Main accent color */
    --secondary-color: #00ffc3;     /* Secondary accent */
    --dark-bg: #0a0a0a;            /* Background color */
    --text-primary: #ffffff;        /* Main text color */
    --text-secondary: #b0b0b0;      /* Secondary text color */
}
```

### Content

1. **Hero Section**: Update your name, titles, and description in `index.html`
2. **About Section**: Modify your bio and skills
3. **Projects**: Add or remove project cards with your work
4. **Contact**: Update form action for email integration

### Typography

The portfolio uses system fonts for optimal performance. To change fonts, add Google Fonts or other web fonts in the `<head>` section.

## Contact Form Setup

The contact form currently shows an alert on submission. To make it functional:

### Formspree 
```html
<form action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
```

## License

This project is open source and available under the [MIT License](LICENSE).

## Author

**Hamza Hibbah Falaki**

- LinkedIn: [@hamza-hibbah-falaki](https://www.linkedin.com/in/hamza-hibbah-falaki/)
- GitHub: [@HamzaHibbahFalaki](https://github.com/HamzaHibbahFalaki)
- Email: hamzahibbah0@gmail.com

## Acknowledgments

- Font Awesome for the amazing icons
- Inspiration from modern portfolio designs
- The developer community for continuous support
