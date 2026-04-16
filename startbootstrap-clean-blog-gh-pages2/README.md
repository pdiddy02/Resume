# Payton Webley Portfolio Website

This is a static HTML portfolio site with pages for Home, Education, Experience, Skills, Contact, and a single-page web app (`webapp.html`).

## Publish on GitHub Pages

1. Create a new GitHub repository and push this folder to it.
   - If you already have Git installed locally, run:
     ```bash
     git init
     git add .
     git commit -m "Initial site commit"
     git branch -M main
     git remote add origin <your-github-repo-url>
     git push -u origin main
     ```

2. In the repository settings, enable GitHub Pages:
   - Go to `Settings` > `Pages`
   - Select the `main` branch and `/ (root)` folder
   - Save

3. Your site will usually be available at:
   - `https://<your-github-username>.github.io/<repository-name>/`

## Notes

- The site is already structured for static hosting.
- The `.nojekyll` file is included so GitHub Pages serves files like `webapp.html` and any non-standard assets.
- `index.html` is the home page entrypoint.

## Direct links

- Home: `index.html`
- Education: `education.html`
- Experience: `experience.html`
- Skills: `skills.html`
- Contact: `contact.html`
- Resume scratch page: `resume.html`
- Web app: `webapp.html`
