# GridQuest

A classroom-friendly location game for exploring optimization on a `50x50` grid.

## Publish On GitHub Pages

1. In GitHub, create a new public repository.
2. In this folder, run:

```bash
git init
git add index.html README.md .gitignore
git commit -m "Initial GridQuest app"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/YOUR-REPO.git
git push -u origin main
```

3. In the GitHub repo, go to `Settings` -> `Pages`.
4. Under `Build and deployment`, choose:
   `Source: Deploy from a branch`
5. Choose:
   `Branch: main`
   `Folder: / (root)`
6. Save.

Your site will appear at:

`https://YOUR-USERNAME.github.io/YOUR-REPO/`

## Notes

- The app is fully self-contained in `index.html`.
- No build step is required.
- The ignored `node_modules` and `package*.json` files were only for local testing and are not needed for deployment.
