# DE-EXTINCTION LAB — The Genome Vault

An interactive, static educational website built from the team's **Genome Project Information** and **Complete Research and Experience Blueprint** documents.

## Included
- Cinematic homepage and substantial introductory content
- Scientific Mode with seven research archives, four detailed species records, conservation case studies and source links
- Explorer Mode with four independent expeditions, evidence boards and locally saved completion badges
- Eight playable mini-games: specimen identification, word clues, DNA complementary pairing, tic-tac-toe, Snake, specimen shuffle, evidence-based proxy studio and memory matching
- Responsive layout, keyboard-friendly navigation, reduced-motion control and semantic landmarks

## Run locally
Open `index.html` in a modern browser. The website has no server-side dependencies. For more consistent testing, use VS Code Live Server or run `python -m http.server 8000` inside the folder and visit `http://localhost:8000`.

## Publish with GitHub Pages
1. Create a **public** GitHub repository named `de-extinction-lab`.
2. Upload `index.html`, `styles.css`, `app.js`, `content.js` and `.nojekyll` to the repository root (README optional).
3. Open **Settings → Pages → Build and deployment**, select **Deploy from a branch**, branch **main**, folder **/(root)**, and save.
4. Wait for GitHub Pages to finish deployment. The URL will usually be `https://YOUR-USERNAME.github.io/de-extinction-lab/`.
5. Test the live URL on desktop and mobile, and click through every research link and game.

## Editorial notes
- The fictional archive setting and arcade games are explicitly educational storytelling, not experimental biotechnology.
- Research paragraphs are adapted from the team's supplied blueprint. Sources have not all been independently checked for complete APA metadata; verify publication details and external links before academic submission.
- Some games intentionally model simplified concepts (DNA base pairing, evidence categorisation). They do not simulate full genome assembly or gene editing.
- Decorative graphics are generated in CSS; species emoji are platform-dependent illustrations, not scientifically accurate reconstructions.
- Progress is stored in the browser's localStorage, not synchronised across devices.
- Google Fonts are requested over the internet; fallback fonts are provided if unavailable.

## Recommended final QA
Check scientific claims and reference metadata, review image/illustration attribution, validate mobile touch controls, keyboard accessibility and all eight games. GitHub Pages must be enabled by the repository owner; creating these files does not automatically publish a live site.
