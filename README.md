# AGRR Gupta | Personal Portfolio

A clean, responsive personal portfolio website built with plain HTML, CSS, and JavaScript. It tells the story of my learning journey as a BCA (Artificial Intelligence) student at INVERTIS University and will grow as I build real projects.

## About this project

I’m a student learning programming, exploring artificial intelligence, and building a technical foundation. This portfolio is where I document that journey, share future projects, and connect with people in technology for internships, placements, and networking.

I don’t have finished projects yet, so the Projects section says so honestly. It is ready to showcase new work as soon as I build it.

## Features

- Responsive layout for mobile, tablet, laptop, and desktop
- Light and dark theme toggle with a saved preference
- Accessible navigation with a mobile hamburger menu, keyboard support, and visible focus states
- Sections: Home, About, Skills, Learning Journey, Projects, Contact
- Skills shown as current learning areas, with no invented ratings
- Learning timeline with clear status labels
- Reusable project-card template driven by a simple data array
- Contact form with validation that opens the visitor’s email app
- Scroll reveal animations and active navigation highlighting
- Respects the `prefers-reduced-motion` setting
- No frameworks, build tools, or external dependencies (only the Manrope font from Google Fonts)

## Tech stack

- HTML5
- CSS3 (custom properties, Grid, Flexbox)
- Vanilla JavaScript

## Project structure

```
.
├── index.html   # The whole website (HTML, CSS, and JavaScript in one file)
└── README.md
```

The website is a single file. If you downloaded it as `portfolio.html`, rename it to `index.html` before deploying.

## Run locally

1. Download or clone this repository.
2. Open `index.html` in any modern browser.

No installation is needed.

## Customize

Everything you’re likely to edit is in the `EDIT HERE` block at the top of the `<script>` section.

| What to change | Where |
| --- | --- |
| Email, GitHub, LinkedIn links | `PROFILE` object |
| Biography paragraphs | `BIO` array |
| About cards | `ABOUT` array |
| Skills and their labels | `SKILLS` array |
| Learning timeline and status labels | `JOURNEY` array |
| Projects | `PROJECTS` array |

### Add a project

Add an entry to the `PROJECTS` array:

```js
const PROJECTS = [
  {
    title: "Project name",
    description: "What it does and what I learned building it.",
    stack: ["Python", "HTML"],
    image: "screenshot.png",             // optional
    github: "https://github.com/user/repo", // optional
    demo: "https://example.com"          // optional
  }
];
```

When the array has at least one project, the “My project journey is just beginning” message and the template card are hidden automatically.

## Deploy with GitHub Pages

1. Push `index.html` to a GitHub repository.
2. Open the repository’s **Settings**, then **Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select the `main` branch and the `/ (root)` folder, then save.
5. After a minute or two, the site is live at the URL GitHub shows on that page.

Netlify and Vercel also work: drag and drop the file or connect the repository.

## Contact form note

The form has no server behind it. Submitting it opens the visitor’s email application with the message prefilled, so a message is only sent when the visitor sends that email.

## Connect with me

- Email: [agrrgupta1@gmail.com](mailto:agrrgupta1@gmail.com)
- GitHub: [agrrgupta1-png](https://github.com/agrrgupta1-png)
- LinkedIn: [AGRR Gupta](https://www.linkedin.com/in/agrr-gupta-04a910439)

---

Learning, building, and growing in technology.
