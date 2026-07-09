# Post Oak Live

Static production site for Post Oak Live, focused on Post Oak Little League and the current featured team: the Post Oak 10s All Stars.

## Stack

- Plain HTML/CSS/JavaScript
- GitHub Pages from the `main` branch root
- Self-hosted HTML5 MP4 hype video

## Pages

- `index.html` — primary landing page
- `live.html` — live stream page with provider embed and direct fallback
- `hype.html` — self-hosted state tournament hype video page

## Brand assets

- `assets/brand/post-oak-little-league-logo.png` — primary Post Oak Little League logo
- `assets/brand/post-oak-logo-512.png` — compact site/fav icon
- `assets/brand/post-oak-state-art.jpg` — state tournament art reference

## Video assets

- `assets/video/post-oak-10s-hype.mp4` — web-ready 720p MP4, metadata-preload friendly
- `assets/video/hype-poster.jpg` — generated poster frame

## Notes

The public custom-domain setting currently remains on `buffaloslive.com`, with PostOakLive.com forwarding to the updated GitHub Pages site. If GoDaddy access is available later, the preferred cleanup is to point PostOakLive.com directly at GitHub Pages and set the GitHub Pages custom domain to `postoaklive.com`.
