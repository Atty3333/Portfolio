# Atang Letso Mutema | Portfolio

A static, single-page portfolio and CV for Atang Mutema . It presents profile and education information alongside software, music-production, and video-editing work.

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

