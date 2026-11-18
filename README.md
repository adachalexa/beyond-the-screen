# Beyond the Screen

Five pre-production marketing rules shown on six film campaigns. SMACC Fall 2026 research, University of Connecticut.

## Publish on GitHub Pages
1. Upload every file here to the top level of the repository (no folders).
2. Settings → Pages → Source: "Deploy from a branch" → main, / (root) → Save.
3. The site goes live at https://<your-username>.github.io/<repo-name>/

## Files
- index.html: the whole site
- odyssey.jpg, barbie.jpg, sinners.jpg, obsession.jpg, aby.jpg, backrooms.jpg: film posters
- playbook-deck.pdf: the deck behind the footer button (replace with the final deck, same file name)

## Adding the team
Upload headshots at the top level (e.g. alexa.jpg). In index.html, find "const TEAM =" and replace the placeholder list with:
const TEAM = [
  {name:'Full Name', role:'Research lane', img:'alexa.jpg', li:'https://www.linkedin.com/in/...'},
  ...8 people...
];
