---
title: Maintenance
layout: default
nav_order: 10
parent: Documentation
---

# Maintenance and Troubleshooting

Occasionally, the application may encounter issues. Here are some steps you can take to resolve them.

If you experience any problems or have suggestions, use the User Feedback form at the bottom of the app or contact us at contact@masqueworks.com.

## Load with Default Layout (Hold Shift on Startup)

Holding the **Shift** key while starting the app resets the window layout to default, ignoring any saved layout settings. This is useful if windows are misplaced or off-screen.

## Temporary Performance Files

Each performance folder contains a `.masque` directory that stores temporary data, such as window layouts. You can safely delete this folder without affecting critical performance data.

## Application Folder

The application installation directory is located at `%LOCALAPPDATA%\Masque`. It contains several important folders:

- **Custom Fixtures** – Stores custom fixture definitions separate from those downloaded from the [Open Fixture Library](https://open-fixture-library.org/). Custom fixtures can be shared and contributed back to the Open Fixture Library.
- **FFmpeg** – Contains Masque's built-in LGPL version of FFmpeg. You can replace it with a custom version if you have the appropriate licensing. The default version can be found [here](https://github.com/BtbN/FFmpeg-Builds/). Note that different versions may cause instability or data loss.
- **Fixtures** – Holds downloaded fixture definitions from the Open Fixture Library. These can be updated manually by downloading the latest JSON file, but compatibility with newer versions is not guaranteed.
- **Masque** – The core application and documentation files.s
- **USBDMX** – Contains FTDI drivers required for USB-to-DMX dongles. Drivers are sourced from [FTDI Chip](https://ftdichip.com/drivers/d2xx-drivers/).
- **.masque** – Stores global application settings, configurable through the Settings Window. Deleting this folder resets all settings to default, which may resolve certain issues.

**Note:** Updating or modifying these components may lead to instability or data loss. Use caution when making changes.

## Release Rings

Users can choose different **Release Rings** to receive updates at varying levels of stability. This setting is found in the **Settings Window** under `General > Release > Release Ring`.

- **General Ring** – The most stable, thoroughly tested version (default).
- **Limited Ring** – Includes newer updates with some testing but may contain unresolved bugs. Not recommended for production.
- **Preview Ring** – Provides early access to experimental features. Highly unstable and *not* recommended for production use.

## Developer Mode

Enabling **Dev Mode** provides additional debugging information. This option is found under `General > Dev > Show Dev Controls` in the **Settings Window**.

Features available in Dev Mode:
- **Console Window** – Displays logs and error reports.
- **Frame Rate Display** – Shows the application's current frame rate.

---

