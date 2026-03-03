# KMP + MapLibre Native + Compose Multiplatform Sample

This is a minimal Kotlin Multiplatform project generated with the JetBrains Wizard.

The project demonstrates:

- Kotlin Multiplatform (KMP)
- Compose Multiplatform
- iOS target with Xcode integration
- MapLibre Native (iOS)
- MapLibre Compose (Kotlin)

## Problem

After upgrading to **Kotlin 2.3.20-RC**, the iOS build fails in Xcode with:

```
Undefined symbol: OBJC_CLASS$_MLNScaleBar
Linker command failed with exit code 1
```

The project builds successfully with earlier Kotlin versions.

## Notes

- Project created using the official JetBrains KMP Wizard
- MapLibre Native added to iOS target
- MapLibre Compose added to shared module
- Kotlin version set to `2.3.20-RC`

---

This repository is intended purely as a minimal reproducible example.
