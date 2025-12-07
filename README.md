# Portfolio Website - Arya Singh

A modern, responsive portfolio website showcasing professional details, education, skills, projects, certifications, and achievements.

## Features

- **Dark Mode Design**: Modern "it-girl" aesthetic with dark theme and pink/purple gradient accents
- **Responsive Design**: Works seamlessly on desktop, tablet, and mobile devices
- **Modern UI**: Sleek, trendy design with smooth animations and glassmorphism effects
- **Contact Information**: Direct contact details (phone and email) with clickable links
- **Smooth Scrolling**: Navigation with smooth scroll effects
- **Interactive Elements**: Hover effects, glow animations, and transitions throughout

## Project Structure

```
portfolio/
├── index.html          # Main HTML file
├── styles.css          # CSS styling file
├── script.js           # JavaScript for interactivity and form handling
└── README.md           # This file
```

## Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- A text editor (VS Code, Sublime Text, etc.)
- A local web server (optional, but recommended)

### Running the Portfolio

#### Method 1: Direct File Opening (Simple)

1. Navigate to the portfolio directory:
   ```bash
   cd portfolio
   ```

2. Open `index.html` directly in your web browser:
   - Double-click the `index.html` file, or
   - Right-click and select "Open with" → Choose your browser

**Note**: The website works perfectly when opened directly in a browser.

#### Method 2: Using a Local Web Server (Recommended)

##### Option A: Using Python (if installed)

1. Navigate to the portfolio directory:
   ```bash
   cd portfolio
   ```

2. For Python 3:
   ```bash
   python3 -m http.server 8000
   ```

3. Open your browser and visit:
   ```
   http://localhost:8000
   ```

##### Option B: Using Node.js (if installed)

1. Install a simple HTTP server globally:
   ```bash
   npm install -g http-server
   ```

2. Navigate to the portfolio directory:
   ```bash
   cd portfolio
   ```

3. Start the server:
   ```bash
   http-server -p 8000
   ```

4. Open your browser and visit:
   ```
   http://localhost:8000
   ```

##### Option C: Using VS Code Live Server Extension

1. Install the "Live Server" extension in VS Code
2. Right-click on `index.html`
3. Select "Open with Live Server"

## Design Features

The portfolio features a modern dark mode "it-girl" aesthetic with:

- **Dark Background**: Deep black (#0a0a0a) with subtle gradient overlays
- **Pink/Purple Accents**: Gradient colors (#ff6b9d, #c44569, #f093fb) for highlights
- **Glassmorphism**: Frosted glass effects on navigation and cards
- **Smooth Animations**: Fade-in effects, hover transitions, and glow effects
- **Modern Typography**: Inter font family for a clean, contemporary look
- **Interactive Cards**: Hover effects with elevation and border color changes

## Customization

### Updating Personal Information

1. Open `index.html`
2. Update the following sections with your information:
   - Hero section: Name, contact details
   - About section: Summary/description
   - Education section: Educational background
   - Skills section: Technical and soft skills
   - Projects section: Project descriptions
   - Certifications section: Certification list
   - Achievements section: Extracurricular activities

### Changing Colors

1. Open `styles.css`
2. Modify the CSS variables in the `:root` selector:
   ```css
   :root {
       --primary-color: #667eea;
       --secondary-color: #764ba2;
       /* ... other variables */
   }
   ```

### Adding New Sections

1. Add a new section in `index.html` following the existing structure
2. Add corresponding styles in `styles.css`
3. Update the navigation menu in `index.html`

## Browser Compatibility

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Technologies Used

- **HTML5**: Structure and content
- **CSS3**: Styling and responsive design
- **JavaScript**: Interactivity and form handling
- **Font Awesome**: Icons (loaded via CDN)
- **Google Apps Script**: Backend for contact form

## Troubleshooting

### Styles Not Loading

1. Ensure `styles.css` is in the same directory as `index.html`
2. Check that the file path in the HTML `<link>` tag is correct
3. Clear browser cache and reload

### JavaScript Not Working

1. Ensure `script.js` is in the same directory as `index.html`
2. Check browser console for JavaScript errors
3. Verify the script tag is included before the closing `</body>` tag

## License

This portfolio template is free to use and modify for personal and commercial projects.

## Contact

For questions or issues, please contact:
- **Email**: reacharya.nhce@gmail.com
- **Location**: Bangalore, India

---

**Note**: Remember to replace placeholder phone number (XXXXXXXXXX) with your actual contact number in the HTML file.

