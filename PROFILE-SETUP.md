# GitHub profile and public repository setup

The files in this folder assume:

- GitHub account or organization: `rosuii`
- Public repository: `rosuii`
- Repository URL: `https://github.com/rosuii/rosuii`
- GitHub Pages URL: `https://rosuii.github.io/rosuii/`

## Why this repository name matters

If the GitHub **user account** is named `rosuii`, a public repository also named `rosuii` is the special profile repository. Its root `README.md` appears on the GitHub profile.

If an **organization** is named `rosuii`, the organization profile README normally lives in a separate `.github` repository at `.github/profile/README.md`. This repository can still be the public product-information and Pages repository.

## Publish steps

1. Create or claim the GitHub user/organization only through an authorized Rosuii account.
2. Create a new **public**, empty repository named `rosuii`. Do not add a README or license in GitHub because this local repository already contains them.
3. In this folder, set the remote and push:

   ```bash
   git remote add origin https://github.com/rosuii/rosuii.git
   git push -u origin main
   ```

4. Open repository **Settings → Pages** and select **GitHub Actions** as the source. The included workflow deploys the static page.
5. After the workflow passes, verify `https://rosuii.github.io/rosuii/`.
6. Add the live GitHub and YouTube URLs to Rosuii's official website and Organization schema only after Rosuii controls them.

## If the username is not `rosuii`

Before publishing, replace `https://rosuii.github.io/rosuii/` and `https://github.com/rosuii/rosuii` in:

- `index.html`
- `README.md`
- `CITATION.cff`
- `robots.txt`
- `sitemap.xml`

Use the real public URLs. Do not publish placeholder or unowned profile links as official `sameAs` identities.

## Human information still required for directories

The Capterra, Crunchbase and G2 files deliberately leave legal name, founding year, founders, team size, funding and similar company facts unfilled. Complete them only with authorized records; do not estimate them.

