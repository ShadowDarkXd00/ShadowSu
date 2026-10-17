# NOTICE — ShadowSU modifications

ShadowSU is a modified version of KernelSU (https://github.com/tiann/KernelSU),
Copyright (C) 2023–2025 tiann and contributors, licensed under the GNU General
Public License version 3 (see `LICENSE`).

Modifications made to produce ShadowSU (from KernelSU v3.3.1, manager build 32680):

1. Application name rebranded from "KernelSU" to "ShadowSU" across the UI
   (all bundled locales), theme names, notification/log labels and file-name
   prefixes shown in the UI.
2. Application ID changed from `me.weishu.kernelsu` to `com.shadowsu.magic`
   (manifest, dex classes, IPC descriptors, provider authorities, and the
   manager-identity markers inside the bundled ksud binary).
3. Launcher, adaptive, monochrome and splash icons replaced with new artwork.
4. Default Material You key color and splash/webview accent colors changed to
   a purple palette (user-selectable key colors are still available).
5. JNI bridge library renamed `libkernelsu.so` → `libshadowsu.so` with its
   exported JNI symbols renamed to the new package.
6. Update-check endpoint changed to this repository's GitHub releases.
7. Root engine (`libksud.so`, kernel-module handling, `/data/adb/ksu` layout)
   is functionally unchanged from upstream.

This program is distributed in the hope that it will be useful, but WITHOUT ANY
WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A
PARTICULAR PURPOSE. See the GNU General Public License for more details.
