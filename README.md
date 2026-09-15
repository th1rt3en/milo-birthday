# Milo's 1st Birthday 🎈

A simple single-page invite site with the party date, a map to the venue, and a QR code for well-wishers who can't attend to send a gift.

## Editing before publishing

- **Placeholders to update in [index.html](index.html):**
  - Party time (currently `10:00 AM – 1:00 PM`)
  - Bank details in the "Can't make it?" section (bank name, account name, account number)
- **QR code:** replace [assets/qr-placeholder.svg](assets/qr-placeholder.svg) with your real bank transfer QR image. Keep the filename `assets/qr-placeholder.svg`, or update the `src` in `index.html` if you rename/change the file type (e.g. `assets/qr.png`).
- **Venue/map:** currently set to Long Biên Palace. To change it, update the `iframe src` (swap the lat/lng) and the "Get Directions" link in `index.html`.

## Publishing to GitHub Pages

1. Push this repo to GitHub.
2. In the repo, go to **Settings → Pages**.
3. Under "Build and deployment", set **Source** to "Deploy from a branch".
4. Choose branch `main` and folder `/ (root)`, then **Save**.
5. Your site will be live at `https://<your-username>.github.io/<repo-name>/` within a minute or two.
