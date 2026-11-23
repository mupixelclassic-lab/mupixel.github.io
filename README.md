# Mu Pixel — Pixelore website

Static website files prepared for GitHub Pages.

## Files
- `index.html` — homepage
- `privacy-policy.html` — Polish privacy policy
- `privacy-policy-en.html` — English privacy policy
- `delete-account.html` — account deletion instructions in Polish and English
- `assets/style.css` — shared styling

## Publish with GitHub Pages
1. Upload the contents of this ZIP to the root of the repository `mupixelclassic-lab/mupixel.github.io` (the files should sit next to README.md, not inside an extra folder).
2. In GitHub, open **Settings → Pages**.
3. Under **Build and deployment**, select **Deploy from a branch**.
4. Select branch `main` and folder `/ (root)`, then save.
5. Wait for deployment and open `https://mupixelclassic-lab.github.io/`.

## Expected URLs
- https://mupixelclassic-lab.github.io/
- https://mupixelclassic-lab.github.io/privacy-policy.html
- https://mupixelclassic-lab.github.io/privacy-policy-en.html
- https://mupixelclassic-lab.github.io/delete-account.html

## Important checks before publishing
- Confirm that KORBANK S.A. is the actual hosting/infrastructure provider for the game server.
- Confirm that the public-facing identification “Sam” is sufficient for the applicable GDPR transparency requirements. A pseudonym may not replace the legal identity/contact details required of a natural-person data controller.
- Confirm that the described data flows and retention periods match the live game and hosting setup.
- The deletion page currently describes email-based requests. Monitor the mailbox and implement an effective deletion process. Google Play also requires an account-deletion initiation path from within the app; implement this before declaring the app compliant.
- If the game is intended for users aged 13+, review Google Play target-audience and Families requirements. “13+” does not automatically remove all child-related obligations in every country.
- Do not claim that an in-game deletion feature is live until it has actually been implemented.
