<p align="center">
  <a href="PRIVACY.md">🇷🇺 Русский</a> &nbsp;|&nbsp; <strong>🇬🇧 English</strong>
</p>

# FACEIT UI — Privacy Policy

**Last updated: August 31, 2026**

FACEIT UI is a browser extension that provides a presentation and customization layer for [faceit.com](https://www.faceit.com). This policy describes what data the extension handles.

## Local use (not transmitted)

- Theme and panel settings, custom theme data, media library, and presets are stored locally in your browser (`chrome.storage.local`).
- FACEIT UI does **not** run automatic telemetry or background data collection.
- Visual changes to FACEIT pages are applied locally. The extension does not automatically send page HTML/DOM, screenshots, cookies, FACEIT authentication or session data, extension storage contents, or your browsing history.

## Bug Report (voluntary, opt-in)

The **Bug Report** feature in the FACEIT UI panel is the only way the extension sends data off your device.

**When it is sent:** only after you fill in the form, check the consent box, and click **Send**.

**Purpose:** bug reporting and extension support.

**Data you may submit:**

- Problem **description** (required)
- **Reproduction steps** (optional)
- **Contact** information (optional; for example email or Telegram for a reply)
- Current **FACEIT page URL** at the time of submission
- Browser **user-agent**
- Technical context: extension **version**, panel **locale**, active theme **name**, bug **category**, and submission **timestamp**

**Not included in Bug Report:**

- Browser or FACEIT cookies
- FACEIT login, password, or session tokens
- Contents of extension storage (themes, settings, imports, media)
- Browsing history (only the current page URL is sent when you submit)
- Page HTML/DOM or screenshots

Before sending, the form asks you to confirm that you did not include sensitive data.

## How Bug Reports are processed

Submitted reports are transmitted over HTTPS through:

1. **Cloudflare Worker** — `https://faceit-ui-intake.actually-question.workers.dev`
2. **Render** — intake backend (`https://faceit-ui-intake.onrender.com`)
3. **Resend** — email delivery to the extension developer

Reports are delivered by email for manual review. FACEIT UI does not sell user data. Data from Bug Reports is used only for support and bug fixing.

## Donate link

The **Donate** button opens an external website in your browser. FACEIT UI does not process or transmit payment information.

## Remote code

FACEIT UI does not download or execute remote JavaScript. Executable code is included in the published extension package (Manifest V3).

## Changes

This policy may be updated when FACEIT UI functionality changes. The **Last updated** date above reflects the latest revision.

## Contact

For questions about this policy or FACEIT UI, use the support or contact method on the extension store listing, or submit a Bug Report from the extension panel.
