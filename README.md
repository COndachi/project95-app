# Project 95 — web app

Static front-end for Collo's Project 95 tracker, served by GitHub Pages so it
runs without Google's "created by a Google Apps Script user" banner.

**This repo is the source of truth for the UI.** Edit `index.html` here and push
to `main`; GitHub Pages rebuilds in about a minute. The older flow (editing
`Index.html` in the private `project95` repo and running `build-web.py`) stopped
being used in July 2026 and that copy is stale. Do not regenerate over this file.

The server side (Apps Script `Code.js`) is deployed with clasp from the Mac
folder; the copy in the private repo is behind the live deployment.

It stores no secrets: the access code is typed by the user and kept in
localStorage on their own device. Data lives in the owner's Google Sheet behind a
code-gated API.
