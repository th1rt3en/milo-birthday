# Milo's 1st Birthday 🎈

A simple single-page invite site with the party date, a map to the venue, and a QR code for well-wishers who can't attend to send a gift.

## Editing before publishing

- **QR code:** the real VPBank VietQR image is at [assets/bank-qr.jpg](assets/bank-qr.jpg), referenced from the "Can't make it?" section.
- **Venue/map:** currently set to Long Biên Palace. To change it, update the `iframe src` (swap the lat/lng) and the "Get Directions" link in `index.html`.

## Publishing to GitHub Pages

1. Push this repo to GitHub.
2. In the repo, go to **Settings → Pages**.
3. Under "Build and deployment", set **Source** to "Deploy from a branch".
4. Choose branch `main` and folder `/ (root)`, then **Save**.
5. Your site will be live at `https://<your-username>.github.io/<repo-name>/` within a minute or two.
