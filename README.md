# Autonomous-Scientific-Agents.github.io

Source for the Autonomous Scientific Agents organization website, served by GitHub Pages at
https://autonomous-scientific-agents.github.io/.

The site is a single static page (`index.html`) with no build step. Each public repository has a short
curated summary in the `REPOS` list inside `index.html`. When the page loads it refreshes star counts from
the GitHub API, and any new public repository shows up automatically with its GitHub description until a
curated summary is added.

To update a summary, edit its entry in `REPOS` and push to `main`.
