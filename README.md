# Huckleberry Hounds Dog Grooming

Static website for Huckleberry Hounds Dog Grooming, a full-service dog grooming studio in Spokane Valley, WA owned and operated by Amanda Zietz.

## Tech Stack

- **HTML** — single-page static site (`index.html`)
- **Tailwind CSS** — loaded via Play CDN (no build step)
- **Alpine.js v3.14.9** — loaded via CDN for mobile nav toggle
- **Google Fonts** — Fredoka (headings) + Poppins (body)

No build tools, no npm, no bundlers. Everything runs from CDNs.

## Deploying to GitHub Pages

1. Push this repository to GitHub.
2. Go to **Settings > Pages** in the repository.
3. Under **Source**, select **Deploy from a branch**.
4. Set the branch to `main` and the folder to `/ (root)`.
5. Click **Save**. The site will be live at `https://<username>.github.io/<repo-name>/` within a few minutes.

To use a custom domain, update the `CNAME` file with the domain name and configure DNS accordingly.
