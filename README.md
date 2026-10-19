<div align="center">

# OpenDock

**A per-window taskbar for macOS — every window gets its own spot, one click takes you there.**

English · [简体中文](README.zh-CN.md)

</div>

This repository is OpenDock's issue tracker: bug reports and feature requests go here. The app's
source code is not hosted in this repository.

> **Status: early development.** There is no public release yet.

## Report a problem or suggest a feature

[Open a new issue](https://github.com/gentpan/OpenDock/issues/new/choose) and pick a template:

- **Bug report** — something doesn't work as expected.
- **Feature request** — something you would like OpenDock to do.

Please [search the existing issues](https://github.com/gentpan/OpenDock/issues?q=is%3Aissue) first.
If someone has already reported the same thing, add a thumbs-up or your details there instead of
opening a new one.

For a bug report, the diagnostic info saves a round-trip: open **Settings › About**, click **Copy**
next to **Diagnostic Info**, and paste it into the report. It holds the OpenDock and macOS versions,
your Mac model, display setup and appearance settings. Nothing is sent anywhere — it only goes on
the clipboard for you to paste.

English or Chinese are both fine.

## What OpenDock is

If you come from Windows, the macOS Dock feels upside down: it shows apps, not windows. Open five
Finder folders and you get one Finder icon. OpenDock puts every window on the bar, the way the
Windows taskbar does, and keeps the rest of macOS the way you know it.

- **Respect your setup.** OpenDock does not touch the system Dock unless you turn that on, backs up
  your Dock settings before changing anything, and restores them with one click or when it quits.
- **Finder first.** Each Finder folder window is its own item. Drag a file onto an item and hover to
  bring that window forward; drop it onto a Finder item to move the file into that folder.
- **A cleaner interface.** Larger icons, stable item widths, a clear focus highlight, one settings
  window with reset buttons, and bars on the bottom, left or right edge.
- **A launcher** in the spirit of Launchpad, built into the bar.

## Requirements

- macOS 12 or later (Liquid Glass styling on macOS 26 and later)
- Accessibility permission (see below)

## Accessibility permission

OpenDock reads and switches windows through the macOS Accessibility API. On first launch it asks you
to turn it on in **System Settings › Privacy & Security › Accessibility**. OpenDock does not need
Screen Recording permission.

If the switch looks on but OpenDock still can't see your windows (this can happen after moving
OpenDock to another folder): quit OpenDock, select it in the Accessibility list and remove it with
the minus button, then open OpenDock again and grant the permission once more.

## License and credits

OpenDock is licensed under the GNU General Public License v3.0 or later (`GPL-3.0-or-later`).

OpenDock is based on **[Tungsten Edge](https://github.com/moonbai-studio/tungsten-edge)**,
Copyright (C) 2026 Moonbai Studio, licensed under GPL-3.0-or-later.

The screenshot features are ported from **[tendedero](https://github.com/alejandrobujan/tendedero)**,
Copyright (c) 2026 Alejandro Buján, licensed under the MIT License.

"Tungsten Edge" and "钨极" are trademarks of Moonbai Studio. OpenDock is a separate project and is not
affiliated with or endorsed by Moonbai Studio.
