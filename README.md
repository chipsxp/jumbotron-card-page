# Jumbotron Card Page

A responsive Bootstrap-based web template with WordPress integration capabilities.

## Project Overview

This project provides a complete Bootstrap header design with responsive navigation menu buttons that work down to 768px width. The footer uses CSS Flex with dropdown columns for data entry forms. The template is prepared for WordPress front-page integration.

## Features

- **Responsive Header**: Navigation menu with collapsible hamburger menu for mobile devices
- **Card Components**: Three-column card layout that stacks on smaller screens
- **Jumbotron Section**: Attention-grabbing hero area with call-to-action
- **Two-Column Content**: Responsive content sections with contrasting styles
- **Interactive Footer**: Form elements and dropdown selectors in a two-column layout
- **WordPress Ready**: Prepared structure for WordPress theme integration

## Technical Implementation

### Bootstrap Framework Usage

The project leverages Bootstrap 5.0.2 for responsive design and UI components:

- Responsive grid system with appropriate breakpoints
- Navigation components with mobile-friendly collapsing
- Card components for content organization
- Form styling and validation
- Button variants for different UI needs
- Utility classes for spacing, colors, and typography

### Responsive Design Approach

The template follows a mobile-first approach with:

- Viewport meta tag for proper mobile scaling
- Responsive breakpoints (focusing on 768px as a key breakpoint)
- Column classes that adapt to screen size (`col-12 col-md-4`, etc.)
- Flexible media with appropriate scaling
- Responsive typography using relative units
- Collapsible navigation for smaller screens

### Project Structure

- `index.html` - Main standalone HTML template
- `wpsetup/index.php` - WordPress-ready version
- `style.css` - Custom styling for the standalone version
- `wpsetup/style.css` - WordPress theme styling with theme metadata

## Getting Started

1. Clone this repository
2. Open `index.html` in your browser to view the standalone version
3. For WordPress integration, copy the contents of the `wpsetup` folder to your WordPress themes directory

## Browser Compatibility

Tested and working on:
- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Android Chrome)

## License

This project is licensed under the GNU General Public License v3 - see the LICENSE file for details.
