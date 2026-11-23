# firazoscar.com

Personal site of Firaz Wianda Faric Oscar. Plain static HTML + CSS, no build step. Hosted on Vercel.

- `index.html`: the whole page. `assets/site.css`: styles (light and dark tokens at the top).
- `Firaz_Oscar_Resume.pdf`: the public CV the page links to, with the phone number removed. The full original stays local only (`Firaz_Oscar_Resume.original.pdf`, git-ignored). To update: export a no-phone version and replace this file (keep the name).
- `og.png`: link preview image (1200x630). `favicon.svg`, `favicon-32.png`, `apple-touch-icon.png`: icons.
- `assets/img/*.webp`: screenshots (demo data), made with ffmpeg from the project screenshot folders.

## TODO

- TemanCukur live link: search `TODO(live-link)` in `index.html` and delete the `hidden` attribute on the line below it once the redeploy is live.

## Local preview

`python -m http.server 8787` in this folder, then open http://127.0.0.1:8787/

## Domain

`firazoscar.com` was bought on Vercel and is attached to this Vercel project (Settings > Domains), with `www.firazoscar.com` redirecting to it. If you ever move the domain elsewhere: add `firazoscar.com` under Settings > Domains, then point DNS at Vercel (A record `@` to `76.76.21.21`, CNAME `www` to `cname.vercel-dns.com`), or use Vercel's nameservers.
