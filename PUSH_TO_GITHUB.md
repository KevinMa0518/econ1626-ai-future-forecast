# Push this project to GitHub while preserving commits

This folder has been prepared as a local Git repository with meaningful commits. To preserve those commits, do **not** use GitHub drag-and-drop upload. Use Git commands:

```bash
cd econ1626-ai-future-forecast
git remote add origin https://github.com/YOUR-USERNAME/econ1626-ai-future-forecast.git
git branch -M main
git push -u origin main
```

Then enable GitHub Pages:

1. Repository → Settings → Pages
2. Source: Deploy from a branch
3. Branch: `main`, folder: `/root`
4. Save and wait for the Pages URL

Before submitting, open the Pages URL and make sure `forecast.html` loads correctly.
