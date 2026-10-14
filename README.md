# Silo Downloads

This public repository hosts downloadable Silo preview installers. The Silo application source is in [ilovespectra/Silo](https://github.com/ilovespectra/Silo).

The [Try Silo download page](https://trysilo.kolektivkrog.si/#download) reads **published, public releases from this repository**. A draft release, or files attached only to a release in the Silo source repository, will not appear on that page.

## Installer filenames

Try Silo enables a download only when the newest published release contains the matching installer name:

- Apple silicon Mac: `Silo-<version>-arm64.dmg`
- Intel Mac: `Silo-<version>-x64.dmg`
- Windows x64: `Silo-<version>-x64-Setup.exe`

Use the release tag `v<version>` (for example, `v2.0.4`) and attach a SHA-256 checksum for each installer. Keep preview releases marked as prereleases. Draft assets can be staged for private testing; publishing makes the assets visible to visitors and updates Try Silo automatically.

## Current test status — October 11, 2026

Try Silo's live download feed currently resolves Silo 2.0.3 and has matching Apple silicon, Intel Mac, and Windows x64 installers. Silo 2.0.4's release draft is in the separate Silo source repository; until matching 2.0.4 installers are added to a release here and that release is published, Try Silo will continue to offer 2.0.3.

The 2.0.4 one-computer license rule is $25 per computer, with a separate purchase for each computer. Real card and Solana payment verification, activation, and one-computer enforcement have not yet passed the planned real-machine tests. A healthy relay status is not proof of a successful payment. Keep release notes clear about this until the two real-machine payment tests are complete.
