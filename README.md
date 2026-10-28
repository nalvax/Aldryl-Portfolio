# Aldryl Portfolio — JRU Computer Programming 1 e-portfolio

Website: https://nalvax.github.io/Aldryl-Portfolio/

This repo contains a complete mobile-friendly, framework-free static website which GitHub Pages can deploy directly (no npm install or external build service needed). **The uploaded Markdown brief identifies Roshis Rai as portfolio owner** even though the repository is named Aldryl-Portfolio. Verify ownership and replace profile text before submitting.

## Structure

- `index.html`: ten sections — Home, About, Academics, Experience, Seminars, Organizations, Awards, Other, Reflections, Contact
- `styles.css`: responsive styling, CSS theme tokens, mobile navigation and motion preferences
- `site.js`: skill groups, five projects, work timeline, three term reflection prompts, dark/light theme, mailto contact and PDF placeholders
- `.github/workflows/deploy.yml`: static GitHub Pages deploy workflow
- `DEPLOY.md`: publication steps

## Edit portfolio information

Update `index.html` for profile details, contact links, and About; `site.js` for skills, projects, experience and reflection scaffolds. Search `TODO` for items requiring real evidence.

Add actual assets at:
- `assets/portrait.jpg`
- `assets/Roshis-Rai-Resume.pdf`
- `assets/docs/cp1-compiled-works.pdf`
- `assets/docs/project-documentation.pdf`

Add a video embed URL in `site.js` (only if applicable). Missing PDFs display a placeholder and the resume link does not download until its file is supplied.

## Run locally

Open the folder with VS Code and use a local web server, such as `python3 -m http.server 8000`, then visit http://localhost:8000. (The PDF availability check uses fetch and works more reliably from HTTP rather than file://.)

## Submission TODO checklist

1. Confirm identity, program/year, and JRU course with the actual portfolio owner.
2. Upload compiled course works and available documentation, resume, and portrait.
3. Verify work and project details before representing them as personal accomplishments.
4. Fill seminar, organization, award, and JRU-experience placeholders.
5. Replace each term's first-person narrative scaffold with actual experiences and check the syllabus topics.
6. Add video project presentation when applicable.
7. Test with an actual browser on desktop/mobile and check Lighthouse metrics.

The original provided React/Vite project is **not** what was published here: this repository uses the static HTML/CSS/JavaScript option permitted by the supplied course instructions, because it is reliable on GitHub Pages with no dependencies.
