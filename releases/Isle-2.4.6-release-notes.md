# Isle v2.4.6 — Magic Capsule notification synchronization (private-device verified)

Signed release APK: `Isle-2.4.6-PRIVATE-SIGNED.apk`  
Package: `dev.haradreamer.capsule`  
Version: `2.4.6` (`versionCode 246`)

## Changes

- Restored source-notification dismissal handling from Isle v2.1.1: when Android reports a user dismissal of an Isle mirror, Isle attempts to dismiss the matching clearable source notification.
- Added diagnostic logging (`IsleSwipeTrace`) to trace removal events, reasons, mirror lookup, source cancellation requests, and a delayed check of whether the original notification remains active.
- Added recognition of both Yandex Navigator (`ru.yandex.yandexnavi`) and Yandex Maps (`ru.yandex.yandexmaps`) as navigation notification sources.
- Retained the existing AOD and other v2.4.5 features.
- Increased `versionCode` to 246 for in-place installation over v2.4.5 with the original Isle signing key.

## Validation

- Android release build, regression tests, lint, and localization audit completed successfully.
- Original Isle signing certificate was used for the private-device test.
- Notification swipe behavior was reported working by the developer on HONOR Magic 9 Pro Max.
- Yandex Navigator turn-arrow display has not yet been confirmed by an additional device test.

## Diagnostics

To capture traces after a swipe:

```powershell
adb logcat -d -s IsleSwipeTrace:I IsleDismiss:I > swipe-246.txt
```

## Publication

The owner must attach the *signed* production APK `Isle-2.4.6-PRIVATE-SIGNED.apk` to the GitHub Release tagged `v2.4.6`; do not attach an unsigned or debug APK. Never publish the keystore or recovery materials.
