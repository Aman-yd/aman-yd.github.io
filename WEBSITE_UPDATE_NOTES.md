# Ocabico site update — November 2026

## Done
- Added third featured app: Block Blast Classic, using the existing `assets/bloack_blast.png`.
- Renamed the public-facing StackRiot card to UNO Stack! No Mercy.
- Updated page description, page title, and app count to 3.
- Preserved existing A1 Thermal Printer links and printer product JSON, ads.txt, and robots.txt.
- Preserved both existing privacy policy links and the UNO account deletion link.
- Responsive CSS for the third app card.

## Before publishing / Google OAuth verification
1. Confirm the official Google Play URL for Block Blast Classic; there is no verified package ID in this repository, so no store URL was invented. Replace the informational availability line with a Play Store button once confirmed.
2. Confirm whether the UNO Stack app's current Play Store listing and privacy-policy URLs still match its rebranded name.
3. Publish a full, accurate privacy policy for Block Blast Classic. This source package only contained published privacy links for UNO and A1 Thermal Printer.
4. Publish an accessible Terms of Service page (either a shared agreement with app-specific sections or separate agreements). The original project has none.
5. For Google Auth Platform, the OAuth homepage can be the public GitHub Pages root. Privacy and Terms URLs must be working public pages, not placeholders.
6. Check the site under its real GitHub Pages URL after deployment and ensure asset paths are correct (especially if served from a project subpath).

## Deployment
Copy changed `index.html`, `style.css`, and new notes to the repo root, commit and push to the branch configured in GitHub Pages. Do not upload .git from the original ZIP.
