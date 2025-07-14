# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a personal portfolio website for Mathew Selvi, a full stack web developer and MERN stack expert. The site is built using pure HTML, CSS, and JavaScript without any build tools or frameworks. It's hosted on GitHub Pages and showcases his web development projects, MERN stack expertise, and technical skills.

## Site Structure

The website consists of three main pages:

- **index.html** - Main homepage with hero section, about, skills, and services focused on web development
- **work.html** - Portfolio page displaying MERN stack projects and web development applications
- **resume.html** - Professional resume page with web development experience, education, and technical skills

## Common Development Commands

Since this is a static website with no build system, development is straightforward:

1. **Local Development**: Open HTML files directly in a browser or use a local server
2. **Testing**: Test manually in multiple browsers and devices
3. **Deployment**: Push to GitHub - the site auto-deploys via GitHub Pages

## Code Architecture

### CSS Structure
- **CSS Variables**: All colors, fonts, and spacing are defined in `:root` for consistency
- **Mobile-First Approach**: Base styles target mobile, with responsive breakpoints for larger screens
- **Component-Based Styling**: Each section (hero, about, services, etc.) has its own CSS block
- **Consistent Naming**: Uses semantic class names like `.hero`, `.about`, `.portfolio-item`

### JavaScript Features
- **Mobile Navigation**: Hamburger menu with overlay for mobile devices
- **Smooth Scrolling**: Custom smooth scrolling implementation for anchor links
- **Animations**: Intersection Observer for skill bars and counters
- **Interactive Elements**: Typing animation, portfolio filtering, and scroll effects

### Responsive Design
- **Mobile-First**: 320px+ base styles
- **Tablet**: 576px+ breakpoint
- **Desktop**: 768px+ and 992px+ breakpoints
- **Large Screens**: 1200px+ optimization

## Key Design Patterns

1. **Color Scheme**: Gold primary (#FFD700) with dark text (#222222) and light backgrounds
2. **Typography**: Poppins for body text, Montserrat for headings
3. **Hover Effects**: Consistent transform and shadow effects throughout
4. **Grid Layouts**: CSS Grid for portfolio items and responsive sections
5. **Animation Timing**: Staggered animations using CSS custom properties
6. **Tech Stack Colors**: Different skill bars use technology-specific colors (React blue, Node green, etc.)

## Content Management

### Images
- Profile photos and project images are stored in the root directory
- Use descriptive filenames (e.g., `mathew.jpg`, `greenpeak.jpg`)
- Optimize images for web before adding them

### Portfolio Projects
- MERN stack projects showcase full-stack applications
- Frontend projects demonstrate modern web development skills
- Each project has consistent metadata: title, category, description, and link
- Projects are categorized by technology stack (MERN, frontend, fullstack)
- Single unified portfolio section for better user experience

### Contact Information
- Email: mathewselvi29@gmail.com
- Phone: +91 9633035175
- Location: Adimali, Idukki
- Social media links are consistent across all pages

## Testing and Quality Assurance

When making changes:
1. Test on mobile devices (responsive design is crucial)
2. Verify all external links work correctly
3. Check smooth scrolling and animations
4. Ensure portfolio filtering works properly with MERN/frontend/fullstack categories
5. Test mobile menu functionality
6. Verify skill bars animate correctly with technology-specific colors
7. Check that all web development content is accurate and up-to-date

## Deployment

The site is automatically deployed through GitHub Pages. Any push to the main branch will trigger a deployment. No build process is required since it's a static site.

## Performance Considerations

- Images should be optimized for web
- External resources (fonts, Font Awesome) are loaded from CDN
- CSS and JavaScript are inlined for faster loading
- Critical CSS is loaded first, with animations triggered on viewport entry
- Skill bars use technology-specific colors for better visual hierarchy
- Portfolio filtering works seamlessly with MERN stack categorization