# picklgo-legal

Public legal pages for [PicklGo](https://github.com/aaronmusa/picklgo-ios), a pickleball scorekeeper for iPhone.

Kept in its own repo so the copy can be corrected without shipping an app release.

| Page | URL |
|---|---|
| Landing | `/` |
| Privacy Policy | `/privacy/` |
| Terms of Use | Apple's Standard EULA (linked out, not hosted here) |

## Deploying

GitHub Pages, deploying from `main` at the repo root. Push to `main` and Pages republishes.

## Rules

- The privacy policy must keep matching `PicklGo/PrivacyInfo.xcprivacy` and the App Store Connect nutrition labels. If one changes, change all three.
- The app reads these URLs from `LegalLinks` in the app repo. Moving a page means updating that file, or the in-app links go dead.
- Bump the effective date in `privacy/index.html` whenever the policy text changes materially.
