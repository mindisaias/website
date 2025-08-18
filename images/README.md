# Images Directory

This directory is for storing all the images used in your portfolio website.

## 📁 Recommended Image Structure

### Profile Photos
- `profile-photo.jpg` - Your main profile picture (recommended: 400x400px)
- `about-photo.jpg` - Professional photo for about section (recommended: 500x500px)

### Project Screenshots
- `project1-screenshot.jpg` - Screenshot of your first project
- `project2-screenshot.jpg` - Screenshot of your second project
- `project3-screenshot.jpg` - Screenshot of your third project

### Other Images
- `og-image.jpg` - Open Graph image for social media sharing (recommended: 1200x630px)
- `favicon.ico` - Website favicon (16x16px, 32x32px)

## 🖼️ Image Guidelines

### Format
- Use **JPG** for photos and screenshots
- Use **PNG** for images with transparency
- Use **WebP** for better compression (with JPG fallback)

### Sizes
- **Profile photos**: 400x400px minimum
- **Project screenshots**: 800x600px minimum
- **Hero background**: 1920x1080px minimum
- **Social sharing**: 1200x630px

### Optimization
- Compress images to reduce file size
- Use descriptive filenames
- Include alt text for accessibility

## 🔄 How to Replace Placeholder Icons

In your HTML files, replace Font Awesome icons with actual images:

```html
<!-- Before (placeholder) -->
<div class="hero-avatar">
    <i class="fas fa-user-circle"></i>
</div>

<!-- After (your photo) -->
<div class="hero-avatar">
    <img src="images/profile-photo.jpg" alt="Your Name" style="width: 100%; height: 100%; object-fit: cover; border-radius: 50%;">
</div>
```

## 📱 Responsive Images

For better performance, consider using different image sizes for different devices:

```html
<picture>
    <source media="(min-width: 768px)" srcset="images/profile-photo-large.jpg">
    <source media="(min-width: 480px)" srcset="images/profile-photo-medium.jpg">
    <img src="images/profile-photo-small.jpg" alt="Your Name">
</picture>
```

## 🚀 Image Hosting Alternatives

If you prefer not to store images locally:

- **Cloudinary** - Image optimization and CDN
- **Imgur** - Free image hosting
- **GitHub** - Store in your repository
- **CDN Services** - Fast global delivery

Remember to update image paths in your HTML files accordingly!
