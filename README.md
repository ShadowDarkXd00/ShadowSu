<p align="center">
  <img src="assets/banner.png" width="100%" alt="ShadowSU — Advanced Android Root Solution" />
</p>

<h1 align="center">
  <img src="logo.png" width="56" height="56" alt="ShadowSU logo" /><br/>
  ⚡ ShadowSU
</h1>

<p align="center">
  <b>Advanced, systemless Android root — with a built-in module ecosystem.</b><br/>
  Root your device, supercharge it with modules, and manage everything from one clean purple app.
</p>

<p align="center">
  <a href="https://github.com/ShadowDarkXd00/ShadowSu/releases/latest"><img src="https://img.shields.io/github/v/release/ShadowDarkXd00/ShadowSu?style=for-the-badge&color=8B5CF6&label=Download" alt="Download" /></a>
  <img src="https://img.shields.io/badge/Android-11%2B-8B5CF6?style=for-the-badge&logo=android&logoColor=white" alt="Android 11+" />
  <img src="https://img.shields.io/badge/Architecture-arm64%20%7C%20x86_64-8B5CF6?style=for-the-badge" alt="Architectures" />
  <img src="https://img.shields.io/badge/UI-Purple%20Material%20You-8B5CF6?style=for-the-badge" alt="Purple UI" />
</p>

<p align="center">
  <a href="https://github.com/ShadowDarkXd00/ShadowSu/releases/latest">📥 <b>Download Latest Release</b></a>
  &nbsp;·&nbsp;
  <a href="#-installation">🛠 Installation</a>
  &nbsp;·&nbsp;
  <a href="#-features">✨ Features</a>
</p>

---

## 🚀 What is ShadowSU?

**ShadowSU** is a complete Android root solution built on a **systemless** architecture — it grants root access *without touching your system partition*, so OTA updates, banking apps, and your device integrity stay safe(r).

Think: **one app = root manager + module engine + superuser firewall + WebUI platform.**

> 🔐 Superuser access. 📦 Powerful modules. 🌐 Web interfaces. 🛒 Online store. ⚡ Zero system modification.

---

## ✨ Features

<table>
<tr>
<td width="50%">

### 🔐 Complete Root Control
Grant or deny **root per-app**, with logging, notification prompts, and per-app UID rules. You decide exactly what gets root.

</td>
<td width="50%">

### 📦 Powerful Module System
Install systemless modules — **like Magisk modules** — to customize anything: theming, performance, audio, UI tweaks. Flash, update, remove, all in-app.

</td>
</tr>
<tr>
<td width="50%">

### 🌐 WebUI Modules
Modules can ship **interactive web dashboards** rendered right inside the app — configure your modules with modern tap-friendly interfaces.

</td>
<td width="50%">

### 🛒 Online Module Store
Browse and install modules from the **integrated online repository** — no file hunting, no forums. Tap → install → done.

</td>
</tr>
<tr>
<td width="50%">

### 🔄 Automatic Module Updates
Modules can self-update in the background via their update channel — always on the **latest version** without lifting a finger.

</td>
<td width="50%">

### 👤 App Profiles
Per-app profiles: configure root access, namespaces, and mount settings **granularly** for every installed application.

</td>
</tr>
<tr>
<td width="50%">

### 🧩 LKM Mode Support
Works as a **loadable kernel module** on supported kernels — root without patching the boot image when the kernel allows it.

</td>
<td width="50%">

### ⚡ Systemless by Design
Nothing on `/system` is modified. Uninstall cleanly anytime. **Safetynet/Play Integrity friendlier** than legacy root methods.

</td>
</tr>
</table>

<div align="center">

### 🎨 And a beautiful, modern purple UI
Material You design · Dark AMOLED theme · Smooth animations · Clean manager dashboard

</div>

---

## 🛠 Installation

### Step 1 — Get the app
Download **`ShadowSU.apk`** from the [**latest release**](https://github.com/ShadowDarkXd00/ShadowSu/releases/latest).

### Step 2 — Install the manager
```
Settings → allow "Install unknown apps" for your browser/file manager → open ShadowSU.apk → Install
```

### Step 3 — Activate root
| Your device | Method |
|---|---|
| Kernel with module support | Tap **Install** in the app → flash the module from recovery / kernel module loader |
| Other rooted devices | Install the app module via your kernel's module system |

### Step 4 — Enjoy
Open ShadowSU → manage **superuser requests**, install modules from the **store**, and configure **WebUI** dashboards. 🎉

---

## 📱 Requirements

| | |
|---|---|
| 🤖 Android | 11.0+ (recommended) |
| 🏗 CPU | `arm64-v8a` · `x86_64` · `riscv64` |
| 💾 Size | ~18 MB |
| 🔓 Bootloader | Unlocked (for kernel-level install) |

---

## 📦 What's Inside

| Component | Description |
|---|---|
| 📱 **Manager App** | Purple-themed control center — root rules, modules, settings |
| ⚙️ **Core Daemon** | Systemless root engine handling su requests & module mounts |
| 📦 **Module Engine** | Installs, mounts, and updates systemless modules |
| 🌐 **WebUI Platform** | Renders module dashboards with in-app WebView |
| 🛒 **Online Store** | One-tap module discovery & install |
| 🔐 **su Tool** | On-device superuser binary for apps & terminal |

---

## 🧰 For Developers

- **App package:** `com.shadowsu.magic`
- **Root daemon:** `libshadowsu.so` / `libksud.so` — module & su backend
- **WebUI:** Built-in WebView platform with purple theme injection
- **Releases:** tagged `vX.Y` — CI automatically attaches `ShadowSU.apk` to every release

---

## 💜 Why ShadowSU?

- ✅ **Systemless** — survives OTA, reversible, clean
- ✅ **All-in-one** — root + modules + store + WebUI, zero extra tools
- ✅ **Modern** — Material You purple design, not 2016-era dialogs
- ✅ **Powerful** — per-app root, profiles, LKM mode, auto-updates
- ✅ **Simple** — tap-to-install modules from the store

---

<div align="center">
<br/>
<img src="logo.png" width="72" height="72" alt="ShadowSU" />
<br/><br/>

**ShadowSU** — *Rule your Android. Quietly.* 🌑⚡

<a href="https://github.com/ShadowDarkXd00/ShadowSu/releases/latest"><img src="https://img.shields.io/github/v/release/ShadowDarkXd00/ShadowSu?style=for-the-badge&color=8B5CF6&label=⬇%20Download%20ShadowSU" alt="Download" /></a>

<br/><br/>
<sub>Built on open-source foundations · See <a href="NOTICE.md">NOTICE.md</a> for attributions</sub>
</div>
