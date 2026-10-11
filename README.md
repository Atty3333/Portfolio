# PROD DAYZ | Portfolio

A static, single-page portfolio and CV for Atang Mutema (Prod Dayz). It presents profile and education information alongside software, music-production, and video-editing work.

## Sections

- **Overview** — CV/profile, skills and tools, domain areas, education, and selected projects.
- **Software** — embedded project demos and descriptions, including QuickInvoice and the Tach Agent web client.
- **Beats** — music-production information and embedded player areas.
- **Edits** — video-editing and visual-work information with an embedded video area.

The page is implemented in `index.html` with inline CSS and JavaScript. There is no package manager, build step, or backend. Google Fonts and several image, demo, and media embeds load from external services.

## View locally

```bash
git clone https://github.com/Atty3333/Portfolio.git
cd Portfolio
python3 -m http.server 8000
```

Open `http://localhost:8000` in a browser. An internet connection is needed for remote fonts, images, project demos, and embeds.

## Before publishing

Replace the `via.placeholder.com` image references and the `YOUR_ID` BeatStars and Spotify embed values in `index.html` with the intended assets and account/track identifiers. The Software tab embeds external project URLs, so update those links if the demos move.