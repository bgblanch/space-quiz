# Cosmic Quiz

A self-contained space exploration quiz with 10 questions, keyboard-friendly answer choices, progress tracking, instant feedback, and a results screen. The interface adapts to the system light or dark theme and respects reduced-motion preferences.

## Run locally

No build tools, packages, or server are required. Open `index.html` directly in a browser.

To serve it locally instead, run Python from this directory:

```sh
python3 -m http.server 8000
```

Then visit <http://localhost:8000>.

## GitHub Pages

The `Deploy to GitHub Pages` workflow validates the static site on pull requests and deploys the repository root to GitHub Pages after changes are pushed to `main`. There is no build step.
