# Veyra Website

A modern, responsive website for the Veyra programming language featuring a unique futuristic design with glassmorphism effects and smooth animations.

## Features

- **Fully Responsive**: Works perfectly on desktop, tablet, and mobile devices
- **Modern Design**: Dark theme with orange/blue gradient accents and glassmorphism effects
- **Interactive Elements**: Animated navigation, hover effects, and smooth scrolling
- **Complete Sections**: Hero, Features, Code Examples, Documentation, Community, and Footer
- **Veyra Branding**: Integrated logo and language-specific content
- **Performance Optimized**: Pure HTML/CSS/JS with no external dependencies

## Sections

### 🏠 Hero Section
- Animated title with glitch effect
- Call-to-action buttons
- Professional tagline

### ⚡ Features Section
- Lightning Fast performance
- Military-Grade Security
- Global Neural Network
- Advanced Analytics
- Seamless Integration
- AI/ML Ready

### 💻 Code Examples
Interactive tabbed examples showing:
- Hello World
- Web Server creation
- AI Integration
- Async Programming

### 📚 Documentation
- Getting Started guide
- Advanced Topics
- API Reference
- Installation instructions

### 👥 Community
- Discord community link
- GitHub repository
- Documentation access
- Newsletter signup

## Local Development

### Prerequisites
- Python 3.x installed

### Running the Website

1. **Clone or navigate to the project directory**
   ```bash
   cd /home/gups/Pictures/Projects/nk
   ```

2. **Start the local server**
   ```bash
   python3 serve_website.py
   ```

3. **Open your browser and visit**
   ```
   http://localhost:8000
   ```

The server will automatically serve the website from the `web/` directory and provide live reloading for development.

## File Structure

```
web/
├── index.html          # Main website file
└── 1.svg              # Veyra logo
serve_website.py       # Local development server
```

## Design Philosophy

The website embraces a futuristic aesthetic with:
- **Dark Theme**: Easy on the eyes and modern
- **Gradient Accents**: Orange (#FF5E00) and blue (#00B2FF) colors
- **Typography**: Orbitron for headings, Rajdhani for body text
- **Animations**: Subtle glows, pulses, and smooth transitions
- **Glassmorphism**: Backdrop blur effects for depth
- **Responsive Grid**: Flexible layouts that adapt to screen size

## Browser Support

- Chrome 90+
- Firefox 88+
- Safari 14+
- Edge 90+

## Contributing

To modify the website:

1. Edit `web/index.html` for content and styling
2. Test locally using `python3 serve_website.py`
3. Ensure responsive design works on mobile devices
4. Update this README if adding new features

## Deployment

The website is a single HTML file that can be deployed to any static hosting service:

- GitHub Pages
- Netlify
- Vercel
- AWS S3 + CloudFront
- Traditional web hosting

Simply upload the `web/index.html` file and the logo will be embedded.

## License

This website is part of the Veyra project and follows the same MIT license.