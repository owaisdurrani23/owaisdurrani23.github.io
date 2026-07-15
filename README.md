# Publishing this site (free, via GitHub Pages)

1. Go to https://github.com/new and create a repository named exactly:
   `owaisdurrani23.github.io`
   (Must match your GitHub username exactly, all lowercase.)
   Leave it public, don't add a README (you already have one).

2. Upload these files into that repository:
   - Either drag-and-drop all files/folders in this project directly into
     the GitHub web UI ("Add file" → "Upload files"), keeping the folder
     structure intact (`assets/css/...`, `assets/js/...`, `assets/img/...`).
   - Or, if you're comfortable with git:
     ```
     git init
     git add .
     git commit -m "Initial site"
     git branch -M main
     git remote add origin https://github.com/owaisdurrani23/owaisdurrani23.github.io.git
     git push -u origin main
     ```

3. In the repository, go to Settings → Pages. Under "Build and deployment",
   set Source to "Deploy from a branch", branch `main`, folder `/ (root)`.
   Save.

4. Wait 1–2 minutes. Your site will be live at:
   https://owaisdurrani23.github.io

## Updating content later
- Publications: edit `research.html`
- Bio/experience/education: edit `about.html`
- Contact links: edit `contact.html`
- Colors/fonts: edit `assets/css/style.css` (all variables are at the top)
