# Technology Stack

## Frontend Architecture
- **HTML5**: Semantic markup with modern standards
- **CSS3**: Custom CSS with CSS Grid and Flexbox for layouts
- **Vanilla JavaScript**: No framework dependencies, pure DOM manipulation
- **Google Fonts**: Inter font family for consistent typography

## Build System
- **No Build Process**: Static HTML/CSS/JS files served directly
- **No Package Manager**: Minimal dependencies approach
- **No Bundling**: Individual files loaded directly

## Development Approach
- **Component-Based**: Modular HTML components in `/components` directory
- **Single Page Application**: All content in one `index.html` file
- **Progressive Enhancement**: Works without JavaScript, enhanced with JS
- **Mobile-First**: Responsive design with mobile breakpoints

## Styling Architecture
- **CSS Custom Properties**: Extensive use of CSS variables for theming
- **BEM-like Naming**: Semantic class naming conventions
- **Component Scoping**: Styles organized by component sections
- **Design System**: Consistent color palette, spacing, and typography scales

## Asset Management
- **Local Assets**: All images stored in `/assets` directory
- **Optimized Images**: JPG format for photos, PNG for graphics
- **Icon Strategy**: Emoji icons used throughout for simplicity

## Browser Support
- **Modern Browsers**: ES6+ JavaScript features
- **Responsive Design**: Mobile-first approach with breakpoints at 768px, 1024px
- **Accessibility**: ARIA labels and semantic HTML structure

## Common Commands
Since this is a static site with no build process:
- **Development**: Open `index.html` directly in browser or use local server
- **Deployment**: Copy all files to web server
- **Testing**: Manual browser testing across devices