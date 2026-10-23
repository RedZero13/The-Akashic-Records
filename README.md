# The Akashic Records

A legal-intelligence platform in development: a Terratales venture. This repository holds the public preview at
**https://akashic.terratalesmedia.world**.

The preview shows the look and feel and a sample of the planned features: the advocate directory, law-firm
profiles, bar associations, internships, case-tracking and firm dashboards, messaging and registration.

**Every piece of data in the preview is representative sample data for testing.** No advocate, firm, case, judge,
organisation, figure or fee is real, and nothing a visitor enters is sent or stored. The site says so in a banner on
every page, a notice on the first visit and the footer.

## Run it

It is a single static page: open `index.html`, or serve the folder (`python3 -m http.server`).

## Deploy

`.github/workflows/pages.yml` publishes the site to GitHub Pages on every push to `main`. `CNAME` points it at
`akashic.terratalesmedia.world`; the domain needs a DNS `CNAME` record from `akashic` to `redzero13.github.io`.

© 2026 TERRATALES MEDIA ENTERTAINMENT PRIVATE LIMITED
