<p align="center">
  <a href="../ru/PRIVACY.md">🇷🇺 Русский</a> &nbsp;|&nbsp; <strong>🇬🇧 English</strong>
</p>

# FACEIT UI — Privacy Policy

**Last updated: September 4, 2026**

FACEIT UI is a browser extension that provides a presentation and customization layer for [faceit.com](https://www.faceit.com). This policy describes what data the extension handles.

## Local use (not transmitted)

- Theme and panel settings, custom theme data, media library, and presets are stored locally in your browser (`chrome.storage.local`).
- FACEIT UI does **not** run automatic telemetry or background data collection.
- Visual changes to FACEIT pages are applied locally. The extension does **not** automatically send page HTML/DOM, screenshots, cookies, FACEIT authentication or session data, full contents of extension storage, or your browsing history.

## Bug Report (voluntary, opt-in)

The **Bug Report** feature in the FACEIT UI panel is the only way the extension sends data off your device.

**When it is sent:** only after you provide a required description, check the consent box, and click **Send**.

**Purpose:** bug reporting and extension support.

### Base report (always included on submit)

- Problem **description** (required)
- **Reproduction steps** (optional)
- **Contact** information (optional; for example email or Telegram for a reply)
- Current page **URL** at the time of submission
- Browser **user-agent**
- Extension **version**, panel **locale**, **theme**, bug **category**, and submission **timestamp**

### Optional attachments (only if you check the box)

All attachments are **optional**. You can leave them unchecked — that is how you opt out. None of the items below are added to a report unless you separately check the corresponding box.

- **Technical snapshot** — limited technical context: version, locale, theme, current URL, viewport, panel state, and settings **without** media images, cookies, or tokens.
- **Screenshot** — a capture of the visible faceit.com tab and the FACEIT UI panel. It may show your nickname, avatar, and on-screen page content.
- **Selected elements list** — numbered technical metadata for elements you chose yourself (selector / tag / class / geometry / URL) for diagnostics. This is **not** full HTML/DOM, **not** page text, and **not** input field values.

### What the extension does not send automatically

- Browser or FACEIT cookies
- Passwords, session tokens, or payment data
- Messages
- Browsing history (only the current page URL is sent)
- Full contents of extension storage (themes, imports, media, etc.)

Before sending, the form asks you to confirm that you did not include sensitive data in the description or contact fields.

## How Bug Reports are processed

Submitted reports are transmitted over HTTPS through:

1. **Cloudflare Worker** — `https://faceit-ui-intake.actually-question.workers.dev`
2. **Render** — intake backend (`https://faceit-ui-intake.onrender.com`)
3. **Resend** — email delivery to the extension developer

Reports are delivered by email for manual review. FACEIT UI does not sell user data. Data from Bug Reports is used for support and bug fixing.

## Donate link

The **Donate** button opens an external website in your browser. FACEIT UI does not process or transmit payment information.

## Remote code

FACEIT UI does not download or execute remote JavaScript. Executable code is included in the published extension package (Manifest V3).

## Changes

This policy may be updated when FACEIT UI functionality changes. The **Last updated** date above reflects the latest revision.

## Contact

For questions about this policy or FACEIT UI, use the support or contact method on the extension store listing, or submit a Bug Report from the extension panel.
