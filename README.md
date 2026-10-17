# Rift Ledger website

Public website for [riftledger.io](https://riftledger.io), hosted with GitHub Pages.

## Edit and publish

Edit `index.html`, `styles.css`, or `app.js`, then commit and push to `sudoryan/site`.
GitHub Pages publishes the repository root automatically. No build service, API key,
or paid hosting plan is required for the current static site.

- `privacy/index.html`: extension privacy policy, website hosting disclosure, support contact.
- `assets/`: screenshots and site icon.
- `downloads/RiftLedgerCompanion.zip`: manual-install extension package (includes its outer folder).
- `riot.txt`: existing Riot site verification; preserve this file.
- `CNAME`: custom domain configuration once the domain is connected.
- `.nojekyll`: serves these files directly without Jekyll processing.

To preview locally: `python3 -m http.server 4173`, then open http://localhost:4173.
Check desktop and mobile layouts, navigation, the privacy link and the downloaded
extension manifest version before publishing a new release.

This repository contains the public website and downloadable extension only.
Rift Ledger is independent of Riot Games and RiftAtlas. Riftbound artwork belongs
to Riot Games; screenshots depict sample matches. Existing third-party rights apply.
