# applynow.nocostshoes.com → Quantum application

GitHub Pages site whose only job is to forward `applynow.nocostshoes.com` (the old agency "Start Eligibility" app, which
still posts to a retired Basin form) to the live Quantum Medical Supply application at
`https://portal.quantummedicalsupply.com/#/apply_now`, keeping any `utm_*` query parameters.

Same pattern as `nocostshoes411-redirect`. DNS: `applynow` CNAME → `matthewteamcerium.github.io` (at Aplus, managed by
Amarnath/Pocha). `404.html` is a copy of `index.html` so any path under the domain forwards too.
