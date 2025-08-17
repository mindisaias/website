# Personal Portfolio Website

A modern, responsive personal portfolio website built with HTML, CSS, and JavaScript. Features a clean design, smooth animations, and mobile-first responsive layout.

## ✨ Features

- **Responsive Design**: Works perfectly on all devices
- **Modern UI/UX**: Clean, professional design with smooth animations
- **Interactive Elements**: Hover effects, scroll animations, and smooth transitions
- **Mobile Navigation**: Hamburger menu for mobile devices
- **Contact Form**: Functional contact form with validation
- **SEO Optimized**: Semantic HTML structure
- **Fast Loading**: Optimized CSS and JavaScript
- **Cross-browser Compatible**: Works on all modern browsers

## 🚀 Getting Started

### 1. Customize Your Information

#### Personal Details
Edit `index.html` and update:
- Your name (replace "Your Name" throughout the file)
- Professional title
- About me description
- Contact information (email, phone, location)
- Social media links
- Experience statistics

#### Projects Section
Update the projects in the projects section:
- Project names and descriptions
- Technologies used
- Live demo and GitHub links
- Project images (replace Font Awesome icons with actual project screenshots)

#### Skills Section
Modify the skills to match your expertise:
- Add/remove skill categories
- Update skill names and icons
- Reorganize based on your proficiency

### 2. Add Your Photos

Replace the placeholder icons with your actual photos:
- **Hero Section**: Add your profile picture
- **About Section**: Add a professional photo
- **Projects**: Add screenshots of your projects

Example:
```html
<!-- Replace this -->
<div class="hero-avatar">
    <i class="fas fa-user-circle"></i>
</div>

<!-- With this -->
<div class="hero-avatar">
    <img src="images/profile-photo.jpg" alt="Your Name" style="width: 100%; height: 100%; object-fit: cover; border-radius: 50%;">
</div>
```

### 3. Customize Colors and Styling

Edit `styles.css` to match your brand:
- **Primary Colors**: Update `#6366f1` (indigo) to your preferred color
- **Accent Colors**: Modify `#fbbf24` (yellow) for highlights
- **Background Colors**: Adjust section backgrounds
- **Typography**: Change font weights and sizes

### 4. Update Contact Form

The contact form currently shows a success message. To make it functional:

#### Option A: Use a Form Service
- [Formspree](https://formspree.io/)
- [Netlify Forms](https://docs.netlify.com/forms/setup/)
- [EmailJS](https://www.emailjs.com/)

#### Option B: Backend Integration
- Connect to your own backend API
- Use serverless functions (Vercel, Netlify)
- Integrate with your CMS

## 🎨 Customization Examples

### Changing the Color Scheme
```css
:root {
    --primary-color: #your-color;
    --accent-color: #your-accent;
    --text-color: #your-text;
    --background-color: #your-bg;
}
```

### Adding Custom Fonts
```html
<link href="https://fonts.googleapis.com/css2?family=Your+Font:wght@400;600;700&display=swap" rel="stylesheet">
```

```css
body {
    font-family: 'Your Font', sans-serif;
}
```

### Adding More Sections
```html
<section id="experience" class="experience">
    <div class="container">
        <h2 class="section-title">Work Experience</h2>
        <!-- Add your experience content -->
    </div>
</section>
```

## 📱 Mobile Optimization

The website is already mobile-optimized with:
- Responsive grid layouts
- Mobile-first navigation
- Touch-friendly buttons
- Optimized typography for small screens

## 🚀 Deployment

### GitHub Pages
1. Push your code to GitHub
2. Go to repository Settings > Pages
3. Select source branch (usually `main`)
4. Your site will be available at `https://username.github.io/repository-name`

### Netlify
1. Drag and drop your project folder to [Netlify](https://netlify.com)
2. Your site will be deployed instantly
3. Custom domain can be added in settings

### Vercel
1. Connect your GitHub repository to [Vercel](https://vercel.com)
2. Automatic deployments on every push
3. Custom domain support included

### Traditional Hosting
1. Upload files to your web server
2. Ensure all files are in the root directory
3. Test all functionality

## 🔧 Performance Optimization

The website includes several performance features:
- **Lazy Loading**: Images load only when needed
- **Debounced Scroll Events**: Optimized scroll handling
- **CSS Animations**: Hardware-accelerated transitions
- **Minified Assets**: Consider minifying CSS/JS for production

## 📊 Analytics and SEO

### Google Analytics
Add to `<head>` section:
```html
<!-- Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=GA_MEASUREMENT_ID"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'GA_MEASUREMENT_ID');
</script>
```

### SEO Meta Tags
Update the `<head>` section with your information:
```html
<meta name="description" content="Your Name - Full-Stack Developer Portfolio">
<meta name="keywords" content="developer, portfolio, web development, your skills">
<meta name="author" content="Your Name">
<meta property="og:title" content="Your Name - Portfolio">
<meta property="og:description" content="Full-Stack Developer Portfolio">
<meta property="og:image" content="https://yoursite.com/images/og-image.jpg">
```

## 🐛 Troubleshooting

### Common Issues

1. **Images not loading**: Check file paths and ensure images exist
2. **Form not working**: Verify form service configuration
3. **Mobile menu not working**: Check JavaScript console for errors
4. **Styling issues**: Clear browser cache and check CSS file paths

### Browser Support
- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Contributing

Feel free to submit issues and enhancement requests!

## 📞 Support

If you need help customizing your portfolio:
1. Check this README for common solutions
2. Review the code comments for guidance
3. Open an issue in the repository

---

**Happy coding! 🎉**

Your portfolio website is now ready to showcase your skills and projects to the world!
