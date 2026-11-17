# Publishing checklist — RawanIDE

## Repository

- [ ] Confirm the repository's intended visibility and whether it contains source code or only distribution files.
- [ ] Add `README.md`, `README.ar.md`, `SUPPORT.md`, `SECURITY.md`, `CONTRIBUTING.md`, and issue templates.
- [ ] Verify the repository license status. If it is open source, publish the actual applicable `LICENSE` text after choosing/confirming the license.
- [ ] Set GitHub About description and website; add topics.
- [ ] Enable Discussions only if you plan to moderate them.
- [ ] Enable private vulnerability reporting if available.

## Release

- [ ] Verify actual `versionName` / `versionCode` from the build or source; choose an accurate release tag.
- [ ] Verify the APK is the intended release and has the correct application ID and signing identity.
- [ ] Create a GitHub Release with `RELEASE_NOTES.md` content, replacing VERSION.
- [ ] Upload `RawanIDE-release-signed.apk` under Assets.
- [ ] Verify the published SHA-256 matches the actual uploaded APK.
- [ ] Do not upload `mapping.txt` publicly unless you explicitly intend to disclose the obfuscation mapping.
- [ ] Confirm https://github.com/elhizazi1/RawanIDE/releases/latest works.
- [ ] Confirm the Marketplace download button targets the exact release asset name and downloads successfully.
- [ ] Test the installed APK, permissions, project opening, preview, and optional integrations.
- [ ] Verify the live help/about/privacy pages describe the current app behavior.

## Suggested GitHub About

**Description:** Android IDE for editing, managing, and previewing local development projects, with Termux integration and an extensible marketplace.

**Website:** https://rawanide.elhizazi.me

**Topics:** android, ide, android-development, code-editor, termux, web-development, developer-tools, webview, extensions

**Suggested release title:** RawanIDE vX.Y.Z (replace with verified version)

**Release asset filename:** RawanIDE-release-signed.apk

**Optional screenshot:** Add only screenshots captured from the actual current release, not mockups presented as real UI.
