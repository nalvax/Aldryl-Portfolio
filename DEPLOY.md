# Deploy on GitHub Pages

1. Open [repository Settings → Pages](https://github.com/nalvax/Aldryl-Portfolio/settings/pages).
2. Under **Build and deployment**, set **Source** to **GitHub Actions**.
3. Open [Actions](https://github.com/nalvax/Aldryl-Portfolio/actions) and run **Deploy portfolio to GitHub Pages** if it has not already run.
4. When the workflow completes, visit https://nalvax.github.io/Aldryl-Portfolio/.

The deployed website is plain HTML/CSS/JS; it does not need Vite, npm or a lockfile. GitHub Actions uploads the repository root as its Pages artifact. Set Pages source to GitHub Actions, not Deploy from a branch.

## Alternatives
For Netlify or Vercel, choose a static site without a build command, publish root `.` (or copy site files to a publish directory).

## Content
Before academic submission, replace all TODO placeholders and upload the course artifacts named in README.md.
