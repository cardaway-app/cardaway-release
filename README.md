# Cardaway Releases

Signed and notarized Cardaway releases — binaries only, no source code.

Each release attaches two artifacts under a stable URL pattern:

    https://github.com/cardaway-app/cardaway-release/releases/download/v<version>/Cardaway-<version>.zip
    https://github.com/cardaway-app/cardaway-release/releases/download/v<version>/Cardaway-<version>.dmg

- `Cardaway-<version>.zip` — Sparkle auto-update archive (referenced by the update feed).
- `Cardaway-<version>.dmg` — first-install drag-to-Applications image.

The Sparkle update feed is served at https://cardaway-landing.pages.dev/appcast.xml.
Source repository: https://github.com/mysideproject/cardaway (private).

Cardaway is an MIT-licensed fork of SD Offload by t0nyz0; see the source repo's
LICENSE/NOTICE for attribution.

> This repo is private until the first public release. Private download links
> require a GitHub login (anonymous Sparkle clients cannot fetch them).
