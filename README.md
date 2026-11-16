# Devnet dVPN

**The peer-to-peer VPN on Solana devnet.** Downloads for Windows, macOS, Linux and Android.

Devnet dVPN is a peer-to-peer VPN on Solana devnet. You pay the server operator directly; there are no accounts and no company servers in between.

> **Pre-release for testing.** It runs on Solana **devnet** with test tokens that have no real value.

**Current version: 0.3.0 rc.4** · 15 languages + English

## Repositories

Each system has its own repository with its releases, release notes and checksums.

| System | Repository | All releases |
|---|---|---|
| Windows | [sentinel-solana-dvpn-windows](https://github.com/Sentinel-Bluebuilder/sentinel-solana-dvpn-windows) | [Releases](https://github.com/Sentinel-Bluebuilder/sentinel-solana-dvpn-windows/releases) |
| macOS | [sentinel-solana-dvpn-macos](https://github.com/Sentinel-Bluebuilder/sentinel-solana-dvpn-macos) | [Releases](https://github.com/Sentinel-Bluebuilder/sentinel-solana-dvpn-macos/releases) |
| Linux | [sentinel-solana-dvpn-linux](https://github.com/Sentinel-Bluebuilder/sentinel-solana-dvpn-linux) | [Releases](https://github.com/Sentinel-Bluebuilder/sentinel-solana-dvpn-linux/releases) |
| Android | [sentinel-solana-dvpn-android](https://github.com/Sentinel-Bluebuilder/sentinel-solana-dvpn-android) | [Releases](https://github.com/Sentinel-Bluebuilder/sentinel-solana-dvpn-android/releases) |

## Download

### Windows

Windows 10 or 11, 64-bit.

- [**Download the installer (.exe)**](https://github.com/Sentinel-Bluebuilder/sentinel-solana-dvpn-windows/releases/download/v0.3.0-rc4/Devnet-dVPN-Setup-0.3.0-rc.4-x64.exe)
- [Release notes and checksums](https://github.com/Sentinel-Bluebuilder/sentinel-solana-dvpn-windows/releases/tag/v0.3.0-rc4)

### macOS

Intel and Apple Silicon.

- [**Download from the macOS releases**](https://github.com/Sentinel-Bluebuilder/sentinel-solana-dvpn-macos/releases) (pick `arm64` for Apple Silicon, `x64` for Intel)

### Linux

| Distribution | x64 | ARM64 |
|---|---|---|
| Ubuntu / Debian | [.deb](https://github.com/Sentinel-Bluebuilder/sentinel-solana-dvpn-linux/releases/download/v0.3.0-rc4/devnet-dvpn_0.3.0-rc.4_amd64.deb) | [.deb](https://github.com/Sentinel-Bluebuilder/sentinel-solana-dvpn-linux/releases/download/v0.3.0-rc4/devnet-dvpn_0.3.0-rc.4_arm64.deb) |
| Fedora / RHEL | [.rpm](https://github.com/Sentinel-Bluebuilder/sentinel-solana-dvpn-linux/releases/download/v0.3.0-rc4/devnet-dvpn-0.3.0-rc.4.x86_64.rpm) | [.rpm](https://github.com/Sentinel-Bluebuilder/sentinel-solana-dvpn-linux/releases/download/v0.3.0-rc4/devnet-dvpn-0.3.0-rc.4.aarch64.rpm) |
| Arch | [.pkg.tar.zst](https://github.com/Sentinel-Bluebuilder/sentinel-solana-dvpn-linux/releases/download/v0.3.0-rc4/devnet-dvpn-0.3.0-rc.4-x64.pkg.tar.zst) | [.pkg.tar.zst](https://github.com/Sentinel-Bluebuilder/sentinel-solana-dvpn-linux/releases/download/v0.3.0-rc4/devnet-dvpn-0.3.0-rc.4-aarch64.pkg.tar.zst) |
| Any distribution | [AppImage](https://github.com/Sentinel-Bluebuilder/sentinel-solana-dvpn-linux/releases/download/v0.3.0-rc4/Devnet-dVPN-0.3.0-rc.4-x86_64.AppImage) | [AppImage](https://github.com/Sentinel-Bluebuilder/sentinel-solana-dvpn-linux/releases/download/v0.3.0-rc4/Devnet-dVPN-0.3.0-rc.4-arm64.AppImage) |

- [Release notes and checksums](https://github.com/Sentinel-Bluebuilder/sentinel-solana-dvpn-linux/releases/tag/v0.3.0-rc4)

### Android

Android 8 or newer.

- [**Download the APK from the Android releases**](https://github.com/Sentinel-Bluebuilder/sentinel-solana-dvpn-android/releases)

Each release page has a `SHA256SUMS` file to check your download.

## Built from components anyone can use

Devnet dVPN is more than one app. Each of its features is a building block, made to be used in other people's apps too.

Sentinel's goal is a library of components that are tried and tested end to end: connecting, paying, the kill switch, split tunnelling, leak protection, refunds, server testing, AI agent control, languages and the rest. Each one is proven in a real app on four systems before anyone else relies on it.

The aim is that anyone can build their own VPN app by picking the features they want, the way you would pick parts from a catalogue, and get a working app end to end without rebuilding any of it from scratch:

- **Pick the features.** A privacy browser might take connect, the kill switch and leak protection. An AI tool might take only the agent commands.
- **Get them already tested.** Each component has been used and tested on Windows, macOS, Linux and Android in this app.
- **Keep it peer-to-peer.** Every app built this way talks to the servers and the blockchain directly, with no company server in between and no API keys to request.

This app is where those components are built and proven first. The table below shows each feature and the GitHub repository it comes from.

## Features

Each feature links to how it works and to the GitHub repository it comes from. Features built into the app itself link to the app's repositories: [Windows](https://github.com/Sentinel-Bluebuilder/sentinel-solana-dvpn-windows) · [macOS](https://github.com/Sentinel-Bluebuilder/sentinel-solana-dvpn-macos) · [Linux](https://github.com/Sentinel-Bluebuilder/sentinel-solana-dvpn-linux) · [Android](https://github.com/Sentinel-Bluebuilder/sentinel-solana-dvpn-android).

| Feature | GitHub repository |
|---|---|
| [6-protocol VPN](FEATURES.md#6-protocol-vpn) | [WireGuard](https://github.com/WireGuard/wireguard-go) · [OpenVPN](https://github.com/OpenVPN/openvpn) · [V2Ray](https://github.com/v2fly/v2ray-core) · [Xray](https://github.com/XTLS/Xray-core) · [Hysteria2](https://github.com/HyNetworks/hysteria) · [AmneziaWG](https://github.com/amnezia-vpn/amneziawg-go) |
| [Anti-censorship protocols](FEATURES.md#anti-censorship-protocols) | [V2Ray](https://github.com/v2fly/v2ray-core) · [Xray](https://github.com/XTLS/Xray-core) · [Hysteria2](https://github.com/HyNetworks/hysteria) · [AmneziaWG](https://github.com/amnezia-vpn/amneziawg-go) |
| [Peer-to-peer, no accounts](FEATURES.md#peer-to-peer-no-accounts) | [sentinel-official/sentinel-solana](https://github.com/sentinel-official/sentinel-solana) |
| [Pay per GB or per hour](FEATURES.md#pay-per-gb-or-per-hour) | [sentinel-official/sentinel-solana](https://github.com/sentinel-official/sentinel-solana) |
| [Claim refunds](FEATURES.md#claim-refunds) | [sentinel-official/sentinel-solana](https://github.com/sentinel-official/sentinel-solana) |
| [Node speed test](FEATURES.md#node-test) | [sentinel-official/sentinel-solana](https://github.com/sentinel-official/sentinel-solana) |
| [Built-in Solana wallet](FEATURES.md#built-in-solana-wallet) | [Solana (Agave)](https://github.com/anza-xyz/agave) · [Solana web3.js](https://github.com/solana-foundation/solana-web3.js) |
| [One-click test tokens](FEATURES.md#one-click-test-tokens) | [Solana (Agave)](https://github.com/anza-xyz/agave) |
| [Kill switch](FEATURES.md#kill-switch) | the app ([Windows](https://github.com/Sentinel-Bluebuilder/sentinel-solana-dvpn-windows) · [macOS](https://github.com/Sentinel-Bluebuilder/sentinel-solana-dvpn-macos) · [Linux](https://github.com/Sentinel-Bluebuilder/sentinel-solana-dvpn-linux) · [Android](https://github.com/Sentinel-Bluebuilder/sentinel-solana-dvpn-android)) |
| [Split tunnelling](FEATURES.md#split-tunnelling) | the app ([Windows](https://github.com/Sentinel-Bluebuilder/sentinel-solana-dvpn-windows) · [macOS](https://github.com/Sentinel-Bluebuilder/sentinel-solana-dvpn-macos) · [Linux](https://github.com/Sentinel-Bluebuilder/sentinel-solana-dvpn-linux) · [Android](https://github.com/Sentinel-Bluebuilder/sentinel-solana-dvpn-android)) |
| [AI agent mode](FEATURES.md#ai-agent-mode) | the app ([Windows](https://github.com/Sentinel-Bluebuilder/sentinel-solana-dvpn-windows) · [macOS](https://github.com/Sentinel-Bluebuilder/sentinel-solana-dvpn-macos) · [Linux](https://github.com/Sentinel-Bluebuilder/sentinel-solana-dvpn-linux)) |
| [Full command line](FEATURES.md#command-line) | the app ([Windows](https://github.com/Sentinel-Bluebuilder/sentinel-solana-dvpn-windows) · [macOS](https://github.com/Sentinel-Bluebuilder/sentinel-solana-dvpn-macos) · [Linux](https://github.com/Sentinel-Bluebuilder/sentinel-solana-dvpn-linux)) |
| [DNS and WebRTC leak protection](FEATURES.md#leak-protection) | the app ([Windows](https://github.com/Sentinel-Bluebuilder/sentinel-solana-dvpn-windows) · [macOS](https://github.com/Sentinel-Bluebuilder/sentinel-solana-dvpn-macos) · [Linux](https://github.com/Sentinel-Bluebuilder/sentinel-solana-dvpn-linux) · [Android](https://github.com/Sentinel-Bluebuilder/sentinel-solana-dvpn-android)) |
| [One-click connect](FEATURES.md#one-click-connect) | the app ([Windows](https://github.com/Sentinel-Bluebuilder/sentinel-solana-dvpn-windows) · [macOS](https://github.com/Sentinel-Bluebuilder/sentinel-solana-dvpn-macos) · [Linux](https://github.com/Sentinel-Bluebuilder/sentinel-solana-dvpn-linux) · [Android](https://github.com/Sentinel-Bluebuilder/sentinel-solana-dvpn-android)) |
| [15 languages](FEATURES.md#15-languages) | the app ([Windows](https://github.com/Sentinel-Bluebuilder/sentinel-solana-dvpn-windows) · [macOS](https://github.com/Sentinel-Bluebuilder/sentinel-solana-dvpn-macos) · [Linux](https://github.com/Sentinel-Bluebuilder/sentinel-solana-dvpn-linux) · [Android](https://github.com/Sentinel-Bluebuilder/sentinel-solana-dvpn-android)) |
| [Light and dark mode](FEATURES.md#light-and-dark-mode) | the app ([Windows](https://github.com/Sentinel-Bluebuilder/sentinel-solana-dvpn-windows) · [macOS](https://github.com/Sentinel-Bluebuilder/sentinel-solana-dvpn-macos) · [Linux](https://github.com/Sentinel-Bluebuilder/sentinel-solana-dvpn-linux) · [Android](https://github.com/Sentinel-Bluebuilder/sentinel-solana-dvpn-android)) |
| [Session history with CSV export](FEATURES.md#activity-history) | the app ([Windows](https://github.com/Sentinel-Bluebuilder/sentinel-solana-dvpn-windows) · [macOS](https://github.com/Sentinel-Bluebuilder/sentinel-solana-dvpn-macos) · [Linux](https://github.com/Sentinel-Bluebuilder/sentinel-solana-dvpn-linux) · [Android](https://github.com/Sentinel-Bluebuilder/sentinel-solana-dvpn-android)) |
| [Windows, macOS, Linux, Android](FEATURES.md#windows-macos-linux-android) | [Windows](https://github.com/Sentinel-Bluebuilder/sentinel-solana-dvpn-windows) · [macOS](https://github.com/Sentinel-Bluebuilder/sentinel-solana-dvpn-macos) · [Linux](https://github.com/Sentinel-Bluebuilder/sentinel-solana-dvpn-linux) · [Android](https://github.com/Sentinel-Bluebuilder/sentinel-solana-dvpn-android) |

## Languages

English, Chinese (Simplified), Chinese (Traditional), Spanish, French, Portuguese, Russian, German, Korean, Hindi, Tamil, Indonesian, Malay, Filipino, Thai, Kurdish (Kurmanji). Some status and error messages still show in English. Right-to-left languages are coming later.
