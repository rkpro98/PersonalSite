# Rajish Khatiwada - Portfolio Website

A modern, responsive portfolio website showcasing skills, projects, and professional information. Built with vanilla HTML, CSS, and JavaScript with a focus on performance, accessibility, and user experience.

## 🌟 Features

- **Modern Design**: Clean, professional layout with gradient backgrounds and smooth animations
- **Fully Responsive**: Optimized for all devices (desktop, tablet, mobile)
- **Interactive Elements**: Hover effects, scroll animations, and dynamic content
- **Smooth Navigation**: Fixed navbar with smooth scrolling and active section highlighting
- **Contact Form**: Functional contact form with validation and notifications
- **Performance Optimized**: Fast loading with efficient CSS and JavaScript
- **SEO Friendly**: Semantic HTML structure and meta tags
- **Accessibility**: WCAG compliant with proper ARIA labels and keyboard navigation

## 🎨 Sections

1. **Hero Section**: Eye-catching introduction with call-to-action buttons
2. **About**: Personal introduction with animated statistics
3. **Skills**: Categorized technical skills with interactive icons
4. **Projects**: Showcase of portfolio projects with technology tags
5. **Contact**: Contact form and social media links
6. **Footer**: Professional footer with copyright information

## 🛠️ Technologies Used

- **HTML5**: Semantic markup and accessibility features
- **CSS3**: Modern styling with Flexbox, Grid, animations, and responsive design
- **JavaScript (ES6+)**: Interactive functionality and smooth animations
- **Font Awesome**: Professional icons throughout the site
- **Google Fonts**: Poppins font family for modern typography

## 🚀 Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- Basic text editor or IDE (VS Code recommended)
- Local server (optional, for development)

### Installation

1. **Clone or download** the repository to your local machine
2. **Open the project** in your preferred code editor
3. **Launch the website** by opening `index.html` in your browser

### Local Development Server (Optional)

For better development experience, you can use a local server:

```bash
# Using Python 3
python -m http.server 8000

# Using Node.js (if you have live-server installed)
npx live-server

# Using PHP
php -S localhost:8000
```

Then open `http://localhost:8000` in your browser.

## 🎯 Customization Guide

### Personal Information

1. **Update contact details** in the contact section:
   - Email address
   - Phone number
   - Location
   - Social media links

2. **Modify the hero section**:
   - Change the name and title
   - Update the description
   - Customize the call-to-action buttons

3. **About section customization**:
   - Update the personal introduction
   - Modify the statistics (projects, experience, technologies)
   - Change the about image or icon

### Skills Section

Update the skills in the HTML file:

```html
<div class="skill-item">
    <i class="fab fa-your-icon"></i>
    <span>Your Skill</span>
</div>
```

### Projects Section

Add your projects by duplicating the project card structure:

```html
<div class="project-card">
    <div class="project-image">
        <i class="fas fa-your-icon"></i>
    </div>
    <div class="project-content">
        <h3>Your Project Name</h3>
        <p>Project description...</p>
        <div class="project-tech">
            <span class="tech-tag">Technology</span>
        </div>
        <div class="project-links">
            <a href="#" class="project-link">Live Demo</a>
            <a href="#" class="project-link">Code</a>
        </div>
    </div>
</div>
```

### Color Scheme

The website uses a modern blue and purple gradient theme. To change colors, update the CSS variables:

```css
:root {
    --primary-color: #3498db;
    --secondary-color: #9b59b6;
    --accent-color: #ffd700;
    --text-dark: #2c3e50;
    --text-light: #666;
}
```

### Fonts

To change the font family, update the Google Fonts import and CSS:

```css
@import url('https://fonts.googleapis.com/css2?family=YourFont:wght@300;400;600;700&display=swap');

body {
    font-family: 'YourFont', sans-serif;
}
```

## 📱 Responsive Design

The website is built with a mobile-first approach and includes:

- **Mobile Navigation**: Hamburger menu for small screens
- **Responsive Grid**: Flexible layouts that adapt to screen size
- **Touch-Friendly**: Optimized for touch interactions
- **Performance**: Optimized images and efficient CSS

### Breakpoints

- **Mobile**: < 768px
- **Tablet**: 768px - 1024px
- **Desktop**: > 1024px

## ⚡ Performance Features

- **Optimized CSS**: Efficient selectors and minimal reflow
- **Lazy Loading**: Images and animations load when needed
- **Smooth Animations**: Hardware-accelerated CSS transitions
- **Minimal JavaScript**: Lightweight vanilla JS implementation
- **CDN Resources**: Fast loading of external libraries

## 🔧 Browser Support

- **Chrome**: 60+ ✅
- **Firefox**: 55+ ✅
- **Safari**: 12+ ✅
- **Edge**: 79+ ✅
- **Internet Explorer**: Not supported ❌

## 📋 File Structure

```
portfolio/
├── index.html          # Main HTML file
├── styles.css          # CSS styles and animations
├── script.js           # JavaScript functionality
├── README.md           # Project documentation
└── .git/              # Git repository (if cloned)
```

## 🚀 Deployment

### GitHub Pages

1. Push your code to a GitHub repository
2. Go to repository Settings > Pages
3. Select source branch (usually `main` or `master`)
4. Your site will be available at `https://username.github.io/repository-name`

### Netlify

1. Drag and drop your project folder to [Netlify](https://netlify.com)
2. Or connect your GitHub repository for automatic deployments

### Vercel

1. Install Vercel CLI: `npm i -g vercel`
2. Run `vercel` in your project directory
3. Follow the deployment prompts

## 🐛 Troubleshooting

### Common Issues

1. **Icons not loading**: Check Font Awesome CDN link
2. **Animations not working**: Ensure JavaScript is enabled
3. **Form not submitting**: Currently shows notification only (no backend)
4. **Mobile menu not working**: Check JavaScript console for errors

### Development Tips

- Use browser developer tools for debugging
- Test on multiple devices and browsers
- Validate HTML and CSS using online validators
- Check accessibility with browser accessibility tools

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Contributing

Feel free to fork this project and customize it for your own portfolio! If you make improvements, consider submitting a pull request.

## 📞 Support

If you have questions or need help customizing the portfolio:

- Create an issue on GitHub
- Contact: rajish.khatiwada@email.com

---

**Built with ❤️ by Rajish Khatiwada**

*Last updated: 2024*
