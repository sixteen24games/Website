# 1624 Games website

The studio site for 1624 Games: a home page for Scrattle, Gem Buzz, Hexcape and Hexcoil, and a privacy policy that covers all four games.

Plain HTML with no build step. Fonts load from Google Fonts; everything else is in this folder.

| File | What |
|---|---|
| `index.html` | Home page: the games, how we make them, contact |
| `privacy.html` | Privacy policy for every game. This is the URL the App Store and Google Play ask for |
| `assets/` | The bee mark (from the logo, without the wordmark) and 256 px app icons |
| `app-ads.txt` | The ad sellers allowed to sell ads in the games (the IAB app-ads.txt standard). Ad networks read it at https://1624games.com/app-ads.txt, so it has to stay at the site root |
| `CNAME` | The custom domain, 1624games.com |
| `.nojekyll` | Tells GitHub Pages to serve the files as they are |

## Publishing with GitHub Pages

Settings → Pages → Source: *Deploy from a branch*, branch `main`, folder `/ (root)`, custom domain `1624games.com`. The site is at https://1624games.com and the privacy policy at https://1624games.com/privacy.html.

## Before launch

- **Contact email:** `hello@1624games.com` is a placeholder, in `index.html` (contact section and footer) and `privacy.html` (contact section and footer).
- **Privacy policy:** remove the *Draft* notice, set the effective date, and add the legal entity's name and address once the policy has been reviewed.
- **Game status:** each game card says "Coming soon to the App Store and Google Play". Replace it with store links as the games launch.
- **app-ads.txt:** Google AdMob, ironSource (publisher 695901) and Unity Ads (159517641), with ironSource's resellers (from its docs page, 2026-10-28) and Unity's (from the Unity Monetization dashboard, Settings → Organization, 2026-10-29). Recopy both reseller lists now and then, since they change. Each game's store listing must give https://1624games.com as the developer website for the file to count.
