# Vasanth D | 3D Developer Portfolio

> A modern, animated single-page portfolio with a 3D background, built by an MCA student and full stack / AI developer. Originally started for the CodeAlpha internship and now updated with new projects, a 3D redesign and a dark/light theme.

## Features

- **3D Animated Background**: Three.js wireframe shapes and particles that react to mouse movement and scroll
- **3D Tilt Project Cards**: Cards tilt toward the cursor with a moving glare effect
- **Interactive Profile Image**: The glowing profile ring tilts in 3D as the mouse moves
- **Magnetic Buttons**: Call-to-action buttons gently follow the cursor, with a shine sweep and glow on hover
- **Dark / Light Theme**: One-click toggle, and your choice is remembered
- **Typing Animation**: Rotating hero text describing what I build
- **Animated Skill Bars**: Progress bars fill when they scroll into view
- **Scroll Reveal Animations**: Sections fade in using Intersection Observer
- **Page Loader**: Branded loading screen on first visit
- **Responsive Layout**: Mobile-first design with a slide-in hamburger menu
- **Active Navigation**: The menu highlights the section you are viewing
- **Contact Form**: Messages are delivered by email through Formspree
- **Scroll to Top**: Floating button that appears after scrolling
- **Accessible**: Visible keyboard focus and `prefers-reduced-motion` support (the 3D scene and animations switch off)
- **No icon-font dependency**: All icons are inline SVG, so nothing breaks if a CDN is blocked

## Sections

1. **Home**: Introduction, call-to-action buttons and social links
2. **About**: Bio and quick stats
3. **Skills**: Technical skills with animated progress bars
4. **Projects**: Five featured projects with tags, live demos and GitHub links
5. **Resume**: Experience and education timeline with a resume download
6. **Contact**: Contact details and a working message form

## Featured Projects

| Project | Description | Stack |
|---------|-------------|-------|
| **Smart Payroll Management System** | Automates salaries, attendance, tax deductions and reports | Java, MySQL, Swing, JDBC |
| **ShopZone: AI Fraud Detection** | E-commerce platform with real-time fraud scoring ([live](https://www.fraudetect.site), [code](https://github.com/Vasanthh06/Fraud_Detection_System)) | FastAPI, Scikit-Learn, PostgreSQL, Resend API |
| **EduX Agent** | AI learning agent for personalised student support | AI Agent, LLMs, Python |
| **SkillGraph AI** | Maps skills and learning paths into a graph | AI, Python, Graphs |
| **FloodGuard AI** | Flood risk prediction and early warning using live weather data and a Gradient Boosting model (about 90% test accuracy) | FastAPI, Scikit-Learn, SQLAlchemy, Chart.js, Open-Meteo |

## Tech Stack

| Layer | Technology |
|-------|-----------|
| Markup | Semantic HTML5 |
| Styling | CSS3 (Grid, Flexbox, Custom Properties, Animations, Glassmorphism) |
| Scripting | Vanilla JavaScript (ES6+) |
| 3D | Three.js (r128, loaded from cdnjs) |
| Icons | Inline SVG |
| Fonts | Google Fonts (Space Grotesk + Syne) |
| Forms | Formspree |

## Project Structure

```
portfolio/
├── index.html            # The whole site (HTML, CSS and JS in one file)
├── profile.JPG           # Profile photo
├── Vasanth_D_Resume.pdf  # Resume (download button)
└── README.md
```

## How to Run

Put `index.html`, `profile.JPG` and `Vasanth_D_Resume.pdf` in the same folder, then open `index.html` in any modern browser. There is no build step.

An internet connection is needed for the 3D library, Google Fonts and the contact form.

## Customisation

**Project links**: Open `index.html`, find the `projects` array in the script and replace each `"#"` with your real URL. Entries with `"#"` show a disabled "(soon)" button.

```js
{ t:"EduX Agent", ..., live:"https://your-link", git:"https://github.com/you/repo" }
```

**Skills**: Edit the `skills` array (name, icon and percentage).

**Colours / theme**: Change the CSS variables at the top of the stylesheet (`--p`, `--s`, `--a`).

**Contact form**: Replace the Formspree URL in the `<form action="...">` with your own endpoint.

## Deployment

The site is static and ready for **GitHub Pages**, **Netlify** or **Vercel**:

1. Push the folder to a GitHub repository.
2. Enable GitHub Pages (Settings, Pages, deploy from the `main` branch), or drag the folder into Netlify.
3. Keep `index.html` at the root of the project.

## Browser Support

Latest versions of Chrome, Edge, Firefox and Safari. The 3D background needs WebGL. If it is unavailable, the rest of the site still works.

## Author

**Vasanth D**: MCA student at M.S. Ramaiah University of Applied Sciences, Bengaluru

- GitHub: [Vasanthh06](https://github.com/Vasanthh06)
- LinkedIn: [vasanthdani](https://www.linkedin.com/in/vasanthdani/)
- Email: vasanthhdani@gmail.com

## License

© 2026 Vasanth D. All rights reserved.
