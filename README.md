# Isle for HONOR

**Isle brings supported app events and notifications into HONOR's Magic Capsule.**

An independent Android project by **Haradreamer**, designed primarily for HONOR smartphones running MagicOS. Isle can surface supported notification events, message updates, navigation, calls, timers, alarms and downloads in a compact capsule-like experience. Available features depend on the phone, system version, and permissions.

## Download

**Latest prepared production build:** Isle **2.4.0** (20 November 2026).

➡️ **[GitHub Releases](https://github.com/Haradreamer/Isle-HONOR-app/releases)**

The signed **Isle-2.4.0-RELEASE.apk** (SHA-256: `2e8abaeb0bb93aaf83aff8ee3e6ce26775f96cad296002d226ee9830070c502f`) has been uploaded to a **draft GitHub release**. It will become publicly downloadable once the `v2.4.0` release is published. Until then, use the current published release.

> This public repository is for official downloads, documentation and issues. Development sources and private signing credentials are stored separately.

## What's new in 2.4.0

- Experimental persistent native idle capsule with bounded recovery after notification removal, periodic registration checks and more reliable idle/event transitions.
- Eight AOD clock styles through a unified editor; improved adaptive layout and dark/light theme appearance.
- Keep settings scroll position and remove the text-size slider that could not affect native HONOR SystemUI capsules.
- Preserve CN / Global detection and event handling introduced in Isle 2.3.0.

**Note:** HONOR SystemUI controls native capsule visibility and swipe behavior. The always-on empty capsule remains experimental and requires device testing.

[Detailed 2.4.0 release notes](RELEASE_NOTES_2.4.0.md)

## Features

- Magic Capsule integration for supported notification events.
- Message and ongoing-event handling with event-specific presentation.
- Navigation, calls, alarms, timers and download-progress scenarios (availability varies by firmware and source app).
- App selection, presentation settings and animations.
- Optional/experimental edge-lighting and universal island features; their availability varies by release and device.
- Eight interface languages: Russian, English, Simplified Chinese, Spanish, Brazilian Portuguese, Arabic, Turkish and Indonesian, plus follow-system selection.

## Compatibility

Isle is primarily developed for HONOR MagicOS devices. **The primary development/test phone is HONOR Magic9 Pro Max (WKL-AN20), MagicOS 11.** Other HONOR models and firmware versions need independent testing.

Magic Capsule is controlled in part by HONOR system components, so behavior cannot be guaranteed on every device or for every notification source. This app is not affiliated with HONOR or HUAWEI.

## Installation

1. Download the **official signed APK** from a published GitHub Release.
2. Install it and open Isle.
3. Follow the on-screen setup: grant the permissions needed for your selected features (for example notification access, notification posting, display over other apps, or optional services).
4. Select the apps/events to monitor and adjust your preferred appearance.
5. Follow the app's startup/battery guidance if MagicOS stops background operation.

**Updating:** In-place installation is possible only when the existing installation uses the same package name **and signing certificate**. Older variants signed with a different key may need manual removal, which can delete app data. Back up your settings where supported.

## Feedback and device testing

Please open an [Issue](https://github.com/Haradreamer/Isle-HONOR-app/issues) with your phone model, country/firmware version, MagicOS/Android version, Isle version, steps to reproduce, and relevant screenshots. Do not include passwords, private messages or other sensitive information.

## Support development

Isle is independently developed and distributed free of charge. Optional voluntary support: [Boosty — Haradreamer](https://boosty.to/haradreamer).

[Russian documentation / Документация на русском](README.ru.md) · [Changelog](CHANGELOG.md)
