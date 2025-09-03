# Portfolio Website

A beautiful, responsive portfolio website built with HTML, Bootstrap, and JavaScript featuring smooth animations and hover effects.

## Features

- ✨ **Modern Design**: Clean and professional layout with gradient backgrounds
- 📱 **Fully Responsive**: Works perfectly on all devices and screen sizes
- 🎨 **Smooth Animations**: CSS animations and JavaScript-powered interactions
- 🖱️ **Hover Effects**: Interactive hover effects on buttons, cards, and navigation
- 📊 **Skills Section**: Animated progress bars and skill cards
- 🚀 **Projects Showcase**: Beautiful project cards with hover animations
- 📧 **Contact Form**: Functional contact form with validation
- 🌟 **Particle Effects**: Dynamic background particles in hero section
- 📱 **Mobile Optimized**: Touch-friendly mobile navigation

## Sections

1. **Hero Section** - Eye-catching introduction with animated text and particles
2. **About Section** - Personal information with statistics and profile image
3. **Skills Section** - Technical skills with animated progress bars
4. **Projects Section** - Portfolio projects with interactive cards
5. **Contact Section** - Contact information and form
6. **Footer** - Social media links and copyright

## Technologies Used

- **HTML5** - Semantic markup
- **CSS3** - Modern styling with animations and hover effects
- **Bootstrap 5** - Responsive grid system and components
- **JavaScript (ES6+)** - Interactive functionality and animations
- **Font Awesome** - Icons
- **Google Fonts** - Typography

## Getting Started

### Prerequisites

- A modern web browser
- Basic knowledge of HTML, CSS, and JavaScript (for customization)

### Installation

1. Download or clone the repository
2. Open `index.html` in your web browser
3. Customize the content to match your information

## Customization Guide

### Personal Information

Edit the following sections in `index.html`:

```html
<!-- Hero Section -->
<h1>Hi, I'm <span class="text-primary">Your Name</span></h1>
<h2>Full Stack Developer</h2>
<p>Passionate about creating beautiful and functional web applications...</p>

<!-- About Section -->
<p>I'm a passionate and creative developer...</p>

<!-- Contact Section -->
<p>your.email@example.com</p>
<p>+1 (555) 123-4567</p>
<p>New York, NY</p>
```

### Skills and Progress Bars

Update the skills section in `index.html`:

```html
<div class="skill-item mb-3">
    <div class="d-flex justify-content-between mb-2">
        <span>Your Skill</span>
        <span>90%</span>
    </div>
    <div class="progress">
        <div class="progress-bar" role="progressbar" style="width: 90%"></div>
    </div>
</div>
```

### Projects

Replace the placeholder projects with your own:

```html
<div class="project-card card h-100">
    <img src="your-project-image.jpg" class="card-img-top" alt="Project Name">
    <div class="card-body">
        <h5 class="card-title">Your Project Name</h5>
        <p class="card-text">Project description...</p>
        <div class="project-tags mb-3">
            <span class="badge bg-primary me-1">Technology</span>
        </div>
    </div>
    <div class="card-footer bg-transparent border-0">
        <div class="d-flex justify-content-between">
            <a href="your-demo-link" class="btn btn-outline-primary btn-sm">Live Demo</a>
            <a href="your-source-code-link" class="btn btn-outline-secondary btn-sm">Source Code</a>
        </div>
    </div>
</div>
```

### Colors and Styling

Customize colors in `style.css`:

```css
:root {
    --primary-color: #007bff;
    --secondary-color: #6c757d;
    --success-color: #28a745;
    --danger-color: #dc3545;
    --dark-color: #2c3e50;
}
```

### Images

Replace placeholder images:
- Profile image in About section
- Project images in Projects section
- Use your own photos or professional stock images

## Hover Effects

The portfolio includes various hover effects:

- **Buttons**: Scale, shadow, and color transitions
- **Cards**: Lift effect with enhanced shadows
- **Navigation**: Underline animations and color changes
- **Skill Cards**: Scale and border color changes
- **Social Links**: Rotation and color transitions

## Animations

- **Fade-in animations** on scroll
- **Typing effect** in hero section
- **Particle effects** in background
- **Progress bar animations** for skills
- **Counter animations** for statistics
- **Smooth scrolling** navigation

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## Performance Tips

1. **Optimize Images**: Use compressed images (WebP, JPEG)
2. **Minimize CSS/JS**: Consider minifying files for production
3. **CDN Usage**: Bootstrap and Font Awesome are loaded from CDN
4. **Lazy Loading**: Images can be lazy-loaded for better performance

## Deployment

### GitHub Pages

1. Push your code to a GitHub repository
2. Go to Settings > Pages
3. Select source branch (usually `main`)
4. Your portfolio will be available at `https://username.github.io/repository-name`

### Netlify

1. Drag and drop your project folder to Netlify
2. Your site will be deployed automatically
3. Custom domain can be added in settings

### Vercel

1. Connect your GitHub repository to Vercel
2. Deploy automatically on every push
3. Get a custom URL and domain

## Customization Examples

### Adding a New Section

```html
<section id="new-section" class="py-5">
    <div class="container">
        <div class="row">
            <div class="col-12 text-center mb-5">
                <h2 class="section-title">New Section</h2>
                <div class="title-underline"></div>
            </div>
        </div>
        <!-- Your content here -->
    </div>
</section>
```

### Adding Custom CSS

```css
/* Add to style.css */
.new-section {
    background: linear-gradient(135deg, #your-color1, #your-color2);
}

.new-section .custom-element {
    transition: all 0.3s ease;
}

.new-section .custom-element:hover {
    transform: scale(1.1);
}
```

### Adding JavaScript Functionality

```javascript
// Add to script.js
function customFunction() {
    // Your custom functionality
    console.log('Custom function executed!');
}

// Call when needed
document.addEventListener('DOMContentLoaded', function() {
    customFunction();
});
```

## Troubleshooting

### Common Issues

1. **Images not loading**: Check file paths and ensure images exist
2. **CSS not applying**: Verify CSS file is linked correctly
3. **JavaScript errors**: Check browser console for error messages
4. **Responsive issues**: Test on different screen sizes

### Performance Issues

1. **Slow loading**: Optimize images and minimize HTTP requests
2. **Animation lag**: Reduce animation complexity on mobile devices
3. **Scroll performance**: Use `transform` instead of `top/left` for animations

## Contributing

Feel free to submit issues and enhancement requests!

## License

This project is open source and available under the [MIT License](LICENSE).

## Support

If you need help customizing your portfolio:

1. Check the browser console for errors
2. Verify all file paths are correct
3. Ensure all dependencies are loaded
4. Test on different browsers and devices

## Credits

- **Bootstrap**: CSS framework
- **Font Awesome**: Icons
- **Google Fonts**: Typography
- **Placeholder.com**: Sample images

---

**Happy coding! 🚀**

Your portfolio is now ready to showcase your skills and projects to the world!

