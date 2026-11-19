# Isle release history

## 2.3.0 — 2026-11-19
- Release branch: `release/isle-2.3.0` in the private development repository.
- Release build checks passed: structural checks, regression tests, translation audit, Android lint and minified release APK assembly.
- Application identity: `dev.haradreamer.capsule`, `versionCode=230`, `versionName=2.3.0`.
- Added CN / Global HONOR SystemUI variant detection at startup, using installed system package location rather than locale or SIM country.
- Preserved legacy native Magic Capsule notification handling for CN and unknown variants.
- Added experimental Global-specific notification content improvements and fallback tap behavior.
- **Public download status:** 2.3.0 signed APK is not yet attached to this public GitHub Releases page; the 2.2.5 signed APK remains available.
- Device behavior may differ by MagicOS version and model.


## 2.2.5 — 2026-11-19
- Production branch: `release/isle-2.2.5` in the private development repository.
- CI verification succeeded: structural verification, regression tests, translation audit, Android lint and minimized APK assembly.
- Target application identity: `dev.haradreamer.capsule`, `versionCode=225`, `versionName=2.2.5`.
- **Important:** CI artifact is **unsigned**. A signed release APK with the existing Isle certificate must be supplied by the owner before public distribution.

For a public changelog of behavior changes, use only information confirmed by the corresponding signed release notes; experimental and research builds are not included here.

## Earlier public versions

Older versions of Isle were distributed separately via the developer's community posts. Signature compatibility may vary between older version families.
