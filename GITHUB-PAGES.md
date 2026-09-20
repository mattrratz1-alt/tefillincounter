# Host TefillinCounter on GitHub Pages

The site files are in the `docs/` folder (ready for GitHub Pages).

## 1. Create a GitHub repo

1. Go to https://github.com/new
2. Name it e.g. `tefillin-counter`
3. Public
4. **Don’t** add a README (this project already has files)

## 2. Push this project

In Terminal:

```bash
cd ~/Desktop/TefillinCounter
git add docs Shared TefillinCounter TefillinCounterWidget TefillinCounter.xcodeproj README.md .gitignore
git commit -m "Add TefillinCounter app and GitHub Pages site"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/tefillin-counter.git
git push -u origin main
```

(Replace `YOUR_USERNAME`.)

## 3. Turn on Pages

1. Repo → **Settings** → **Pages**
2. Source: **Deploy from a branch**
3. Branch: `main` / folder: **/docs**
4. Save

After a minute your site will be at:

`https://YOUR_USERNAME.github.io/tefillin-counter/`

## 4. Add to iPhone Home Screen

1. Open that URL in **Safari** on the XR  
2. Share → **Add to Home Screen**  
3. Name it **TefillinCounter**

It opens full-screen like an app (PWA). Works offline after the first visit.
