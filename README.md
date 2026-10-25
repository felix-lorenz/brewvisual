# BrewVisual

<h3 align="center">A native Homebrew GUI for macOS — built for casual users and power users alike.</h3>

![BrewVisual 0.13.0 app catalog](assets/screenshots/catalog-overview.png?v=09cfec39d987)

Find popular apps in a clear, curated catalog, or explore Homebrew’s wider selection of apps, command-line tools, and libraries. Manage your software from one place, with package details, tap support, and Homebrew logs always within reach.

## Install

```sh
brew install --cask felix-lorenz/tap/brewvisual
```

**Requirements:** macOS 27 or later · Apple Silicon · Homebrew

BrewVisual is available in English and German. Published downloads are signed with an Apple Developer ID certificate and notarized by Apple.

Prefer a direct download? Get the ZIP from the [latest release](https://github.com/felix-lorenz/brewvisual/releases/latest), extract it, and move `BrewVisual.app` to Applications.

## Features

- **A curated app catalog.** Discover popular apps and browse organized categories without having to know package names.
- **Search beyond the catalog.** Search Homebrew formulae and casks, including software from taps you have added, and install supported packages directly.
- **Manage apps and tools.** Install, update, remove, and pin packages from a native macOS interface.
- **Keep updates in view.** Check at launch or on a configurable schedule, see available updates in the menu bar, and choose individual or bulk upgrades.
- **Homebrew logs always within reach.** Follow live command output and inspect recent operations in Activity.
- **Tap support.** Add and remove third-party taps and browse packages from your added sources.
- **Adopt existing apps.** Bring supported apps already on your Mac under Homebrew management.
- **Maintenance with a preview.** Inspect estimated storage use, run Homebrew diagnostics, and review cleanup candidates before confirming cleanup.
- **Homebrew setup included.** If Homebrew is missing, first-run setup can install it for you.
- **No tracking or telemetry.** BrewVisual collects no usage analytics and disables Homebrew analytics for commands it starts.

## Screenshots

![BrewVisual 0.13.0 inline package details](assets/screenshots/dashboard.png?v=12588a9512ef)

*Package details and installation in BrewVisual 0.13.0.*

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
