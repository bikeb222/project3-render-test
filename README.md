# Project 3 Render Test Site

This is a minimal static website for testing a Render deployment.

## Local preview

Open `public/index.html` in a browser, or run a tiny local server:

```powershell
python -m http.server 4173 -d public
```

Then visit `http://localhost:4173`.

## Render deployment

This repository includes `render.yaml` for a Render Blueprint static site.

1. Push this folder to GitHub, GitLab, or Bitbucket.
2. In Render, choose **New > Blueprint** and connect the repo.
3. Render will create a static site named `project3-render-test`.

You can also choose **New > Static Site** manually and use:

- Build Command: `echo "No build needed for this static test site"`
- Publish Directory: `public`
