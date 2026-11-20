# Pocket Backup website

Static site for Pocket Backup (on-demand admin for small businesses, starting with Queensland electricians). Deployed on Netlify (free plan) from the `main` branch; publish directory is the repo root. No build step.

- `index.html` homepage (Netlify Forms contact form named `contact`)
- `thanks.html` form confirmation, `privacy.html` privacy policy, `404.html` not-found page
- `fonts/` self-hosted Barlow and IBM Plex Mono (SIL Open Font License)
- `netlify.toml` security and cache headers

Still to add when available (search for `TODO(Eva)`): ABN, SAA accreditation number. (No public phone number by choice: the form asks for the customer's number and we call back.)
