# Overview

This project is a static bento grid landing page showcasing an AI-powered social media management tool. The page uses a modern, responsive grid layout to present key features like AI content creation, scheduling, multi-platform management, and audience growth analytics. The design emphasizes visual hierarchy through a card-based layout with strategic use of color accents and typography.

# User Preferences

Preferred communication style: Simple, everyday language.

# System Architecture

## Frontend Architecture
The project follows a simple static website architecture with semantic HTML5 structure and modern CSS Grid layout:

- **Layout Pattern**: CSS Grid-based bento grid layout using grid-template-areas for precise card positioning
- **Responsive Design**: Mobile-first approach with flexible grid columns and gap spacing
- **Component Structure**: Modular card-based components with consistent styling patterns
- **Typography System**: Inter font family with Google Fonts integration for consistent cross-platform rendering

## Styling Approach
The CSS architecture uses a systematic approach to maintainability:

- **CSS Custom Properties**: Centralized color palette and spacing variables for consistent theming
- **Color System**: Carefully designed palette with primary, secondary, accent, and contextual colors
- **Grid Layout**: 4-column responsive grid with named grid areas for semantic positioning
- **Modern CSS**: Utilizes CSS Grid, custom properties, and modern selectors for clean, maintainable code

## Design Patterns
The project implements several key design patterns:

- **Bento Grid Layout**: Popular modern web design pattern for showcasing multiple features in a visually appealing grid
- **Card-Based UI**: Each feature is contained within its own card component for clear separation and hierarchy
- **Progressive Enhancement**: Graceful degradation with semantic HTML as the foundation
- **Performance Optimization**: Strategic font loading with preconnect and display=swap for improved loading performance

# External Dependencies

## Third-Party Services
- **Google Fonts**: Inter font family loaded via Google Fonts CDN with preconnect optimization
- **Font Licensing**: Includes DM Sans font files with SIL Open Font License for potential alternative typography

## Asset Management
- **Static Assets**: Self-hosted images and icons stored in assets directory
- **Favicon**: Custom 32x32 PNG favicon for brand identity
- **Illustrations**: WebP format images for optimized loading and modern browser support

## Development Dependencies
- **Frontend Mentor**: Original design challenge source for the bento grid layout concept
- **No Build Process**: Pure HTML/CSS implementation without compilation or bundling requirements
