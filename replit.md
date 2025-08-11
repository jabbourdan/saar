# Overview

This is a professional Hebrew website for Saar Brenner, a certified public accountant (CPA), offering accounting services. The site is built as a single-page application with a modern, responsive design featuring smooth scrolling navigation, mobile-friendly layout, and Hebrew RTL (right-to-left) text support. The website showcases professional accounting services through multiple sections including hero, about, services, gallery, hours, and contact information.

# User Preferences

Preferred communication style: Simple, everyday language.

# System Architecture

## Frontend Architecture
The application follows a traditional client-side architecture using vanilla HTML5, CSS3, and JavaScript:

**HTML Structure**: Single-page application with semantic HTML5 sections organized as a landing page
- Navigation bar with smooth scroll links
- Hero section with call-to-action buttons and statistics
- Multiple content sections (about, services, gallery, hours, contact)

**CSS Architecture**: Modern CSS with CSS custom properties (variables) for consistent theming
- Responsive design using flexible layouts
- CSS Grid and Flexbox for component layouts
- CSS custom properties for color scheme and spacing consistency
- Mobile-first responsive design approach

**JavaScript Functionality**: Vanilla JavaScript for interactive features
- Mobile navigation toggle
- Smooth scrolling navigation
- Scroll-based navbar styling changes
- Animation triggers and scroll effects

## Styling and Visual Design
**Design System**: Professional business theme with carefully chosen color palette
- Primary colors: Dark blue-gray (#2c3e50) and light blue (#3498db)
- CSS gradients for visual appeal
- Consistent spacing and typography scale
- Box shadows for depth and visual hierarchy

**Responsive Design**: Mobile-first approach with breakpoints
- Flexible grid systems
- Adaptive navigation (hamburger menu on mobile)
- Scalable typography and spacing

**RTL Support**: Full Hebrew language support with right-to-left text direction
- Proper text alignment and layout flow
- RTL-aware navigation and component positioning

## Interactive Features
**Navigation System**: Fixed header with smooth scrolling
- Mobile hamburger menu with slide animation
- Active state management for navigation links
- Scroll-triggered navbar background changes

**User Experience Enhancements**: Smooth transitions and animations
- CSS transitions for hover effects
- JavaScript-driven scroll animations
- Progressive disclosure of content sections

# External Dependencies

## Third-Party Libraries
**Font Awesome 6.4.0**: Icon library for visual elements
- Calculator icon for branding
- User interface icons throughout the site
- CDN delivery for optimal performance

**Google Fonts**: Heebo font family for Hebrew typography
- Multiple font weights (300, 400, 500, 600, 700)
- Optimized for Hebrew text rendering
- Web font optimization with display=swap

## Browser APIs
**Vanilla JavaScript APIs**: No framework dependencies
- DOM manipulation for interactive features
- Scroll event handling
- CSS class management for state changes
- Smooth scroll behavior implementation

The architecture prioritizes performance, accessibility, and maintainability while providing a professional presentation for the accounting services business.