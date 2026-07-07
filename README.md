# AIDCEC Attendance — Privacy Policy

This repository hosts the public privacy policy for the **AIDCEC Attendance** mobile app and the
EdUHK AI Education Platform, served as a static site via GitHub Pages.

**Live URL:** https://eduhk-aidcec.github.io/aidcec-attendance-privacy/

Use this URL in:

- Google Play Console → App content → Privacy policy
- App Store Connect → App Privacy → Privacy Policy URL

## Structure

- [`index.html`](index.html) — bilingual policy (English + 繁體中文), aligned with the Hong Kong
  Personal Data (Privacy) Ordinance (Cap. 486).
- [`styles.css`](styles.css) — page styling, no build step required.

## Updating the policy

1. Edit the English `<article id="en">` section and its Traditional Chinese mirror in
   `<article id="zh">` together, so both languages stay consistent.
2. Update the "Last updated" date in the `<header class="hero">` block (both the English and
   Chinese date strings).
3. Commit and push to `main` — GitHub Pages redeploys automatically within a couple of minutes.

## Enabling GitHub Pages (one-time setup)

Repo → **Settings** → **Pages** → Source: **Deploy from branch** → Branch: `main`, folder: `/ (root)` → **Save**.

## Source of truth

The content originates from the platform monorepo's draft at `web/src/app/privacy/page.tsx`
(EdUHK AI Education Platform), extended here with Hong Kong PDPO-specific sections (collection
statement, cross-border transfer, access/correction rights, PCPD complaints) and a Traditional
Chinese translation for Hong Kong app store submissions.
