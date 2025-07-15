# Sachin Rajput Portfolio Website

## Overview

This is a complete static personal portfolio website for Sachin Rajput, a Full Stack Developer. The website showcases his professional experience, technical skills, education, and projects using authentic information from his resume. Built with vanilla HTML, CSS, and JavaScript, it features a modern design with gradient backgrounds, floating animations, and full responsive functionality.

## User Preferences

Preferred communication style: Simple, everyday language.

## System Architecture

This is a client-side only static website with no backend components or database requirements. The architecture follows a simple structure with modern styling enhancements:

- **HTML Structure**: Single-page application layout with semantic sections
- **CSS Styling**: Modern responsive design with Inter font family and Font Awesome icons
- **TailwindCSS**: Added via CDN for utility-first styling capabilities
- **JavaScript Functionality**: Interactive navigation and smooth scrolling behavior

## Key Components

### Frontend Architecture
- **Static HTML**: Single `index.html` file containing the complete page structure
- **Vanilla CSS**: Custom styling in `styles.css` with modern CSS features like backdrop-filter and smooth transitions
- **Vanilla JavaScript**: Interactive functionality in `script.js` for navigation and user experience enhancements

### Design System
- **Typography**: Inter font family from Google Fonts for clean, modern text rendering
- **Icons**: Font Awesome 6.0.0 CDN for consistent iconography
- **Color Scheme**: Blue accent color (#2563eb) with neutral grays and whites
- **Layout**: Responsive design with mobile-first approach

### Navigation System
- **Fixed Header**: Sticky navigation bar with backdrop blur effect
- **Mobile Menu**: Hamburger menu for mobile devices with toggle functionality
- **Smooth Scrolling**: JavaScript-powered smooth scrolling between sections
- **Dynamic Styling**: Navbar background changes on scroll for better visual feedback

## Data Flow

Since this is a static website, there is no traditional data flow. The interaction flow is:

1. **User Navigation**: Click events on navigation links trigger smooth scrolling to target sections
2. **Mobile Menu**: Toggle functionality for mobile navigation menu
3. **Scroll Events**: Window scroll events trigger navbar styling changes
4. **No Data Persistence**: All interactions are temporary and reset on page reload

## External Dependencies

### CDN Resources
- **Google Fonts**: Inter font family for typography
- **Font Awesome**: Version 6.0.0 for icons
- **No Framework Dependencies**: Pure vanilla JavaScript approach

### Browser APIs Used
- **DOM API**: For element selection and manipulation
- **Scroll API**: For smooth scrolling behavior and scroll event detection
- **Event API**: For handling click and scroll events

## Deployment Strategy

### Static Hosting Ready
- **No Build Process**: Direct deployment of HTML, CSS, and JS files
- **CDN Friendly**: All external resources loaded from CDN
- **Platform Agnostic**: Can be deployed on any static hosting service (Netlify, Vercel, GitHub Pages, etc.)

### Performance Considerations
- **Minimal Dependencies**: Only essential external resources loaded
- **Optimized Assets**: Compressed CSS and clean JavaScript code
- **Fast Loading**: Single-page structure with minimal HTTP requests

### Browser Compatibility
- **Modern Browser Support**: Uses modern CSS features like backdrop-filter
- **Progressive Enhancement**: Core functionality works without JavaScript
- **Responsive Design**: Mobile-first approach ensures cross-device compatibility

## Technical Decisions

### Why Vanilla JavaScript
- **Simplicity**: No framework overhead for a simple portfolio site
- **Performance**: Faster loading without bundling or compilation steps
- **Maintainability**: Easy to understand and modify for future updates

### CSS Architecture
- **Custom CSS**: Full control over styling without framework constraints
- **Modern Features**: Utilizes CSS3 features for enhanced visual effects
- **Responsive Design**: Media queries and flexible layouts for all screen sizes

### Single Page Design
- **User Experience**: Smooth navigation between sections without page reloads
- **SEO Considerations**: All content on single page for easy indexing
- **Loading Performance**: Single initial load with all content immediately available