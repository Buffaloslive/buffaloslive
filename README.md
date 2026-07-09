# Post Oak Live

Static website for PostOakLive.com / Buffalos Live.

## Stack

- Static HTML
- CSS custom properties
- Lightweight JavaScript only for footer year and header state
- Hosted on GitHub Pages

## Pages

- `index.html` — landing page
- `live.html` — Varsity Hype livestream page
- `hype.html` — Twitch hype video page

## Media

- Live stream: https://app.varsityhype.com/livestream/16e0a0a6-6b84-4c00-9dd6-6ca06510db5c/
- Hype video: https://www.twitch.tv/videos/2815794470

Both media pages use embedded iframes plus direct-link fallbacks because external providers may block embedding on some devices or domains.

## Maintenance

This site intentionally avoids build tooling, backends, databases, and dependencies. Edit the HTML/CSS directly and push to GitHub Pages.
