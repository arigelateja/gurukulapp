# Little Stars Preschool Website

A modern, responsive website for preschool education similar to Kidzee.com, built with HTML, CSS, and JavaScript.

## Features

### 🎨 Modern Design
- Kid-friendly color scheme with vibrant gradients
- Smooth animations and hover effects
- Responsive design that works on all devices
- Clean, professional layout

### 📱 Responsive Layout
- Mobile-first design approach
- Hamburger menu for mobile navigation
- Optimized for tablets and desktop screens
- Touch-friendly interface elements

### 🚀 Interactive Elements
- Smooth scrolling navigation
- Animated counters for statistics
- Interactive gallery with lightbox
- Contact form with validation
- Loading animations
- Parallax effects

### 📋 Sections Included
1. **Hero Section** - Eye-catching landing area with call-to-action buttons
2. **About Us** - School mission, features, and statistics
3. **Programs** - Three age-appropriate programs (Toddler, Preschool, Pre-K)
4. **DayCare** - Services, features, and daily schedule
5. **Photo Gallery** - Interactive image showcase
6. **Contact** - Contact information and inquiry form
7. **Footer** - Links, social media, and additional information

## File Structure

```
website/
├── index.html          # Main HTML file
├── styles.css          # CSS styles and responsive design
├── script.js           # JavaScript functionality
└── README.md          # This file
```

## Getting Started

1. **Open the website**: Simply open `index.html` in your web browser
2. **Local server** (recommended): Use a local server for best experience:
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js
   npx serve .
   
   # Using PHP
   php -S localhost:8000
   ```

## Customization

### Colors
The website uses a consistent color palette defined in CSS:
- Primary: `#ff6b6b` (Coral red)
- Secondary: `#4ecdc4` (Teal)
- Accent: `#667eea` (Blue)
- Background: `#f8f9fa` (Light gray)

### Content Updates
1. **School Information**: Update the school name, address, phone, and email in the HTML
2. **Programs**: Modify program descriptions, age ranges, and features
3. **Statistics**: Change the numbers in the About section stats
4. **Images**: Replace placeholder gallery items with actual photos

### Adding Real Images
To add real images to the gallery:
1. Replace the `.gallery-placeholder` divs with `<img>` tags
2. Add your image files to an `images/` folder
3. Update the CSS to style the images properly

### Contact Form
The contact form is currently set up for demonstration. To make it functional:
1. Add a backend service (PHP, Node.js, etc.)
2. Update the form action in the HTML
3. Modify the JavaScript form handler

## Browser Support

- Chrome (recommended)
- Firefox
- Safari
- Edge
- Mobile browsers (iOS Safari, Chrome Mobile)

## Performance Features

- Optimized CSS with efficient selectors
- Minimal JavaScript for fast loading
- Responsive images and layouts
- Smooth animations using CSS transforms
- Intersection Observer for performance-optimized animations

## SEO Features

- Semantic HTML structure
- Meta tags for description and viewport
- Proper heading hierarchy (H1, H2, H3)
- Alt text ready for images
- Clean URL structure

## Future Enhancements

Consider adding these features for a production website:
- Backend integration for contact forms
- Content Management System (CMS)
- Blog section for news and updates
- Online enrollment system
- Parent portal
- Payment integration
- Multi-language support

## License

This project is open source and available under the MIT License.

## Support

For questions or support, please contact the development team or refer to the documentation.

---

**Note**: This is a template website. Make sure to customize all content, images, and contact information to match your specific preschool's needs before going live.
