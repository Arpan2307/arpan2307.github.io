# Speed First RL Thesis Page

Static GitHub Pages site for **Speed First RL for 3D Reconstruction and NBV**.

## Local Preview

Open `index.html` directly in a browser, or run a tiny local server from this
folder:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Update Links

Edit the anchors in `index.html` under the `hero-actions` and `resource-list`
sections:

- Replace the GitHub URL with the final project repository.
- Replace the sample data placeholder with the Google Drive link.
- Replace the presentation placeholder with the final slides link.

## Add Videos

Put exported visualization videos here:

```text
assets/videos/nbv-policy-rollout.mp4
assets/videos/reconstruction-flythrough.mp4
```

The page already points to those paths and uses the selected-view plots as
posters.

## Host on GitHub Pages

Create a public repository named `Arpan2307.github.io`, then push this folder to
the repository root:

```bash
git init
git branch -M main
git add .
git commit -m "Add thesis project page"
git remote add origin https://github.com/Arpan2307/Arpan2307.github.io.git
git push -u origin main
```

GitHub Pages should serve it at:

```text
https://Arpan2307.github.io
```
