# Lawyer Landing Page

A professional, responsive landing page for a lawyer with bilingual support (German and Bulgarian), modern design, and interactive features.

## Features

### Design & Layout
- **Color Scheme**: Professional white and navy blue design
- **Typography**: Clean, modern Inter font family
- **Responsive Design**: Optimized for all screen sizes
  - Extra Small Mobile (Portrait): 320px – 480px
  - Large Tablets (Landscape): 769px – 1024px
  - Laptops and Small Desktops: 1250px+

### Navigation
- **Fixed Navigation Bar**: Stays at the top when scrolling
- **Smooth Scrolling**: Anchor links smoothly scroll to sections
- **Working Hours Tooltip**: Hover to see office hours
- **Language Switcher**: Toggle between German (DE) and Bulgarian (BG)
- **Mobile Menu**: Hamburger menu for mobile devices

### Sections
1. **Hero Section**: Split layout with lawyer description (left) and image placeholder (right)
2. **About Section**: General information about the lawyer with credentials and statistics
3. **Practice Areas**: Six main areas of law practice with icons and descriptions
4. **Contact Section**: Contact information, contact form, and Google Maps placeholder

### Interactive Features
- **Language Switching**: Complete bilingual support with translations
- **Contact Form**: Functional form with validation and success messages
- **Animations**: Smooth scroll animations and hover effects
- **Mobile Responsive**: Fully responsive design with mobile-first approach

## File Structure

```
webproject/
├── index.html          # Main HTML structure
├── styles.css          # CSS styles and responsive design
├── script.js           # JavaScript functionality
└── README.md           # Project documentation
```

## Technologies Used

- **HTML5**: Semantic markup and structure
- **CSS3**: Modern styling with CSS Grid, Flexbox, and custom properties
- **JavaScript (ES6+)**: Interactive features and language switching
- **Google Fonts**: Inter font family for typography

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Getting Started

1. **Clone or Download**: Get the project files
2. **Open in Browser**: Simply open `index.html` in any modern web browser
3. **No Build Process**: This is a static website that doesn't require any build tools

## Customization

### Colors
The color scheme is defined using CSS custom properties in `styles.css`:

```css
:root {
    --navy-blue: #1e3a8a;
    --navy-blue-light: #3b82f6;
    --navy-blue-dark: #1e40af;
    --white: #ffffff;
    /* ... other colors */
}
```

### Content
- **Lawyer Information**: Update the content in `index.html`
- **Translations**: Modify the `translations` object in `script.js`
- **Contact Details**: Update address, phone, and email in the contact section

### Google Maps Integration
To add actual Google Maps:

1. Get a Google Maps API key
2. Replace the map placeholder in the contact section with:
```html
<iframe 
    src="https://www.google.com/maps/embed?pb=YOUR_MAP_EMBED_URL"
    width="100%" 
    height="400" 
    style="border:0;" 
    allowfullscreen="" 
    loading="lazy">
</iframe>
```

## Features in Detail

### Language Switching
- Toggle between German and Bulgarian
- All content, including form placeholders, is translated
- Language preference is maintained during the session

### Responsive Breakpoints
- **320px - 480px**: Mobile portrait layout
- **769px - 1024px**: Tablet landscape layout
- **1250px+**: Desktop layout with enhanced spacing

### Form Functionality
- Client-side validation
- Loading states during submission
- Success/error messages
- Form reset after successful submission

### Animations
- Smooth scroll animations
- Hover effects on cards and buttons
- Intersection Observer for scroll-triggered animations
- Navbar transparency effect on scroll

## Performance Optimizations

- **CSS Custom Properties**: Efficient color management
- **Intersection Observer**: Optimized scroll animations
- **Minimal JavaScript**: Lightweight and fast
- **Optimized Images**: Placeholder system for easy image integration

## Accessibility Features

- Semantic HTML structure
- Proper heading hierarchy
- Alt text for images (when added)
- Keyboard navigation support
- Screen reader friendly

## Future Enhancements

- **Real Google Maps Integration**: Add actual map functionality
- **Image Gallery**: Add lawyer photos and office images
- **Blog Section**: Add legal articles and updates
- **Testimonials**: Add client testimonials section
- **Online Booking**: Integrate appointment booking system
- **SEO Optimization**: Add meta tags and structured data

## License

This project is open source and available under the MIT License.

## Support

For questions or customization requests, please refer to the code comments or documentation within the files.

