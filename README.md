# ddx150-eval — static front end for the Protégé 150 DDx rating study

Published with GitHub Pages (branch `main`, root), the same way as `doctor-eval`.
Unlike doctor-eval, this page needs no backend: the 150 blinded cases are embedded in the HTML,
ratings are kept in the rater's browser (localStorage) and returned by the rater via **export CSV**.

- `/`      landing page with links to both versions
- `/v2/`   Version 2.0 — closeness 1–5 per candidate + follow-up "reasonable for this HPI?" when closeness is 1–3
- `/v3/`   Version 3.0 — closeness 1–5 per candidate + appropriateness 1–5 per group (AMIE-style)

Group→arm mapping is NOT in this repo (blind_key_150_CONFIDENTIAL.json, PI only).
