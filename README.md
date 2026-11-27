# Zscaler Policy Wizard updates

> [!IMPORTANT]
> **Zscaler Policy Wizard is no longer supported.** 3.4.2 (November 2026) is its last version: no more updates or fixes.
> It's replaced by **zPolicy Wizard 4.0**, one app for macOS and Windows that does everything 3.4 does.
> On macOS 15 or later, [download zPolicy Wizard](https://github.com/ajawzero/zpolicy-wizard-updates/releases/latest/download/zPolicy-Wizard.dmg)
> ([releases](https://github.com/ajawzero/zpolicy-wizard-updates/releases)). It can copy this app's run records, Config Drift
> reads, POVs and POV templates. On macOS 13 or 14 you can keep using 3.4.2 as it is.

The update feed and downloads for Zscaler Policy Wizard, a Mac app that builds best-practice Zscaler configuration (ZIA, Private Access, Digital Experience, Client Connector and AI Guard), shows exactly what it would change before changing anything, and simulates what your policy does to traffic. This repository holds no source code.

- **Download the last version (3.4.2, unsupported):** [Zscaler-Policy-Wizard.dmg](https://github.com/ajawzero/zscaler-policy-wizard-mac-updates/releases/latest/download/Zscaler-Policy-Wizard.dmg). Open it and drag the app to Applications. It needs macOS 13 or later, on Apple silicon or Intel.
- `appcast.xml` (served at https://ajawzero.github.io/zscaler-policy-wizard-mac-updates/appcast.xml) is the signed list of versions that Zscaler Policy Wizard 1.0 and newer checks for updates. It stays up, so older versions are still offered 3.4.2, but it gets no new versions.
- Each release here has that version's DMG and its release notes. Each update is signed with Zscaler Policy Wizard's update key and with Developer ID, and notarized by Apple; the app checks both signatures before installing.
