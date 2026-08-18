# OTSM CRM Desktop — releases

This repository only hosts the **release binaries** of OTSM CRM Desktop (the One Two Shoot Media CRM desktop app for macOS and Windows). The source code lives in a private repository; nothing here is meant to be built.

Download the latest version from the [Releases page](https://github.com/nevets348/otsm-crm-desktop-releases/releases/latest):

- macOS (Apple silicon + Intel): `OTSM-CRM-x.y.z-universal.dmg`
- Windows 64-bit: `OTSM-CRM-Setup-x.y.z.exe` (installer, updates itself) or `OTSM-CRM-x.y.z.exe` (portable, notify-only)

The builds are unsigned — see the install notes shipped with each release (right-click → Open on macOS, or System Settings → Privacy & Security → Open Anyway on macOS 15+; "More info → Run anyway" on Windows SmartScreen). The `latest.yml` / `latest-mac.yml` files are the update feed the installed app reads.

The app signs in with your own OTSM Google account through Cloudflare Access; it contains no credentials of its own.
