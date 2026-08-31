<p align="center">
  <a href="CHANGELOG.md">🇷🇺 Русский</a> &nbsp;|&nbsp; <strong>🇬🇧 English</strong>
</p>

# Changelog

All notable **public** changes to the FACEIT UI extension. Presentation-only scope unless noted.

## 0.2.0 — 2026-08-31

- Extension version bumped to **0.2.0**.
- **Bug Report** (opt-in): voluntary reports from the FACEIT UI panel with explicit consent; no automatic telemetry.
- Bug Report delivery via HTTPS intake (Cloudflare Worker → Render → email); no background service worker for intake.
- `host_permissions` for the production intake endpoint only (plus reserved `intake.faceit-ui.app`).
- Privacy Policy updated for Bug Report data flow (this repository).

## 0.1.0 — 2026-08-29

- First packaged **Chrome MV3** release.
- Visual customization layer for `https://www.faceit.com/*` (themes, panel, local settings).
- Single permission: **`storage`** (`chrome.storage.local` for themes and preferences).
- Themes include Original, Soft Light, Graphite, Rainbow, and Custom; RU/EN panel language.
- Import / export of Custom theme settings.
- No background service worker; executable code shipped in the extension package only.
