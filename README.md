# CryptoTrade Static Site

This is a simple static site built with `index.html` and `signin.html`.

## Publish on GitHub Pages

1. Create a GitHub repository.
2. Copy the project files into the repository root.
3. Commit and push to GitHub.

```bash
git init
git add .
git commit -m "Initial website"
git branch -M main
git remote add origin https://github.com/<your-username>/<repo-name>.git
git push -u origin main
```

4. Open the repository on GitHub and go to `Settings` > `Pages`.
5. Under `Source`, choose `main` branch and `root` folder.
6. Save.
7. GitHub will publish your site at:

```text
https://<your-username>.github.io/<repo-name>/
```

## Important notes

- The site uses relative links like `signin.html` so it works correctly on GitHub Pages.
- If your homepage is `index.html`, `https://<your-username>.github.io/<repo-name>/` will load it.
- If you want to update the site, edit the files locally, commit, and push again.

## Test locally

Open `index.html` in your browser, or use a simple local server:

```bash
# from the project folder
python -m http.server 8000
```

Then visit `http://localhost:8000`.
