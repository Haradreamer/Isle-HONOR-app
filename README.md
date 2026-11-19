# Isle for HONOR

**Isle brings supported app events and notifications into HONOR's Magic Capsule.**

An independent Android project by **Haradreamer**, designed primarily for HONOR smartphones running MagicOS. Isle can surface supported notification events, message updates, navigation, calls, timers, alarms and downloads in a compact capsule-like experience. Available features depend on the phone, system version, and permissions.

## Download

**Latest production version prepared:** Isle **2.3.0** (19 November 2026).

➡️ **[GitHub Releases](https://github.com/Haradreamer/Isle-HONOR-app/releases)**

**Downloads:** The signed **2.2.5** APK is available in [GitHub Releases](https://github.com/Haradreamer/Isle-HONOR-app/releases/tag/v2.2.5). **2.3.0** has been prepared and signed, but its public GitHub Release APK has **not yet been attached**. Until the 2.3.0 APK appears under Releases, use the published 2.2.5 package or the developer's official community links. Do not install unsigned artifacts or third-party repacks.

> This public repository is the official **download, documentation and issue-tracking page**. Development source code and private signing keys are kept in a separate private repository. No private credentials will be published here.

## What's new in 2.3.0

- Detect HONOR **CN / Global** SystemUI variant at application startup (not based on the device language or SIM country).
- Keep the existing CN Magic Capsule notification behavior.
- Apply a separate notification-content compatibility profile on Global firmware, including filled secondary text, adjusted large-icon handling and a fallback tap action when no source action exists.
- Retain the existing event handling, notification permissions and privacy behavior.

The Global adjustments are based on comparison of MagicOS 11 CN and Global system components. Compatibility varies by device and firmware; reports from additional devices are welcome.

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
