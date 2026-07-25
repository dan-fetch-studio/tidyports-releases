# TidyPorts releases

Downloads and release notes for **TidyPorts**, a macOS menu-bar app for seeing what is
running on your local ports, opening it, and closing what you are not using.

The app's source is not in this repository. This repo exists only to host release
downloads and their notes.

## Download

**[Download TidyPorts for macOS](https://github.com/dan-fetch-studio/tidyports-releases/releases/latest/download/TidyPorts.dmg)**

That link always resolves to the newest release, so it is safe to bookmark or link to.
Every release also carries a version-stamped copy (`TidyPorts-<version>.dmg`) if you need a
specific build, and a `SHA256SUMS.txt` so you can verify what you downloaded:

```bash
shasum -a 256 -c SHA256SUMS.txt
```

Requires macOS 15 or later. Builds are signed with a Developer ID and notarized by Apple,
so they open without an unidentified-developer warning.

## What changed

See [Releases](https://github.com/dan-fetch-studio/tidyports-releases/releases) for the
notes on each version.

## Issues

Found something broken, or want to suggest a feature? Open an
[issue](https://github.com/dan-fetch-studio/tidyports-releases/issues). Please include your
macOS version and the TidyPorts version from Settings, under Help & about.

---

Made by [Dan Marek](https://github.com/dan-fetch-studio) · [@TidyPorts](https://x.com/TidyPorts)
