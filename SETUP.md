# SETUP GUIDE — Read this first

## Step 1: Rename the folder
Rename the `raunit-portfolio` folder to your GitHub username + `.github.io`
e.g. `raunitbudhiraja.github.io`

## Step 2: Add your images
Inside the `images/` folder, add:
- `profile.jpg` — your photo (used on the About page)
- `logo.png` — a simple logo or your initials (shown in navbar)
- `favicon.png` — small icon shown in browser tab

Create a `cv/` folder and drop in `raunit_cv.pdf`

If you don't have these yet, remove the broken references temporarily:
- In `_quarto.yml`: delete the `favicon:` and `logo:` lines
- In `about.qmd`: remove or comment out the `<img>` tag

## Step 3: Open the folder in VS Code
File > Open Folder > select raunitbudhiraja.github.io

## Step 4: Preview locally
In the VS Code terminal:
```
quarto preview
```

## Step 5: Render to /docs
```
quarto render
```

## Step 6: Add .nojekyll file
```
# Mac/Linux:
touch .nojekyll

# Windows CMD:
type nul > .nojekyll

# Windows PowerShell:
ni .nojekyll
```

## Step 7: Push to GitHub
1. Create a new repo on GitHub named exactly: `raunitbudhiraja.github.io`
2. In VS Code Source Control panel: Initialize Repository → Stage All → Commit → Publish Branch

## Step 8: Enable GitHub Pages
GitHub repo → Settings → Pages → Branch: main → Folder: /docs → Save

Your site will be live at: https://raunitbudhiraja.github.io

---

## Things to personalise before submission
- [ ] Add your real profile photo to `images/profile.jpg`
- [ ] Upload your actual CV to `cv/raunit_cv.pdf`
- [ ] Update the About page with real bio details
- [ ] Update the stats on the homepage (years studying, projects, etc.)
- [ ] Update GitHub/LinkedIn URLs in `_quarto.yml` and `contact.qmd`
- [ ] Add Kubicle certificate screenshots or confirmation dates to `about.qmd`
- [ ] Tweak project descriptions to reflect any real work you've done
- [ ] Add `.nojekyll` file before pushing
