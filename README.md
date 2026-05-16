# Academic Homepage

This is a lightweight static academic homepage inspired by the structure of <https://zyy0530.github.io/>. It does not require Node, Jekyll, or a build step.

## Files

- `index.html`: homepage content and SEO metadata.
- `assets/css/styles.css`: responsive layout, typography, light/dark themes.
- `assets/js/main.js`: theme toggle, icon rendering, active navigation state.
- `assets/images/avatar-placeholder.svg`: replace this with your own portrait when ready.

## Customize

Edit `index.html` and update the remaining placeholders:

- `Your University`
- `your.email@example.com`
- education records
- research interests
- publications
- projects
- experience
- honors and awards

For a real portrait, add your image to `assets/images/`, then update the `<img>` path in `index.html`.

## Preview Locally

```bash
python3 -m http.server 8000
```

Then open:

```text
http://localhost:8000/
```

## Deploy to GitHub Pages

The closest deployment to the reference site is a GitHub Pages user site.

1. Create a GitHub repository named `<your-github-username>.github.io`.
2. From this directory, run:

   ```bash
   git remote add origin git@github.com:<your-github-username>/<your-github-username>.github.io.git
   git push -u origin main
   ```

3. Visit:

   ```text
   https://<your-github-username>.github.io/
   ```

If you use an existing repository instead, enable GitHub Pages in repository settings and set the source to `main` branch, root directory.
