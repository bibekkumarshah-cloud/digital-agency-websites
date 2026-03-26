# Digital Solutions Agency Website

A professional, responsive website for Digital Solutions Agency featuring multiple pages with services, portfolio, and contact sections.

## Project Structure

```
digital-agency-website/
├── index.html              # Homepage with hero, about, services, portfolio, and contact sections
├── services.html           # Detailed services page with comprehensive service descriptions
├── portfolio.html          # Portfolio page with project listings and filtering
├── css/
│   └── style.css          # Main stylesheet with responsive design
├── js/
│   ├── main.js            # Main JavaScript for navigation and interactivity
│   └── portfolio.js       # Portfolio filtering functionality
├── images/                # Project images and assets
└── README.md              # This file
```

## Features

### Homepage (index.html)
- **Hero Section**: Eye-catching banner with call-to-action
- **About Section**: Team information and company overview
- **Services Section**: 6 service cards with brief descriptions and "View All Services" button
- **Portfolio Section**: 4 featured projects with "View All Projects" button
- **Contact Section**: Contact form for inquiries
- **Responsive Navigation**: Mobile-friendly hamburger menu

### Services Page (services.html)
- Detailed descriptions of all 6 services
- Service features and benefits listed
- "Why Choose Us" section with key advantages
- Call-to-action buttons for contact and portfolio

### Portfolio Page (portfolio.html)
- 8 complete project showcases with images and descriptions
- **Filter Functionality**: Filter projects by category (All, Web Design, Marketing, Branding)
- **Project Details**: Technologies used, project descriptions, and categories
- **Statistics Section**: Displays company achievements
- Responsive grid layout

## Design Features

### Responsive Design
- Mobile-first approach
- Breakpoints for tablets (768px) and mobile devices (480px)
- Hamburger menu for mobile navigation
- Flexible grid layouts

### Color Scheme
- **Primary Color**: #0066cc (Blue)
- **Secondary Color**: #ff6b35 (Orange)
- **Dark Color**: #1a1a1a (Dark Gray)
- **Light Color**: #f5f5f5 (Light Gray)

### Interactive Elements
- Smooth scroll behavior
- Hover effects on cards and buttons
- Mobile menu animation
- Scroll-triggered animations
- Portfolio filtering with smooth transitions

## Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Modern styling with flexbox and grid
- **JavaScript (Vanilla)**: No frameworks, pure JavaScript for interactivity
- **Responsive Design**: Mobile-first approach

## How to Use

1. **Open the website**: Open `index.html` in a web browser
2. **Navigate**: Use the navigation menu to move between pages
3. **Filter Portfolio**: On the portfolio page, click filter buttons to view specific project categories
4. **Contact**: Fill out the contact form to send inquiries
5. **Mobile**: Test on mobile devices or use browser dev tools to see responsive design

## File Descriptions

### index.html
Main landing page featuring all key sections and navigation to other pages.

### services.html
Comprehensive services page with detailed descriptions of each service offering.

### portfolio.html
Portfolio showcase with filtering capabilities and project details.

### css/style.css
Complete stylesheet including:
- Global styles and variables
- Typography
- Navigation styling
- Component styles (cards, buttons, forms)
- Responsive breakpoints

### js/main.js
Main JavaScript file handling:
- Mobile menu toggle
- Contact form submission
- Smooth scrolling
- Scroll animations
- Navbar effects

### js/portfolio.js
Portfolio-specific JavaScript for:
- Filter button functionality
- Dynamic content filtering
- Fade-in animations

## Customization

### Colors
Edit the CSS variables in `css/style.css`:
```css
:root {
    --primary-color: #0066cc;
    --secondary-color: #ff6b35;
    --dark-color: #1a1a1a;
    --light-color: #f5f5f5;
}
```

### Images
Replace images in the `images/` folder with your own project images.

### Content
Edit HTML files directly to update:
- Team member names and roles
- Service descriptions
- Portfolio project details
- Contact information

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Performance

- Optimized CSS with minimal bloat
- Vanilla JavaScript for fast load times
- Responsive images
- Smooth animations using CSS transitions

## Future Enhancements

- Blog section for articles and case studies
- Client testimonials section
- Team member profiles with individual pages
- Advanced portfolio filtering with search
- Newsletter subscription
- Integration with backend for form submissions

## License

© 2026 Digital Solutions Agency. All Rights Reserved.

## Contact

For inquiries, use the contact form on the website or reach out to the development team:
- Alisha Magar - Project Leader & Lead Designer
- Roji Balami - Frontend Developer
- Bibek Shah - Backend Specialist
- Ayush - Content Strategist & QA
