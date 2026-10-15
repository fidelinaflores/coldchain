# Lab website

A plain HTML site for GitHub Pages. No build tools needed.

## Put it online (about 10 minutes)

1. Create a free account at github.com.
2. Create a new **public** repository named `yourusername.github.io` (or a lab organization name, like `yourlab.github.io`).
3. Click **Add file → Upload files**, drag in everything from this folder (keep the `assets` folder), and click **Commit changes**.
4. Go to **Settings → Pages**. Under "Build and deployment", choose **Deploy from a branch**, branch `main`, folder `/ (root)`, and save.
5. After a minute or two, the site is live at `https://yourusername.github.io`.

## Edit it

- Every page is its own file: `index.html`, `research.html`, `people.html`, `publications.html`, `news.html`, `join.html`.
- You can edit any file directly on github.com by clicking it, then the pencil icon. Changes go live within a minute or two.
- Search for "Your Lab Name", "Your Name" and "university.edu" to find the placeholders.
- Photos: put images in `assets/img/`, then in `people.html` replace the initials inside `<div class="avatar">` with `<img src="assets/img/name.jpg" alt="Name">`.
- Colors and fonts are set at the top of `assets/style.css`.
- The moving background is in `assets/site.js`. Delete the `<canvas id="bg">` line in `index.html` to turn it off.

## Adding a page

1. Copy an existing page (for example `news.html`) and rename it.
2. Change the content inside `<main>`.
3. Add a link to it in the `<ul class="nav">` menu on **every** page.
