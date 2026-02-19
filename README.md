# Portfolio v2

A modern, minimalist personal portfolio website showcasing a full-stack developer's projects, skills, and experience. Built with semantic HTML, custom CSS, and a focus on clean design and user experience.

## Features

- **Responsive Design** — Fully responsive layout that adapts to desktop, tablet, and mobile devices
- **Smooth Navigation** — Fixed navbar with smooth scrolling to different sections
- **Modern Aesthetics** — Custom color scheme with handwriting fonts and subtle texture overlays
- **Section Coverage** — Hero, About, Skills, Projects, Work Experience, and Contact sections
- **Social Integration** — Direct links to GitHub, LinkedIn, and email
- **Accessibility** — Semantic HTML structure and keyboard navigation support

## Project Structure

```
.
├── index.html        # Main HTML file with all sections
├── style.css         # Complete stylesheet with responsive design
└── README.md         # This file
```

## Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- Optional: A local development server for testing (e.g., `python -m http.server`)

### Installation

1. Clone or download this repository:
   ```bash
   git clone https://github.com/atharvashirodkar/Portfolio
   cd Portfolio/v2
   ```

2. Open the website locally:
   - **Option A**: Double-click `index.html` in your file explorer
   - **Option B**: Serve using Python:
     ```bash
     python -m http.server 8000
     ```
     Then visit `http://localhost:8000` in your browser

### Usage

The website is divided into clear sections accessible via the top navigation:

- **About** — Personal introduction and background
- **Skills** — Programming languages, frameworks, and tools
- **Projects** — Showcase of completed projects
- **Work** — Professional experience and roles
- **Contact** — Direct communication links

Customize the content by editing `index.html` with your own information, and modify the styling in `style.css` to match your personal brand.

## Customization

### Updating Content

Edit `index.html` to:
- Change your name, title, and bio
- Update skill categories and technologies
- Add/modify project entries with descriptions and links
- Update contact information and social media links

### Styling

The website uses CSS custom properties (variables) for easy theming. Modify the color scheme in `style.css`:

```css
:root {
    --cream: #faf8f3;
    --paper: #f5f2ea;
    --ink: #1a1a18;
    --yellow: #fde68a;
    --blue: #bfdbfe;
    --green: #bbf7d0;
    --pink: #fecdd3;
    /* ...more colors... */
}
```

### Fonts

The design uses three font families:
- **Caveat** — Handwriting style for headers and navigation
- **Nunito** — Clean sans-serif for body text
- **Special Elite** — Typewriter style for accents

Update Google Fonts imports in `index.html` `<head>` to use different fonts.

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

All modern browsers with ES6+ support are fully compatible.

## Deployment

### GitHub Pages

1. Push your code to GitHub
2. Go to repository **Settings** → **Pages**
3. Set source to `main` branch and `/root` directory
4. Your portfolio will be live at `https://yourusername.github.io/Portfolio`

### Netlify

1. Connect your GitHub repository to Netlify
2. Set build command: (leave empty)
3. Set publish directory: `/` or `/v2`
4. Deploy

### Traditional Hosting

Upload all files to your hosting provider via FTP or file manager. Ensure the web server can serve HTML files.

## Performance Notes

- All CSS is inlined in `style.css` — no client-side build process required
- External dependencies: Font Awesome (CDN), Google Fonts (CDN) — consider self-hosting for privacy
- Lightweight with no JavaScript frameworks — fast load times
- Grain texture overlay uses SVG data URI — minimal performance impact

## Accessibility

- Semantic HTML structure (`<section>`, `<nav>`, `<h1>`-`<h6>` headings)
- Proper heading hierarchy for screen readers and auto-generated table of contents
- Color contrast follows WCAG guidelines
- Focus indicators on interactive elements

## Contributing

This is a personal portfolio project. However, if you'd like to suggest improvements or report issues:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/improvement`)
3. Make your changes
4. Commit with clear messages (`git commit -m 'Add feature'`)
5. Push to your branch (`git push origin feature/improvement`)
6. Open a Pull Request

## License

This project is provided as-is for personal and educational use. Feel free to use it as a template for your own portfolio, but please maintain attribution to the original design.

## Support & Contact

For questions or suggestions:
- **Email**: atharvashirodkar2@gmail.com
- **GitHub**: [@atharvashirodkar](https://github.com/atharvashirodkar)
- **LinkedIn**: [linkedin.com/in/atharvashirodkar](https://linkedin.com/in/atharvashirodkar)
- **Phone**: +91 8355842131

## Credits

- **Fonts**: [Google Fonts](https://fonts.google.com)
- **Icons**: [Font Awesome](https://fontawesome.com)
- **Inspiration**: Modern minimalist design practices

---

**Portfolio v2** © 2025. All rights reserved.
