# BrewVisual

<h3 align="center">Your Homebrew apps, tools, and updates — in one native Mac app.</h3>

![BrewVisual 0.17.0 app catalog](assets/screenshots/dashboard.png?v=96f8eb9c452c)

See what’s installed and what needs updating. Install, upgrade, and remove Homebrew apps and command-line tools, with scheduled update checks and available updates in the menu bar.

## Install

```sh
brew install --cask felix-lorenz/tap/brewvisual
```

**Requirements:** macOS 26 or later · Apple Silicon · Homebrew

BrewVisual is available in English and German. Published downloads are signed with an Apple Developer ID certificate and notarized by Apple.

Prefer a direct download? [Download the DMG](https://github.com/felix-lorenz/brewvisual/releases/latest/download/BrewVisual.dmg), open it, and drag `BrewVisual.app` to Applications.

## Features

- **Control updates.** Schedule checks, see available updates in the menu bar, and choose individual or bulk upgrades. Optionally enable automatic formula updates and pause Homebrew updates for apps with their own updater.
- **Manage apps and tools.** Install, remove, and pin packages, or bring compatible apps already on your Mac under Homebrew management.
- **Maintenance with a preview.** Inspect estimated storage use, run Homebrew diagnostics, and review cleanup candidates before confirming cleanup.
- **Discover apps and search Homebrew.** Browse a curated app catalog and search Homebrew apps, command-line tools, and libraries, including packages from your added taps. Catalog metadata is powered by [CaskFlow](https://github.com/alielsokary/CaskFlow).
- **Manage third-party sources.** Add and remove taps and browse packages from your added sources.
- **Homebrew logs always within reach.** Follow live command output and inspect recent operations in Activity.
- **Homebrew setup included.** If Homebrew is missing, first-run setup can install it for you.

## Screenshots

<img src="assets/screenshots/menu-bar-icon.png?v=b2a34709da2f" alt="BrewVisual menu-bar icon showing eight available updates" width="35" height="30">

*Menu-bar icon in BrewVisual 0.13.0 with eight available updates.*

<img src="assets/screenshots/menu-bar-overlay.png?v=e23308cf36a7" alt="BrewVisual 0.13.0 menu-bar popover during a bulk upgrade" width="402">

*The menu-bar popover during a bulk upgrade in BrewVisual 0.13.0.*

## Permissions

Depending on the operation, macOS or Homebrew may require:

- **App Management access** to install, update, or remove app casks. Enable BrewVisual in **System Settings → Privacy & Security → App Management** when needed. If an update error names **BrewVisual Updater**, review access for that helper separately.
- **Administrator authorization** for Homebrew setup or protected installation steps. BrewVisual requests your password only when needed, passes it only to `sudo`, and never stores it or includes it in command logs.

## Privacy

BrewVisual does not collect usage analytics or send telemetry. Homebrew analytics are also disabled for commands started by BrewVisual.

The app makes network requests to load package and catalog data, icons, release notes, and software downloads. The services involved receive normal connection information, including your IP address.

## Feedback and support

Enjoy using BrewVisual? Please [give the project a star on GitHub](https://github.com/felix-lorenz/brewvisual).

You can support development on [Ko-fi](https://ko-fi.com/felixlorenz).

Found a bug or have an idea? [Open a GitHub issue](https://github.com/felix-lorenz/brewvisual/issues). Include your BrewVisual, macOS, and Homebrew versions, steps to reproduce the problem, and relevant command output. Remove personal information before sharing screenshots or logs.

## About this repository

This repository provides BrewVisual documentation, screenshots, release notes, and downloads. The source code is private.

BrewVisual is an independent app and is not affiliated with or endorsed by the Homebrew project.
