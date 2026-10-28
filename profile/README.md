<p align="center">
  <img src="https://raw.githubusercontent.com/net-merge/net-merge/main/docs/icon.png" width="96" alt="net-merge icon">
</p>

<h1 align="center">net-merge</h1>

<p align="center">
  <strong>Use all your internet connections at the same time.</strong><br>
  Wi-Fi, Ethernet, mobile data and phone hotspots share the load, so downloads, games and browsers get the speed of every connection added up.
</p>

<p align="center">
  <a href="https://net-merge.org">Website</a> ·
  <a href="https://github.com/net-merge/net-merge/releases/latest">Download</a> ·
  <a href="https://github.com/net-merge/net-merge#troubleshooting">Troubleshooting</a> ·
  <a href="https://github.com/net-merge/net-merge/issues/new/choose">Report a problem</a>
</p>

<p align="center">
  <a href="https://github.com/net-merge/net-merge/stargazers"><img src="https://img.shields.io/github/stars/net-merge/net-merge?style=flat" alt="Stars"></a>
  <a href="https://github.com/net-merge/net-merge/releases"><img src="https://img.shields.io/github/v/release/net-merge/net-merge" alt="Latest release"></a>
  <a href="https://github.com/net-merge/net-merge/releases"><img src="https://img.shields.io/github/downloads/net-merge/net-merge/total" alt="Downloads"></a>
  <a href="https://github.com/net-merge/net-merge/blob/main/LICENSE"><img src="https://img.shields.io/github/license/net-merge/net-merge" alt="MIT license"></a>
  <img src="https://img.shields.io/badge/platforms-Windows%20%7C%20macOS%20%7C%20Linux%20%7C%20Android-blue" alt="Windows, macOS, Linux and Android">
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/net-merge/net-merge/main/docs/demo.gif" width="600" alt="Speed test on a Mac with Wi-Fi and an Android phone: both connections carry traffic and the download reaches about 326 Mbit/s">
  <br>
  <sub>A Mac with Wi-Fi and an Android phone, both working at once.</sub>
</p>

A real test with Wi-Fi, an Android USB tether and an iPhone hotspot, 9 downloads at once, gave **232 to 303 Mbit/s**. The fastest connection alone gave about 121 Mbit/s.

It is free and open source (MIT). There is no account, no server and no VPN.

## Install

**Windows** (PowerShell)

```powershell
irm https://raw.githubusercontent.com/net-merge/net-merge/main/install.ps1 | iex
```

**macOS and Linux**

```sh
curl -fsSL https://raw.githubusercontent.com/net-merge/net-merge/main/install.sh | sh
```

**Android**: download the APK from the [latest release](https://github.com/net-merge/android/releases/latest) and open it.

## What is here

- **[net-merge](https://github.com/net-merge/net-merge)**: the app for Windows, macOS and Linux
- **[android](https://github.com/net-merge/android)**: the Android app
- **[website](https://github.com/net-merge/website)**: the source of [net-merge.org](https://net-merge.org), and the Linux package server
- **[homebrew-tap](https://github.com/net-merge/homebrew-tap)**: `brew install net-merge/tap/net-merge`

Want to help? Read [CONTRIBUTING](https://github.com/net-merge/net-merge/blob/main/CONTRIBUTING.md). Questions: hello@net-merge.org.
