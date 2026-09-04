# XO Spark

Free, fast, responsive **Tic-Tac-Toe** game for laptop and mobile, with smart computer opponent and a daily **Thirukkural** verse.

The English Thirukkural fallback uses the public-domain translation by **Rev. G. U. Pope**. Tamil is shown by default; use the language selector on the Kural card to switch to English.

## Features

- Local 2-Player and vs Computer modes (Easy, Medium, Hard).
- Random starting player each round.
- Sound effects with on/off toggle.
- Original synthesized WebAudio cues; no third-party audio files or music licenses required.
- Move counter and best-win streak.
- Share-score button.
- Sixteen themes including Arcade Rush, Christmas, Diwali, Holi, Navratri, Pongal, and Halloween.
- Thirukkural verses from Thiruvalluvar, with Tamil original and English translation.
- Responsive layout for laptop, tablet, and mobile.
- SEO-ready: canonical URL, Open Graph, JSON-LD, sitemap, robots, llms.txt, and a custom favicon.

## Publish with Vercel

### Beginner steps

1. Install Git and create a GitHub account.
2. Create a new GitHub repository named `xo-spark`.
3. Upload these files from this folder:
   - `index.html` (small GitHub Pages redirect)
   - `xo-game.html`
   - `vercel.json`
   - `public/` (contains `robots.txt`, `sitemap.xml`, `llms.txt`, `favicon.svg`)
4. Create a free Vercel account and choose **Add New Project**.
5. Import the `xo-spark` repository.
6. Framework Preset: **Other**, Build/Output/Install commands: leave empty.
7. Click **Deploy**.
8. Vercel will give a public `https://xo-spark.vercel.app` URL. Share it.

### After deployment

- Submit the URL to **Google Search Console** so Google can index it.
- In Vercel, the public URL is HTTPS by default and works on both laptop and mobile.

## Local testing

You can double-click `xo-game.html` for a quick local test. For the real public webpage, use the HTTPS URL provided by Vercel.

## Device use

Open the same public URL on a laptop or phone. Use **2 Players** when two people share one screen, or **vs Computer** for solo play.
