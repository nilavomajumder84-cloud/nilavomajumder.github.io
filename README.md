# Nilavo's Jekyll Portfolio

A personal portfolio built with Jekyll and GitHub Pages.

## Before publishing

1. Create a GitHub repository named `YOUR_GITHUB_USERNAME.github.io`.
2. Replace `YOUR_GITHUB_USERNAME` in `_config.yml` with your GitHub username.
3. Replace the placeholder GitHub and LinkedIn links in `contact.md`.
4. Update the project placeholders in `projects.md` with your real projects.

## Run locally

Install Ruby, Bundler, and the dependencies, then run:

```bash
bundle install
bundle exec jekyll serve
```

Open `http://localhost:4000` in your browser.

## Publish with GitHub Pages

1. Push all files to the `main` branch of `YOUR_GITHUB_USERNAME.github.io`.
2. Open the repository's **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select branch `main` and folder `/ (root)`, then save.
5. Wait for the deployment to finish. Your site should appear at
   `https://YOUR_GITHUB_USERNAME.github.io`.

This repository uses the GitHub Pages gem and the supported Minima theme.
