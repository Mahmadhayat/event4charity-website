# Project Structure

## Root Directory
```
/
├── index.html          # Main application file with all content
├── styles.css          # Global styles and component styles
├── package.json        # Minimal package configuration
├── assets/             # Static assets (images, graphics)
└── components/         # Modular HTML components
```

## Component Architecture
The `/components` directory contains reusable HTML sections:
- `header.html` - Navigation and branding
- `hero.html` - Main hero section
- `features.html` - Feature grid section
- `case-studies.html` - Customer testimonials
- `pricing.html` - Pricing tiers
- `contact-form.html` - Lead generation form
- `footer.html` - Site footer with links
- `cta-section.html` - Call-to-action sections
- `donations.html` - Donations feature section
- `fundraising-platform.html` - Platform features
- `mass-participation.html` - Event partnership section
- `client-logos.html` - Customer logo grid

## Asset Organization
All visual assets are stored in `/assets`:
- Hero and section background images
- Feature illustrations
- Client logos and case study images
- Contact form and donation illustrations

## Styling Structure
Single `styles.css` file organized by:
1. CSS Custom Properties (design tokens)
2. Base styles and typography
3. Component-specific styles (matching HTML sections)
4. Responsive breakpoints
5. Utility classes and animations

## Development Patterns
- **Single File Application**: All content compiled into `index.html`
- **Component Inclusion**: Components can be referenced but main file contains all content
- **CSS Scoping**: Use component-specific class prefixes (e.g., `.hero-`, `.footer-`)
- **Asset References**: Relative paths from root (e.g., `assets/hero-image.jpg`)
- **ID Strategy**: Use IDs for navigation anchors and JavaScript targets

## File Naming Conventions
- **HTML**: Kebab-case for component files (`case-studies.html`)
- **CSS Classes**: BEM-inspired naming (`.component-element--modifier`)
- **Assets**: Descriptive names with hyphens (`hero-image.jpg`)
- **JavaScript**: camelCase for variables and functions

## Content Organization
The main `index.html` follows this section order:
1. Header/Navigation
2. Hero Section
3. Features Overview
4. Mass Participation
5. Fundraising Platform
6. Client Logos
7. Call-to-Action
8. Case Studies
9. Donations Section
10. Pricing
11. Contact Form
12. Footer