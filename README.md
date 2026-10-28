# EV Atlas — Electric Vehicle Market

A responsive, single-page website for exploring the electric vehicle market through an embedded Tableau dashboard and Tableau story.

## Features

- Light, responsive design with a custom electric vehicle illustration
- Embedded Tableau Public dashboard and story
- Quick navigation between the dashboard and story
- Flux-style navigation flow in JavaScript: **Actions → Dispatcher → Store → UI**
- No Python, build step, or package installation required

## Run locally

Open `index.html` in a browser. For a local web-server preview, open this folder in Visual Studio Code and use the **Live Server** extension.

The Tableau views are hosted by Tableau Public, so an internet connection is needed to load them.

## Publish with GitHub Pages

1. Push this repository to GitHub.
2. In the repository, open **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select the `main` branch and `/(root)` folder, then save.

GitHub Pages will provide a public website URL after deployment finishes.

## Tableau views

- Dashboard: `project_evMarket1234/Dashboard1`
- Story: `project_evMarket12345/Story1`

To change either view, update its Tableau URL in the corresponding `<iframe>` in `index.html`.
