# ShadowSU

ShadowSU is a full rebrand of **KernelSU v3.3.1 (build 32680)** — same root engine,
new identity: new name, new package (`com.shadowsu.magic`), new purple UI, new icons.

## What's in this repo

| File | Description |
|---|---|
| `ShadowSU.apk` | The rebranded, signed, installable manager APK |
| `KernelSU_v3.3.1_32680-release.apk` | Original upstream APK used as the base |
| `LICENSE` | GPL-3.0 (KernelSU's license — must be preserved) |
| `NOTICE.md` | Attribution and list of modifications |

## Rebrand summary (v1)

- **Name**: KernelSU → **ShadowSU** (app label, all ~40 locales, themes, strings)
- **Package**: `me.weishu.kernelsu` → `com.shadowsu.magic`
- **Theme**: purple / violet Material You — default key color forced to `#8B5CF6`,
  splash screen & webview accent ramp recolored purple; the in-app color picker
  (Settings → Key color) still works and can override the default
- **Icons**: new launcher icon (purple, "S" mark), new adaptive/monochrome/splash art
- **Native bridge**: `libkernelsu.so` → `libshadowsu.so` with all JNI symbols renamed
- **Root engine**: `libksud.so` (the KernelSU userspace daemon that actually provides
  root, modules and the LKM installer) is kept functionally intact — only the two
  manager-identity marker strings were updated so it binds to the renamed app
- **Update checker**: now points at `ShadowDarkXd00/ShadowSu` releases

## Install

```bash
adb install -r ShadowSU.apk
```

Requires a device with a KernelSU-capable (GKI) kernel or KernelSU LKM support —
the root engine is unchanged from KernelSU v3.3.1.

## License & attribution

KernelSU is Copyright (C) 2023–2025 tiann and contributors, licensed under
**GPL-3.0**. ShadowSU is a modified derivative. Per the GPL, this distribution
keeps the license text and states the modifications (see `NOTICE.md`). Source
for this build is the `main` branch of this repository.

Upstream project: <https://github.com/tiann/KernelSU>
