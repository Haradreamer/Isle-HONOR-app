# Isle 2.4.0 — Native Magic Capsule & AOD improvements

**Release date:** 20 November 2026  
**APK:** `Isle-2.4.0-RELEASE.apk`  
**Package:** `dev.haradreamer.capsule` · **Version:** 2.4.0 (240)

Isle extends HONOR's native Magic Capsule with selected application notifications and ongoing events. This update focuses on reliability of the experimental idle capsule and a more consistent AOD/settings interface.

## What's new

- **Experimental always-visible idle capsule:** attempts to maintain an empty native Magic Capsule when there are no selected ongoing events, without drawing a replacement island overlay.
- **Recovery and transition logic:** improved recovery after notification removal, bounded retries, periodic checks of notification registration, and explicit idle/event state handling.
- **Eight AOD clock styles** in a single editor, with improved layout for varying screen sizes, font scaling and light/dark theme colors.
- **Settings usability:** retain scroll position after screen redraws; hide the text-size control that cannot affect HONOR's native capsule typography.
- **Stability:** guard delayed event updates against stale state changes; retain CN / Global compatibility introduced in 2.3.0.

## Important limitations

The permanent empty capsule is **experimental**. HONOR SystemUI controls whether and how the notification appears, and a successfully registered Android notification does **not** prove that the capsule is visible. The app cannot guarantee that every MagicOS build will resist swipe dismissal.

Firmware/device behavior should be verified on physical HONOR devices; CI tests and APK signature verification alone do not establish OEM compatibility.

## Download and update

Download **Isle-2.4.0-RELEASE.apk** from this version's release Assets, once the draft release is published. The APK is signed with the existing Isle release certificate and is intended for in-place upgrades of versions with the same package name and signer.

**APK SHA-256:** `2e8abaeb0bb93aaf83aff8ee3e6ce26775f96cad296002d226ee9830070c502f`

**Official 4PDA post:** https://4pda.to/forum/index.php?showtopic=1119615&view=findpost&p=145819882

Source code and signing keys are maintained separately and are not part of this downloads repository.
