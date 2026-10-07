# Ganindu Liyana Pathirana — Portfolio

A responsive personal portfolio website built with plain HTML, CSS and JavaScript.

## Files

- `index.html` — portfolio content and structure
- `style.css` — responsive styling and animations
- `script.js` — mobile navigation, reveal animations and current year
- `assets/profile.jpg` — profile photo
- `assets/Ganindu_Pathirana_CV.pdf` — CV download

## Run locally in VS Code

1. Extract the ZIP file.
2. Open the extracted `ganindu-portfolio` folder in VS Code.
3. Open `index.html` in a browser.
4. Recommended: install the **Live Server** extension in VS Code and click **Go Live**.

## Publish with GitHub Pages

### Option A — VS Code + Git terminal

Open the portfolio folder in VS Code, then run:

```bash
git init
git add .
git commit -m "Create personal portfolio"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/ganindu-portfolio.git
git push -u origin main
```

Replace `YOUR-USERNAME` with your GitHub username and create the GitHub repository first.

### Enable GitHub Pages

On GitHub:

1. Open the repository.
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, select **Deploy from a branch**.
4. Select branch **main** and folder **/ (root)**.
5. Save.
6. GitHub will provide the published website URL.

## Updating the portfolio

Edit `index.html` for text/projects, `style.css` for design, and replace `assets/profile.jpg` if you want a different profile photo. Commit and push the changes again:

```bash
git add .
git commit -m "Update portfolio"
git push
```
