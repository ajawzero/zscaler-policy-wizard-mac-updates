# Zscaler Policy Wizard updates

The update feed and downloads for Zscaler Policy Wizard, a Mac app that builds best-practice Zscaler configuration (ZIA, Private Access, Digital Experience, Client Connector and AI Guard), shows exactly what it would change before changing anything, and simulates what your policy does to traffic. This repository holds no source code.

- **Download the latest version:** [Zscaler-Policy-Wizard.dmg](https://github.com/ajawzero/zscaler-policy-wizard-mac-updates/releases/latest/download/Zscaler-Policy-Wizard.dmg). Open it and drag the app to Applications. It needs macOS 13 or later, on Apple silicon or Intel.
- `appcast.xml` (served at https://ajawzero.github.io/zscaler-policy-wizard-mac-updates/appcast.xml) is the signed list of versions that Zscaler Policy Wizard 1.0 and newer checks for updates.
- Each release here has that version's DMG and its release notes. Each update is signed with Zscaler Policy Wizard's update key and with Developer ID, and notarized by Apple; the app checks both signatures before installing.
