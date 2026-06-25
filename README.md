# 姚伟 Wei Yao Academic Homepage

This is a static GitHub Pages site for `https://YYYauW.github.io/academic.github.io/`.

## Local Preview

Open `index.html` directly in a browser, or run:

```powershell
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## Publish to GitHub Pages

1. Use the public GitHub repository named `academic.github.io`.
2. Add it as the remote:

```powershell
git remote add origin https://github.com/YYYauW/academic.github.io.git
```

3. Commit and push:

```powershell
git add .
git commit -m "Create academic homepage"
git branch -M main
git push -u origin main
```

4. In GitHub, open `Settings -> Pages` and set the source to the `main` branch.
5. Visit `https://YYYauW.github.io/academic.github.io/` after GitHub Pages finishes deploying.

## Edit Next

- Replace the email placeholder in `index.html`.
- Add your portrait to `assets/` and update the hero or contact section if desired.
- Add more posts under `posts/`.
- Add Google Scholar, ORCID, or CV links when ready.

## Source Notes

The initial profile structure and publication list were drafted from publicly visible information on ResearchGate:

https://www.researchgate.net/profile/Wei-Yao-58
