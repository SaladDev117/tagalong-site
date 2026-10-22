# tagalong-site

Public pages for the TagAlong Android app, served by GitHub Pages at
https://saladdev117.github.io/tagalong-site/

| Page | Used for |
| --- | --- |
| `index.html` | Privacy policy (linked from the app's Settings and the Play listing) |
| `terms.html` | Terms of service |
| `delete-account.html` | Account deletion instructions (Play Console → Data safety → delete account URL) |
| `404.html` | Invite-link fallback: `/tagalong-site/join/CODE` shows the code with Open in app / Get it on Play buttons; any other missing path shows "Page not found" |

Root-level files that Android and AdMob look for (`/.well-known/assetlinks.json`, `/app-ads.txt`)
can't live in a project site, so they are in the `SaladDev117/SaladDev117.github.io` repo.
