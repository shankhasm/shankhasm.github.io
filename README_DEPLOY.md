# Deploying this GitHub Pages site

1. Copy `index.html` into the root of your `shankhasm.github.io` repository.
2. Copy the full `assets/` folder into the same repository root.
3. Commit and push:

```bash
git add index.html assets/headshot.jpg
git commit -m "Update personal academic website"
git push
```

4. Visit `https://shankhasm.github.io` after GitHub Pages finishes rebuilding.

The CV button currently points to the Google Drive link you provided. If you later add a local `cv.pdf` to the repository, update the CV link in `index.html` from the Google Drive URL to `cv.pdf`.
