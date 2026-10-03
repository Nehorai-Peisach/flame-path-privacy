# Flame Path — Privacy Policy

The privacy policy for the [Flame Path](https://apps.apple.com/) iOS game, served by GitHub Pages.

Required by two separate parties, both of which refuse to proceed without it:

- **Google AdMob** will not publish a GDPR consent message for an app that has no privacy policy URL.
- **Apple** requires one on every App Store listing.

`index.html` is the policy and `support/index.html` the support page (the App Store's
Support URL). Both share `style.css`, which dresses them in the game's palette and its two
typefaces. The fonts are served from `fonts/` rather than Google Fonts, so a visit sends
nobody's address to a third party: M PLUS Rounded is subset to Latin, and Titan One ships
whole (only rewrapped as WOFF), because its Reserved Font Name does not survive a subset.
Their OFL licences sit beside them. `icon.png` and `favicon.png` are the app icon, scaled
down. Edit, commit, push — Pages redeploys within a minute or so.

Facts in it are drawn from what the app actually does: the save in `UserDefaults`, a backup in
the player's own iCloud Drive through Game Center, the ledger on Supabase (Game Center player
ID, purchase receipts, a daily progress line), no analytics SDK, and an advertising data table
taken from Google's own published `PrivacyInfo.xcprivacy` for the Mobile Ads SDK rather than
from marketing copy. When the app starts collecting anything new, this page changes with it.
