# Project 95 — web app

Static front-end for Collo's Project 95 tracker, served by GitHub Pages so it
runs without Google's "created by a Google Apps Script user" banner.

**Generated file — do not edit here.** The source of truth is `Index.html` in the
private `project95` repo; run `python3 build-web.py` there and re-deploy.

It stores no secrets: the access code is typed by the user and kept in
localStorage on their own device. Data lives in the owner's Google Sheet behind a
code-gated API.
