# Changelog

## v2.0.10 — 2026-06-14

## GAM & Google Workspace Companion — v2.0.10

### What's new
- **See when you're signed in with Google.** The sidebar now shows a clear "✓ Signed in with Google · 15 saved commands" indicator, with a **Sign out** link, for free users who sign in. Previously there was no way to tell you were signed in (or to sign out).
- **Free Google sign-in unlocks more.** Signing in with Google on the free tier raises your saved Custom Commands from **5 → 15** — no purchase required. A gentle, dismissible nudge points this out (with a "Don't ask again" option).
- **More reliable sign-in detection.** Your signed-in status is now recognized even if local settings get cleared, so the bonus sticks.

### Install / update
1. Download the DMG below (or let the app auto‑update).
2. Open the DMG and drag the app to Applications.
3. Launch it. (Signed and notarized by Apple.)

Requires macOS 10.15+ and GAM 7+ installed separately. Not a Google product.

## v2.0.8 — 2026-06-06

## GAM Companion v2.0.8

### Fixed
- **License activation no longer blocked.** Beta/test keys (`GAM7-BETA-*`), master keys, and legitimately purchased keys could fail to activate with a "not found"/404 error. Activation now only performs provider seat-activation for paid providers (Lemon Squeezy / Gumroad); local and Marketplace licenses validate without being sent to a billing provider.

### Changed
- **OAuth sign-in requests identity-only scopes** (`userinfo.email`, `userinfo.profile`). All Google Workspace directory/report reads are performed by your own GAM installation under your own credentials — the app's Google sign-in is used only to identify the admin and validate licensing.

### Install / Update
- New install: download the DMG below, open it, and drag the app to Applications.
- Already on v2.0.7: the app updates itself — you'll be prompted to download and restart.

macOS universal (Apple Silicon + Intel), signed & notarized (Developer ID: Hal Carrell).

## v2.0.7 — 2026-05-30

- Auto-updater **Restart** now actually quits and installs the update.
- App reliably comes to the foreground when launched.
- Command Builder: the **Type DELETE to continue** confirmation input is now reachable.
- Google Sheets upload works with **keyless OAuth** (no service-account key needed); fixed a 404 caused by a stale Drive folder.
- The **How to connect Google Sheets** help now hides once Sheets is configured.
- **Open store** now links to gam-gui.com.
