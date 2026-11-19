# RawanIDE APK Publishing Checklist (Maintainer)

This checklist is for the RawanIDE Android app's public distribution repository, not for the Extension SDK or Marketplace releases.

## Before publishing

- [ ] Confirm the exact APK, `versionName`, `versionCode`, application ID, and signing certificate.
- [ ] Verify the APK installs and starts on a supported device.
- [ ] Test the features you intend to claim in release notes; note any untested areas.
- [ ] Review the release's distribution permissions, third-party notices, and source-availability obligations as applicable.
- [ ] Remove credentials, private files, and signing keys from release assets.

## GitHub release

- [ ] Create the correct tag and title for the verified version.
- [ ] Write release notes for this build; do not publish the placeholders in `RELEASE_NOTES.md`.
- [ ] Upload the intended signed APK and verify the exact published filename.
- [ ] Calculate SHA-256 from that APK and publish the matching checksum.
- [ ] Confirm that the release's download link works.
- [ ] Confirm links in `README.md` and `README.ar.md` still work.

## Optional distribution channels

- [ ] If publishing store metadata, review `FASTLANE_README.md` and the actual store's requirements.
- [ ] Use genuine screenshots of the released application, not concept mockups.
- [ ] Check the live Help, About, and Privacy pages for accuracy.

## Repository metadata (optional)

**Description:** RawanIDE — Android IDE with a local editing workspace, Termux integration, embedded preview, and an extension ecosystem.

**Website:** https://rawanide.elhizazi.me
