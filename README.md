# UI/UX Designer Portfolio

A modern, responsive portfolio website for UI/UX designers. Built with HTML, CSS, and vanilla JavaScript.

## Features

- 🎨 Modern, clean design with gradient accents
- 📱 Fully responsive for all devices
- ⚡ Smooth animations and micro-interactions
- 🎯 Case study template included
- 💼 Sections for: Hero, Work, Process, About, Skills, Testimonials, Contact
- 🌙 Scroll-triggered animations
- 📝 Contact form with validation
- 🎪 Custom notification system

## Getting Started

1. **Open in Browser**
   - Simply open `index.html` in any modern web browser
   - No build process or dependencies required

2. **Customize Content**
   - Edit the text content in `index.html` to add your information
   - Replace placeholder images with your own
   - Update links to your social profiles

3. **Deploy**
   - Upload to any web hosting service (Netlify, Vercel, GitHub Pages, etc.)
   - Or use with Framer by recreating the design visually

## File Structure

```
portfolio/
├── index.html              # Main portfolio page
├── case-study-nova.html   # Case study template
├── styles.css             # All styles
├── script.js              # Interactions & animations
└── README.md              # This file
```

## Customization Guide

### 1. Personal Information

Update these in `index.html`:

```html
<!-- Hero Section -->
<span class="badge-dot"></span> Available for new projects
<h1>Crafting digital experiences<br><span class="gradient-text">that matter.</span></h1>
<p>UI/UX Designer with 5+ years...</p>

<!-- About Section -->
<img src="YOUR_PHOTO" alt="Your Name">
<h2>Designing with purpose,<br>building with passion.</h2>
```

### 2. Projects

Find the `projects-grid` section and update:

```html
<article class="project-card" data-category="mobile">
    <div class="project-image">
        <img src="YOUR_PROJECT_IMAGE" alt="Project Name">
    </div>
    <div class="project-content">
        <span class="project-category">Mobile App</span>
        <h3 class="project-title">Your Project Name</h3>
        <p class="project-desc">Brief description of the project...</p>
        <div class="project-tags">
            <span>UI Design</span>
            <span>User Research</span>
        </div>
    </div>
</article>
```

### 3. Skills & Tools

Update the `skills-grid` section with your actual skills and tools.

### 4. Contact Information

Update the contact section with your email and social links:

```html
<a href="mailto:YOUR_EMAIL" class="contact-link">
    hello@yourname.design
</a>
```

### 5. Colors

Edit CSS variables in `styles.css`:

```css
:root {
    --primary: #6366f1;        /* Main accent color */
    --primary-dark: #4f46e5;   /* Darker accent */
    --secondary: #ec4899;      /* Secondary accent */
    --text-primary: #0f172a;   /* Main text color */
    --bg-primary: #ffffff;     /* Background color */
}
```

### 6. Images

Replace placeholder images from Unsplash with your own:
- Profile photos
- Project screenshots
- Case study images

## Case Study Template

The `case-study-nova.html` file demonstrates a detailed case study format. Copy this file for each project and customize:

- Hero image and metadata
- Overview section
- Challenge & Solution cards
- Design Process steps
- Gallery of designs
- Results with metrics
- Key Takeaways

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Credits

- **Fonts**: Google Fonts (Inter, Space Grotesk)
- **Icons**: Lucide Icons (inline SVGs)
- **Images**: Unsplash (placeholders)

## License

Free to use for personal and commercial projects.

---

Made with ❤️ for designers, by designers.
