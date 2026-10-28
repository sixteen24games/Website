# 1624 Games website

The studio site for 1624 Games: a home page for Scrattle, Gem Buzz, Hexcape and Hexcoil, and a privacy policy that covers all four games.

Plain HTML with no build step. Fonts load from Google Fonts; everything else is in this folder.

| File | What |
|---|---|
| `index.html` | Home page: the games, how we make them, contact |
| `privacy.html` | Privacy policy for every game. This is the URL the App Store and Google Play ask for |
| `assets/` | The bee mark (from the logo, without the wordmark) and 256 px app icons |
| `.nojekyll` | Tells GitHub Pages to serve the files as they are |

## Publishing with GitHub Pages

Settings → Pages → Source: *Deploy from a branch*, branch `main`, folder `/ (root)`. The site appears at `https://<user>.github.io/1624games-site/`, and the privacy policy at `.../privacy.html`. A custom domain can be added on the same settings page.

## Before launch

- **Contact email:** `hello@1624games.com` is a placeholder, in `index.html` (contact section and footer) and `privacy.html` (contact section and footer).
- **Privacy policy:** remove the *Draft* notice, set the effective date, and add the legal entity's name and address once the policy has been reviewed.
- **Game status:** each game card says "Coming soon to the App Store and Google Play". Replace it with store links as the games launch.
