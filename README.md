# thatnicole.com

Personal portfolio for Nicole DeAngelis. Plain HTML, CSS and JS with no build step.

## Publish on GitHub Pages (GitHub Desktop)
1. Install GitHub Desktop from desktop.github.com and sign in to GitHub.
2. File → Add Local Repository → choose this `thatnicole-site` folder.
3. In the Changes tab, type a summary such as "Launch new portfolio" and click Commit to main.
4. Click Publish repository. Keep the name `thatnicole-site` and untick "Keep this code private" (Pages is free for public repos).
5. On github.com, open the repo → Settings → Pages. Set Source to "Deploy from a branch", choose `main` and `/ (root)`, then Save.
6. The site goes live at `https://<your-username>.github.io/thatnicole-site/` within a minute or two.

To update later: edit files, then in GitHub Desktop commit and click Push origin.

## Custom domain (thatnicole.com)
1. In Settings → Pages, enter `thatnicole.com` as the custom domain. GitHub adds a `CNAME` file.
2. At your DNS provider, add A records for `@` pointing to 185.199.108.153, 185.199.109.153, 185.199.110.153 and 185.199.111.153, plus a CNAME record for `www` pointing to `<your-username>.github.io`.
3. Turn on "Enforce HTTPS" once the certificate is issued.

## Editing
- All copy lives in `index.html`.
- Case study screen recordings are in `assets/video/` (`<name>.mp4` plus `<name>-poster.jpg`). Replace a file with the same name to update it.
- Recommendation photos are in `assets/people/`, logos in `assets/logos/`.
- Swap `Nicole-DeAngelis-Resume.pdf` to update the résumé link.
