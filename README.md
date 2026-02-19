# hidlayers-workshop.github.io

Hugo-based website for Hidlayers Workshop.

## Menu Structure

- Home
- Call for Papers
- Committee
- EDOC

## Project Structure

- `hugo.toml` – Hugo site config and menu definitions
- `content/` – markdown content pages
- `layouts/` – HTML templates
- `static/css/site.css` – bright theme stylesheet
- `.github/workflows/hugo.yml` – GitHub Pages deployment pipeline

## Run Locally

1. Install Hugo Extended.
2. Run:

	```bash
	hugo server -D
	```

3. Open `http://localhost:1313`.

## Deploy to GitHub Pages

This repository is configured to deploy automatically with GitHub Actions when you push to `main`.

1. In GitHub repository settings, set **Pages** source to **GitHub Actions**.
2. Push changes to `main`.
3. Wait for the workflow **Deploy Hugo site to Pages** to finish.
4. Open `https://hidlayers-workshop.github.io`.
