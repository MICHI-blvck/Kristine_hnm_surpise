# Happy New Month

A static website built with HTML, CSS, and JavaScript. There is no build step or package installation.

## Publish with GitHub Pages

1. Create a GitHub repository and push this project to its `main` branch.
2. In the repository, open **Settings > Pages** and set the source to **GitHub Actions**.
3. The workflow in `.github/workflows/deploy-pages.yml` publishes the site whenever you push to `main`. You can also start it from the repository's **Actions** tab.
4. After the workflow finishes, open **Settings > Pages** to find the published site URL.

Keep `index.html`, `style.css`, `script.js`, `images/`, and `audio/` together at the repository root. The links in the site are relative, so they work at a GitHub Pages project URL.

To push this folder from a terminal, replace `YOUR-USERNAME/YOUR-REPOSITORY` with your repository name:

```sh
git init
git add .
git commit -m "Prepare site for GitHub Pages"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/YOUR-REPOSITORY.git
git push -u origin main
```

Before publishing publicly, make sure you have permission to share the personal photos and music in this project. Replace any media you do not have distribution rights for.