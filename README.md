# 328T628T-starter-repo

A basic template repo to start from when developing visuals and interactives for the modern web.

## Quick start (local)

1. Install Node (recommended LTS >=16).
2. Install dependencies and run the dev server:

```bash
npm install
npm run dev
```

Open the forwarded URL shown by Vite (usually `http://localhost:5173`).

## Build / Preview

Build a production bundle and preview it locally:

```bash
npm run build
npm run preview
```

## Student Setup (Fork + GitHub Pages)

Use this checklist to publish your project from your own fork.

### 1. Fork this repo

Click Fork (top-right on GitHub).

Create your own copy under your GitHub account.

### 2. Clone and run locally

### 3. Enable GitHub Pages in your fork

Open your fork on GitHub.

Go to Settings -> Pages.

Under Build and deployment, set Source to GitHub Actions.

### 4. Trigger deployment

Commit and push to main:

Go to the Actions tab and wait for Deploy to GitHub Pages to complete.

### 5. Find your live site

Return to Settings -> Pages.

Copy the published URL (usually https://<your-username>.github.io/<your-fork-repo>/).

### 6. Submit for review

Share both:

- Your fork URL
- Your live GitHub Pages URL

### Common issues

**404 / missing JS or CSS:** wait 1-2 minutes and hard refresh.
**No deployment running:** confirm Pages source is set to GitHub Actions.
**Action failed:** open Actions -> Deploy to GitHub Pages and read the failed step log.

### Other notes

Update your site after changes
Every push to main automatically rebuilds and redeploys your Pages site.
