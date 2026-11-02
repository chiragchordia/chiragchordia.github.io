# Chirag Jain - Portfolio

Personal portfolio site: plain HTML, CSS and JavaScript (no build step), hosted free on GitHub Pages.

## Files

| File | What it is |
|---|---|
| `index.html` | All page content (about, resume, impact, contact). Edit text here. |
| `styles.css` | Look and feel. Colours are at the top under `:root`. |
| `script.js` | Animations, skill cards, theme switcher. Skill list, scrolling words and optional GitHub username are near the top. |
| `images/profile.jpg` | Hero photo. Replace with any square photo of the same name. |
| `Chirag_Jain_Resume.pdf` | The file behind every "Download resume" button. Replace to update. |
| `.nojekyll` | Tells GitHub Pages to serve the files as they are. Keep it. |

## Publish on GitHub Pages

1. Create a GitHub account (or sign in) at https://github.com.
2. Create a new **public** repository named exactly `YOUR-USERNAME.github.io`.
3. Upload every file and folder from this project (including `.nojekyll` and `images/`) and commit.
4. Repository **Settings → Pages**: Source = *Deploy from a branch*, Branch = `main`, folder = `/ (root)`, Save.
5. After 1–2 minutes the site is live at `https://YOUR-USERNAME.github.io`.

## Common edits

- **Add your GitHub link:** in `script.js`, set `const GITHUB_USERNAME = 'your-username';`
- **Change skills or levels:** edit the `SKILLS` list in `script.js` (levels: `Expert`, `Advanced`, `Proficient`).
- **Change the default colour theme:** edit the `--c1` / `--c2` colours at the top of `styles.css`.
- **Preview locally:** open `index.html` in your browser, or run `python3 -m http.server` in this folder and visit http://localhost:8000.

Tech logos are from Simple Icons (CC0), via react-icons (MIT). Fonts: Inter and Orbitron from Google Fonts (OFL).
