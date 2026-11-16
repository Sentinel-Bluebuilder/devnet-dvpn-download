# Devnet dVPN features

What each feature does and where to find it in the app. [Back to downloads](README.md)

- [6-protocol VPN](#6-protocol-vpn)
- [Kill switch](#kill-switch)
- [Split tunnelling](#split-tunnelling)
- [AI agent mode](#ai-agent-mode)
- [Peer-to-peer, no accounts](#peer-to-peer-no-accounts)
- [Leak protection](#leak-protection)
- [Pay per GB or per hour](#pay-per-gb-or-per-hour)
- [Claim refunds](#claim-refunds)
- [One-click connect](#one-click-connect)
- [Node test](#node-test)
- [Command line](#command-line)
- [15 languages](#15-languages)
- [Built-in Solana wallet](#built-in-solana-wallet)
- [One-click test tokens](#one-click-test-tokens)
- [Light and dark mode](#light-and-dark-mode)
- [Activity history](#activity-history)
- [Windows, macOS, Linux, Android](#windows-macos-linux-android)

## 6-protocol VPN

Connects with WireGuard, OpenVPN, V2Ray, Xray, Hysteria2 or AmneziaWG, whichever the server offers. The server list shows each server's protocols, and you can filter by protocol. V2Ray, Xray, Hysteria2 and AmneziaWG make VPN traffic hard to recognise and block, for networks where ordinary VPNs are blocked.

## Kill switch

Blocks all internet traffic if the VPN connection drops, so nothing goes out unprotected. Turn it on in **Kill switch**. If a block is ever left behind, **Restore network** removes it in one click.

## Split tunnelling

Choose which apps go through the VPN and which use your normal connection. Set it in **Split tunnelling**; the two lists show what goes through the VPN and what stays outside.

## AI agent mode

An AI agent can run the VPN on its own with three commands: `agent up` connects, `agent status` reports the state, `agent down` disconnects. The **CLI** screen has **Copy instructions** to hand these to your agent.

## Peer-to-peer, no accounts

There is no sign-up and no company server. The app finds servers on the Solana blockchain and pays the server operator directly from your wallet.

## Leak protection

DNS lookups go through the VPN, not your internet provider. The browser started from the app blocks WebRTC from showing your real address. The connection view shows the address websites see.

## Pay per GB or per hour

Each connection is paid per GB or per hour, as you choose. You pay the price shown when you connected, never more.

## Claim refunds

Money left in a deposit after a session ends comes back to your wallet with **Claim refunds** in **Wallet**, including deposits made from an earlier device.

## One-click connect

**Connect** picks the fastest server, or one in your preferred country. While connected you see the server, protocol, data used and cost.

## Node test

Test any server's speed and whether it answers before you pay for real use. Open **Node test**, pick servers and run the test.

## Command line

Every feature in the app is also a command (more than 80 of them), so you can script it. Run them in the app's **CLI** screen, or with `devnet-dvpn` in a terminal on Windows, macOS and Linux. `status --json` gives output another program can read.

## 15 languages

English, Chinese (Simplified), Chinese (Traditional), Spanish, French, Portuguese, Russian, German, Korean, Hindi, Tamil, Indonesian, Malay, Filipino, Thai and Kurdish (Kurmanji). Pick one from the language menu at the bottom left; it changes at once with no restart. **System language** follows your computer. Some status and error messages still show in English.

## Built-in Solana wallet

Create a wallet or import one with its recovery phrase. **Wallet** shows your SOL and tDVPN balances, your address with a QR code, and the spending limit that lets this device pay servers on its own.

## One-click test tokens

The **Devnet** card at the bottom left has **SOL** and **tDVPN** buttons. Each copies your address; SOL opens the Solana devnet faucet.

## Light and dark mode

Switch with the sun and moon buttons at the bottom left, beside the language menu. **Settings** also lets the app follow your system.

## Activity history

**Activity** lists every session with country, server, protocol, data, cost and how it ended. **Export CSV** saves it as a file.

## Windows, macOS, Linux, Android

The same app on all four systems. [Download it here](README.md#download).
