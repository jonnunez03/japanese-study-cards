# Japanese Study Cards &#40;Simple Static Version&#41;

This is the lightweight personal study site only\. It is intentionally separate from the full\-scale Japanese learning application\.

## Structure

- `index.html` — page structure only
- `css/styles.css` — visual styles
- `js/cards.js` — study\-card content
- `js/app.js` — study behavior, audio, filters, local progress, and spaced repetition

## Hosting

This site is designed for GitHub Pages\. It does not require Node, React, a backend, a database, authentication, or a build step\.

## Progress storage

Study progress is stored in the browser using `localStorage`, so it is local to that browser/device unless you use the built\-in export/import feature\.

## Updating GitHub Pages

Upload all files and folders while preserving this structure\. `index.html` must stay at the repository root\.
