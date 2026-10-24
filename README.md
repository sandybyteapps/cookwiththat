# CookWithThat website

Static pages for the CookWithThat iOS app, served by GitHub Pages from the public repo `sandybyteapps/cookwiththat`:

- `/` home
- `/privacy/` privacy policy (linked from the app and App Store Connect)
- `/support/` support page (the App Store Connect Support URL)

Plain HTML and CSS, no build step. `icon.png` (512×512) and `favicon.png` (64×64) come from the app icon (`Assets.xcassets/AppIcon.appiconset/AppIcon-light.png`).

This folder is the source. Push to `main`; GitHub Pages updates within a minute or two.
The URLs must match `AppInfo.privacyURL` in `CookWithThat/CookWithThat/Features/Recipe/RecipeSharing.swift`.
