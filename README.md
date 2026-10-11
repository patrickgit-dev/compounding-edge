# The Compounding Edge

An open-ended daily small-actions planner that runs entirely in the browser.
No build step, no server, no dependencies: it is a single `index.html` file.

## Features
- Profile creation required before first use
- Daily page: top 3 priorities, small actions, energy, win, friction, tomorrow's first move
- Weekly review, monthly habit tracker, checkpoint reviews, setup (vision, goals, actions, obstacles, commitment)
- Day and week counts from your start date, with no end date
- Entries are saved in your browser (localStorage) on your device only
- Export and import a JSON backup from the Setup tab

## Run locally
Open `index.html` in any modern browser.

## Host with GitHub Pages
1. Put `index.html` (and this README) in the root of a public repository.
2. In the repository, go to Settings, then Pages.
3. Under "Build and deployment", choose "Deploy from a branch", pick `main` and `/ (root)`, then Save.
4. After a minute or two the site is live at `https://<your-username>.github.io/<repository-name>/`.

## Notes
- Data does not sync between devices. Use Export backup and Import backup to move it.
- The Think Labs logo is embedded in the page. Only publish it if you have the right to use it.
