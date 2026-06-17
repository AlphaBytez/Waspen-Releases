# Waspen Releases

Public release, checksum, and support metadata for Waspen desktop builds.

This repository is the public distribution surface for Waspen installers, release notes, checksums, and support routing. The Waspen application source code remains private.

## Release Channels

- **GitHub Releases**: signed installer artifacts, release notes, and checksums.
- **Backblaze mirrors**: optional alternate download URLs for larger artifacts or CDN-backed delivery.
- **Mac App Store**: separate store channel when available. Store builds may use different purchase and update rules.

## macOS Distribution

Direct macOS builds should be signed with Developer ID and notarized before public release. GitHub or Backblaze downloads should include SHA-256 checksums and signing/notarization status in the release notes.

Mac App Store builds should stay channel-separated from direct builds. Do not assume a direct license or updater flow is allowed inside the MAS build without checking the current Apple Developer Program terms and App Review Guidelines.

## Windows Distribution

Windows installers can be attached to GitHub Releases and mirrored through Backblaze. Release notes should include architecture, minimum Windows version, installer type, and SHA-256 checksum.

## Licensing

Waspen license files can be generated independently of platform distribution. A public release artifact can support Free mode by default and unlock Pro with a valid license file where the channel permits it.

## Support

Use GitHub Issues for release-specific installation problems, broken download links, checksum mismatches, and public beta feedback. For licensing, private diagnostics, or account-specific support, email support@alphabytez.dev.
