# Vihaan Purohit — Personal Portfolio

A responsive personal portfolio website for **Vihaan Purohit**, a first-year B.Tech Information Technology student interested in programming, web development, artificial intelligence, and building useful digital products.

The website introduces the developer, highlights selected projects, presents current skills and learning goals, and provides a contact form.

## Features

- **Home section** — Introduction and links to projects and contact information.
- **About section** — Education, interests, and development goals.
- **Projects section** — Showcases two projects: REDOUT and Attendly, with descriptions, technology tags, and links.
- **Skills section** — Highlights HTML, CSS, Python, C, and C++.
- **Journey section** — Summarizes the developer's learning path and goals.
- **Contact section** — Provides a form that prepares a message in the visitor's default email application.
- **Responsive navigation** — Desktop navigation and a collapsible mobile menu.
- **Visual effects** — Dark theme, gradient accents, glass-style panels, hover effects, animated elements, and scroll-triggered reveals.
- **Reduced-motion support** — Respects the visitor's reduced-motion preference.

## Built With

- HTML5
- CSS3
- JavaScript
- [Tailwind CSS](https://tailwindcss.com/) via CDN
- [Lucide](https://lucide.dev/) icons via CDN
- [Google Fonts — Inter](https://fonts.google.com/specimen/Inter)

## Getting Started

### Run Locally

1. Download or clone this repository.
2. Open the project HTML file in a modern web browser.

For a cleaner repository setup, you can rename the HTML file to `index.html`.

No build step or package installation is required. An internet connection is needed to load Tailwind CSS, Lucide icons, and the Inter font from their CDNs.

## Customize the Portfolio

The main editable content is in the `portfolio` JavaScript object near the beginning of the `<body>` section.

Update the following values to personalize the site:

- `name` and `role`
- `email`
- `socials` — GitHub, LinkedIn, and Instagram URLs
- `project1` and `project2` — names, descriptions, screenshots, technologies, GitHub links, and live project URLs

Replace the placeholder project images with screenshots of your actual projects. Add valid URLs for social profiles and project links before publishing.

## Contact Form Note

The contact form uses a `mailto:` link to open the visitor's default email application. It does **not** send messages through a server or backend. Set a valid email address in `portfolio.email` for the form to work as intended.

## Deployment

This is a static website and can be hosted on GitHub Pages:

1. Upload the HTML file and this `README.md` to your repository.
2. Rename the HTML file to `index.html` if needed.
3. Open **Settings → Pages** in your GitHub repository.
4. Select the deployment branch (for example, `main`) and the root folder.
5. Save the settings and wait for GitHub Pages to publish the site.

## Project Structure

```text
portfolio/
├── index.html
└── README.md
```

If you keep the original HTML filename, replace `index.html` in the structure above with that filename.

## License

No license is specified in the project file. Add a license if you want to define how others may use, modify, or distribute this project.
