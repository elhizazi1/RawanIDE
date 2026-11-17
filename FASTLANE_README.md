# RawanIDE Fastlane metadata

Copy the `fastlane/` directory into the root of `https://github.com/elhizazi1/RawanIDE`.

Locales: `en-US` and `ar`. Each contains `title.txt`, `short_description.txt`, and `full_description.txt`. These are descriptive listing texts, **not** an F-Droid inclusion request or certification.

## Before publishing to an app store

- Confirm the store’s supported locale codes, title and description limits, package ID, license, build provenance, and policies.
- Screenshots must be genuine captures of the released application. Add them under `fastlane/metadata/android/<locale>/images/phoneScreenshots/` after review. Do not use invented screenshots.
- Add a real icon and feature graphic only when required and sourced from approved RawanIDE artwork.
- Release changelogs belong in `fastlane/metadata/android/<locale>/changelogs/<versionCode>.txt`. The APK's verified versionCode is required; no changelog was fabricated.
- Some F-Droid tooling uses `fastlane/metadata/android/`; actual F-Droid inclusion additionally requires a suitable license, source/build metadata, and review. Metadata alone does not make an APK eligible.
- GitHub Releases assets and README are managed separately.
