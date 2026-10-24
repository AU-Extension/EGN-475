# EGN 475 Software Prototyping: course interactives

Interactive simulations for EGN 475 at Atlantis University, School of Information Technology. Each week has two self-contained HTML pages: an explorer (Interactive A) and a scored challenge (Interactive B). The Moodle description blocks link to these pages through GitHub Pages.

Live site: https://au-extension.github.io/EGN-475/

## Structure

| Folder | Topic | Interactive A | Interactive B |
|---|---|---|---|
| week1 | Prototyping and the AI-assisted workflow | prototype-fidelity-explorer.html | prompt-quality-challenge.html |
| week2 | Requirements and wireframes | user-story-builder.html | wireframe-match-challenge.html |
| week3 | Flask pages and templates | flask-request-lifecycle.html | route-matcher-challenge.html |
| week4 | Adding data with SQLite (prototype v0.1) | crud-sql-playground.html | data-model-challenge.html |
| week5 | Forms, editing, and iteration | prg-form-flow.html | ai-code-bug-hunt.html |
| week6 | Login and polish | session-login-visualizer.html | usability-heuristics-challenge.html |
| week7 | Testing and debugging with AI | test-runner-simulator.html | traceback-debug-challenge.html |
| week8 | Ship and present (final project) | deployment-pipeline-explorer.html | demo-day-readiness.html |

## Publishing

1. Upload the contents of this folder to the `main` branch of `AU-Extension/EGN-475` (keep the `week1` to `week8` folders at the root).
2. In the repository, open Settings, then Pages, and set Source to "Deploy from a branch", branch `main`, folder `/ (root)`.
3. Each page is then live at `https://au-extension.github.io/EGN-475/weekN/<file>.html`.

Every page loads the AU logo from `AU-Extension/items` and GSAP and fonts from public CDNs, and still works if GSAP fails to load. No build step is needed.
