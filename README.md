# Raj Panchal — Personal Portfolio Website

A personal portfolio website showcasing my background, skills, projects, certifications, and professional experience. Published live via GitHub Pages.

## Live Site

**https://rajpanchal0101.github.io**

## Tech Stack

- **HTML5** — page structure and content
- **CSS3** — styling and layout
- **JavaScript** — navigation and interactivity (portfolio page)
- **Font Awesome** — icons
- **Google Fonts** — typography

## Project Structure

```
├── index.html          # Main landing/portal page
├── resume.html         # Detailed resume page with badges and credentials
├── css/
│   └── master.css      # Global stylesheet
├── images/             # Banner and background images
├── website/
│   ├── index.html      # Full portfolio page (summary, skills, projects, experience)
│   ├── master.css      # Portfolio-specific styles
│   └── script.js       # Navigation and UI interactions
└── favicon.ico
```

## Running Locally

No build step is required — just open the HTML files in a browser.

```bash
# Clone the repository
git clone https://github.com/rajpanchal0101/rajpanchal0101.github.io.git
cd rajpanchal0101.github.io

# Open in your default browser
open index.html        # macOS
xdg-open index.html    # Linux
start index.html       # Windows
```

Or use any local server, for example:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000` in your browser.

## Deployment

This site is deployed automatically via [GitHub Pages](https://pages.github.com/). Any push to the `master` branch updates the live site.

## License

Copyright (c) 2024 Raj Panchal
