# Changelog

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
