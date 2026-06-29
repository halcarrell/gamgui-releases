# Changelog

## v2.0.14 — 2026-06-29

## GAM & Google Workspace Companion — v2.0.14

### What's new

- **Premium Files overhaul** — Newest-first lists, search on every tab, date filters on Google Sheets, scheduled-run hint (outputs often land in **Log Files**), load-more pagination, Drive folder + label columns.
- **Scheduled workflows UX** — Panel at top of Premium Workflows; last-run status, Run now, expandable log, deep-link to Premium Files with the right tab.
- **AI Assistant** — GAM parser rejects invalid field choices before a misleading live test; shows `expected_choices`; paste-to-validate without AI quota; workflow step selection, run selected, save-as-chain.
- **Custom Commands** — Tag folders, bulk tag rename, filters (All / Chains / From AI / Manual), favorites sidebar, G-Function grouping.
- **Google Sheets registry** — Workflow source, `tdtitle` labels, optional Drive folder display name from Configuration.
- **Product guardian** — Strategy reference, daily six-pillar review agent, always-on Cursor rule, automation hooks.
- **i18n** — Full locale sweep (10 languages) for Premium Files, AI, scheduler, and Custom Commands keys.
- **Marketing accuracy** — `PRODUCT_DESCRIPTIONS.md` clarifies Enterprise **5 concurrent seat licenses** (activation model, not shared workspace).

### Install / update

1. Download the DMG below (or let the app auto-update).
2. Open the DMG and drag the app to Applications.
3. Launch it. (Signed and notarized by Apple.)

Requires macOS 10.15+ and GAM 7+ installed separately. Not a Google product.

## v2.0.13 — 2026-06-26

## GAM7 Admin v2.0.13

### Installation
1. Download the DMG file below
2. Open the DMG
3. Drag the app to Applications
4. Launch the app

### Changes
See the main repository for detailed changelog.

---

**Note:** This repository only contains release files. Source code and documentation are in the private repository.

## v2.0.12 — 2026-06-23

## GAM7 Admin v2.0.12

### Installation
1. Download the DMG file below
2. Open the DMG
3. Drag the app to Applications
4. Launch the app

### Changes
See the main repository for detailed changelog.

---

**Note:** This repository only contains release files. Source code and documentation are in the private repository.

## v2.0.11 — 2026-06-19

## GAM & Google Workspace Companion — v2.0.11

### What's new
- **The app now speaks 10 languages.** Added **Hindi** and **Filipino**, joining English, Spanish, French, German, Japanese, Portuguese, Chinese, and Korean. The command catalog, Quick Actions, Premium Workflows, Help & Support, and the upgrade screen are all translated.
- **Fixed the "Pricing" link on the upgrade screen.** The "View full pricing & FAQ" link on the "Do more with GAM GUI" screen was broken — it now takes you straight to the pricing page.
- **More reliable Quick Actions.** Actions that legitimately return zero results (for example, an audit with nothing to report) no longer show a confusing error — they now clearly report **"No matching items found."** We also added a confirmation prompt before the **Forward Threads** action runs.

### Install / update
1. Download the DMG below (or let the app auto‑update).
2. Open the DMG and drag the app to Applications.
3. Launch it. (Signed and notarized by Apple.)

Requires macOS 10.15+ and GAM 7+ installed separately. Not a Google product.

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
