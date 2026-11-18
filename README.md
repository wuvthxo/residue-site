# residuefw.org

Landing page for RESIDUE., an independent docu-series about growing up in Fort Wayne, Indiana.

Static site, no build step. `public/index.html` is the whole page. Hosted on Cloudflare Workers (static assets in `public/`). Deploy: `npm run deploy`.

Preview locally: `python3 -m http.server 8080` from `public/`, then open http://localhost:8080
