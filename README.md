# Atang Letso Mutema | Portfolio

A static, single-page portfolio and CV for Atang Mutema, implemented in `index.html` with inline CSS and JavaScript. It opens with an intro screen before the portfolio content; click to enter or wait five seconds.

## Sections

- **Overview** — CV content for a Systems Engineering student at Botswana Accountancy College, including engineering and audio/visual skills, profile, certification, experience, and education.
- **Software** — work described around AI agents and MCP tools, self-hosted Ubuntu/Nextcloud, Kotlin app development, and embedded QuickInvoice and Tach Agent demos.
- **Beats** — music-production and independent producer information, with BeatStars and Spotify embeds.
- **Edits & Visuals** — DaVinci Resolve work and an embedded video example.

The page also links to a LinkedIn profile. It has no package manager, build step, or backend. Google Fonts, images, and media/demo embeds load from external sites, so an internet connection is needed for those elements.

## View locally

```bash
git clone https://github.com/Atty3333/Portfolio.git
cd Portfolio
python3 -m http.server 8000
```

Open `http://localhost:8000` in a browser.

## Replace placeholder media

The current HTML still includes `via.placeholder.com` images, a BeatStars embed with `storeId=YOUR_ID`, a Spotify embed with `YOUR_TRACK_ID`, and a YouTube video embed. Replace these references with the intended images, account/track IDs, and video before treating the page as a finished portfolio.