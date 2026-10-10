# True Crime of the Historical Kind — website concept

A static, mobile-friendly, self-hostable website concept for Elizabeth Hill.

## Preview
Open `index.html` in a browser. Internet connection loads the optional Google Fonts; fallback system fonts work offline.

## Before publishing
- Replace Spotify and Apple search links with direct podcast show URLs.
- Review episode series descriptions and status; Salem is marked "in production" as a placeholder.
- Add episode pages / RSS-powered episode updates if desired. The present prototype does **not** auto-sync an RSS feed.
- Confirm all About-page wording with the host.
- Decide whether to add email signup, Patreon link, and contact details.

## Free hosting with GitHub Pages
1. Create a public repository on GitHub and upload the contents of this folder (not the parent folder).
2. Under Settings → Pages, publish from the main branch, root folder.
3. In Pages settings, set custom domain to `truecrimeofthehistoricalkindpodcast.com`.
4. Only after GitHub recognizes the domain, update Squarespace domain DNS: four A records for the root (@): 185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153. Optionally add a `www` CNAME to `<your-github-username>.github.io`.
5. Turn on Enforce HTTPS once GitHub offers it.
6. Preserve existing MX, TXT, and other mail records. If an existing website is live, plan for the DNS change before replacing it.

Official guidance: https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site

This is a concept, not a deployed website. No domain or DNS changes have been made.
