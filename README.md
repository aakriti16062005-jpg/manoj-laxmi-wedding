# Manoj & Laxmi — Wedding Invitation Website

A static wedding invitation website adapted from the supplied invitation template.

## Included
- M & L envelope opening screen
- M & L intro video
- Background music with on-page sound control
- Groom-first family introduction
- Scratch-to-reveal wedding date (02 December 2026)
- Countdown to 02 December 2026 at 8:00 PM IST
- Lagan Ceremony and Wedding event cards
- Groom-side-only sign-off
- M & L social preview image (`og-preview.jpg`)

## Publish on GitHub Pages
1. Create a new GitHub repository.
2. Upload **all files and folders in this ZIP** to the repository root (not the ZIP file itself).
3. Open **Settings → Pages**.
4. Under **Build and deployment**, select **Deploy from a branch**.
5. Select the `main` branch and `/ (root)`, then Save.
6. Wait for GitHub Pages to publish the site.

## Important: set the social preview URL after publishing
The website URL is not known yet, so the Open Graph and Twitter image URLs in `index.html` currently contain:
`https://YOUR-GITHUB-USERNAME.github.io/YOUR-REPOSITORY/`

After GitHub Pages is live, replace that placeholder in the `og:url`, `og:image`, `og:image:secure_url`, and `twitter:image` tags with the actual published URL. For example, set the image URL to:
`https://YOUR-GITHUB-USERNAME.github.io/YOUR-REPOSITORY/og-preview.jpg`

## Pending detail
The wedding venue has intentionally been left out until the confirmed venue name, address, and map link are provided. The Lagan Ceremony venue is already included.

## Update later
When the wedding venue is confirmed, edit the Wedding card in `index.html` and add the venue details and directions link.
