<p align="center">
  <a href="../ru/CHANGELOG.md">🇷🇺 Русский</a> &nbsp;|&nbsp; <strong>🇬🇧 English</strong>
</p>

# Changelog

All notable **public** changes to the FACEIT UI extension. Presentation-only scope unless noted.

## 0.3.0 — Unreleased — 2026-09-02

### New interface
- The FACEIT UI panel has been updated, with settings easier to find in clear sections.
- Compact transparency controls are available for supported themes.
- The settings panel can be dragged to a more convenient place on the page.

### Backgrounds and GIFs
- GIF backgrounds can now repeat to fill the selected block without stretching small GIFs.

### Bug reports
- You can optionally attach a technical snapshot of your extension settings to a report.
- You can optionally attach a screenshot of the current FACEIT tab. The first submission can take up to 30 seconds.
- The report form is more compact and submission errors are easier to understand.

### Fixes
- Improved transparent backgrounds when opening profiles and nested pages.
- Fixed dragging of the settings panel.

## 0.2.1 — Unreleased — 2026-09-01

- Improved theme loading: reduced the noticeable bright flash on page reload; images now load more reliably when switching themes and presets.
- Improved preset import and export.
- Added a **GitHub** button to the extension panel.
- Updated the extension icon in the browser toolbar.
- Improved **Mono** theme readability when adjusting brightness.

## 0.2.0 — Unreleased — 2026-08-31

- Extension version bumped to **0.2.0**.
- **Bug Report** (opt-in): voluntary reports from the FACEIT UI panel with explicit consent; no automatic telemetry.
- Bug Report delivery via HTTPS intake (Cloudflare Worker → Render → email); no background service worker for intake.
- `host_permissions` for the production intake endpoint only (plus reserved `intake.faceit-ui.app`).
- Privacy Policy updated for Bug Report data flow (this repository).

## 0.1.0 — Release — 2026-08-29

- First packaged **Chrome MV3** release.
- Visual customization layer for `https://www.faceit.com/*` (themes, panel, local settings).
- Single permission: **`storage`** (`chrome.storage.local` for themes and preferences).
- Themes include Original, Soft Light, Graphite, Rainbow, and Custom; RU/EN panel language.
- Import / export of Custom theme settings.
- No background service worker; executable code shipped in the extension package only.
