# Listo Labs Website

A simple static homepage for [Listo Labs](https://github.com/listolabs) — showcasing doku, Morphle, and Sixtee.

## Local preview

Open `index.html` in a browser, or run a local server:

```bash
python3 -m http.server 8080
```

Then visit [http://localhost:8080](http://localhost:8080).

## Deploy to GitHub Pages

1. Create a new GitHub repository (e.g. `listo-website` or `listolabs.github.io` for a user site).
2. Push this folder to the repo.
3. In the repo, go to **Settings → Pages**.
4. Under **Build and deployment**, set **Source** to **Deploy from a branch**.
5. Choose the `main` branch and `/ (root)` folder, then save.
6. After a minute or two, your site will be live at:
   - `https://<username>.github.io/<repo-name>/` (project site), or
   - `https://<username>.github.io/` (if the repo is named `<username>.github.io`).

No build step required — this is plain HTML and CSS.

## Structure

```
index.html          Home page with product showcase
terms.html          Terms of Use
privacy.html        Privacy Policy
contact.html        Contact
support.html        Support
css/styles.css      Shared styles
assets/             Logos and app icons
```

## Products

| App     | Website                    |
|---------|----------------------------|
| doku    | https://www.hellodoku.com  |
| Morphle | https://www.playmorphle.com |
| Sixtee  | https://www.playsixtee.com |
