# Ahmad Fahed — Portfolio

My personal portfolio site, live at **https://ahmad-fahed.github.io**.

I'm a junior software developer. I build REST APIs with Java and Spring Boot, secured with JWT, tested with TDD and shipped in Docker through GitHub Actions to Azure.

## What's on the site

- **Projects** — [Hogwarts Artifacts](https://github.com/Ahmad-Fahed/hogwarts-artifacts) and [Equipify](https://github.com/Ahmad-Fahed/Equipify)
- **Skills** — backend, data, cloud & DevOps, practices and tools
- **Experience & education** — work history, my Computer Information Systems degree from the University of Jordan, certificates and languages
- **Contact** — email, LinkedIn and GitHub
- **CV** — downloadable from the header

## How it's built

A single static page, with no framework and no build step:

- `index.html` — the whole site: HTML, CSS and a small amount of vanilla JavaScript
- `AhmadFahed_CV.pdf` — my CV, linked from the Download CV button

Features include a dark/light theme toggle (saved between visits), an animated grid background, cursor-following hover effects and scroll-in animations. The animations turn off for visitors who have reduced motion enabled.

## Run it locally

Open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8000
```

Then visit http://localhost:8000.

## Deploying

The site is hosted on GitHub Pages from the `main` branch. Every push to `main` goes live within about a minute.

## Contact

- Email: ahmaddfahed@gmail.com
- LinkedIn: https://www.linkedin.com/in/ahmad-fahed
- GitHub: https://github.com/Ahmad-Fahed
