# Integer ALU Project Website

A modern, responsive website showcasing the Verilog Integer ALU project implementation.

## Features

- **Modern Design**: Clean, professional interface with gradient accents and smooth animations
- **Responsive Layout**: Fully responsive design that works on desktop, tablet, and mobile devices
- **Interactive Elements**: 
  - Smooth scrolling navigation
  - Tabbed waveform gallery
  - Image modal viewer for waveforms
  - Scroll-to-top button
  - Mobile hamburger menu
- **Comprehensive Content**:
  - Project overview and statistics
  - Detailed operation descriptions with opcodes
  - ALU module specifications (4-bit, 8-bit, 16-bit, 32-bit)
  - Waveform gallery organized by category
  - Team and project information

## File Structure

```
IntegerALU/
├── index.html          # Main HTML file
├── styles.css          # CSS styling
├── script.js           # JavaScript functionality
└── Step2/
    └── WaveForm ScopeShots/  # Waveform images
```

## Getting Started

### Option 1: Open Directly in Browser

Simply open `index.html` in your web browser:

```bash
# On macOS
open index.html

# On Linux
xdg-open index.html

# On Windows
start index.html
```

### Option 2: Use a Local Server (Recommended)

For the best experience, use a local web server:

#### Using Python 3:
```bash
python3 -m http.server 8000
```
Then open `http://localhost:8000` in your browser.

#### Using Python 2:
```bash
python -m SimpleHTTPServer 8000
```

#### Using Node.js (http-server):
```bash
npx http-server -p 8000
```

#### Using PHP:
```bash
php -S localhost:8000
```

## Browser Compatibility

- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Customization

### Colors

The website uses CSS custom properties (variables) defined in `styles.css`. You can customize the color scheme by modifying:

```css
:root {
    --primary-color: #6366f1;
    --secondary-color: #8b5cf6;
    --accent-color: #ec4899;
    /* ... */
}
```

### Content

- Edit `index.html` to modify text content, sections, or structure
- Update waveform images by replacing files in `Step2/WaveForm ScopeShots/`
- Modify team information in the About section

## Features Explained

### Navigation
- Fixed navigation bar that stays visible while scrolling
- Smooth scroll to sections
- Active link highlighting based on scroll position
- Mobile-responsive hamburger menu

### Hero Section
- Animated gradient text
- Project statistics display
- Parallax scrolling effect

### Operations Section
- Cards for each operation with icons and opcodes
- Hover effects and animations
- Organized by category (Logic, Arithmetic, Shift)

### ALU Modules Section
- Grid layout showcasing all four implementations
- Architecture diagram visualization
- Feature lists for each module

### Waveforms Section
- Tabbed interface for organizing waveforms
- Click images to view in fullscreen modal
- Lazy loading for performance

### About Section
- Project overview and key features
- Team member information
- Technology stack display

## Performance

- Images use lazy loading for faster initial page load
- CSS animations use GPU acceleration
- Smooth scroll behavior with requestAnimationFrame
- Optimized for modern browsers

## Deployment

To deploy this website:

1. **GitHub Pages**: 
   - Push files to a GitHub repository
   - Enable GitHub Pages in repository settings
   - Select the main branch

2. **Netlify**:
   - Drag and drop the project folder to Netlify
   - Or connect your Git repository

3. **Vercel**:
   - Install Vercel CLI: `npm i -g vercel`
   - Run `vercel` in the project directory

4. **Traditional Web Hosting**:
   - Upload all files via FTP/SFTP
   - Ensure `index.html` is in the root directory

## Notes

- All waveform images are referenced from `Step2/WaveForm ScopeShots/`
- Ensure image paths are correct relative to `index.html`
- The website uses Google Fonts (Inter) - requires internet connection
- No build process required - pure HTML/CSS/JavaScript

## License

This website is part of the Integer ALU Project for CS.3339 Computer Architecture at Texas State University.

## Contact

For questions or issues with the website, please contact the project team members.

