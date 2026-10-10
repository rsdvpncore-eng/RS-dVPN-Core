# RS dVPN Core

> Next-gen decentralized privacy desktop client.

- **Website:** https://rs-dvpn-core.com
- **Releases:** https://github.com/rsdvpncore-eng/RS-dVPN-Core/releases

---

RS dVPN Core is an independent, non-custodial desktop client that integrates with third-party decentralized VPN infrastructure through TequilAPI. No RS dVPN Core account or custodial wallet is required.

## Key Features

- **Non-Custodial & Registration-Free:** No account creation, email, or custodial tracking required.
- **TequilAPI Native Support:** Native integration with decentralized node discovery and management protocols (including bundled Mysterium helpers).
- **Built-in Speed Test:** In-app ping, download, and upload measurement tools optimized for VPN routes.
- **Enhanced Connection Control:** Clearer auto-connect progress, smart reconnection handling, and real-time public IP / wallet status tracking.
- **Subscription-Aware Interface:** Intuitive navigation with dynamic access management across Wallet, VPN, Subscription, and Diagnostic logs.
- **Cross-Platform:** Dark-themed native support for Windows (`.exe`), macOS (`.pkg`), and Linux (`.AppImage` with WSL2 compatibility).

## Downloads

Download the latest version on the official website **[rs-dvpn-core.com](https://rs-dvpn-core.com)** or directly from **[GitHub Releases](https://github.com/rsdvpncore-eng/RS-dVPN-Core/releases)**.

- **Windows:** `.exe` installer
- **macOS:** `.pkg` installer (ad-hoc signed)
- **Linux:** `.AppImage` (x64, requires `sudo` / admin privileges; see WSL2 instructions in release notes)

## Status

- [x] **v0.0.2** — AppImage fixes, built-in Speed Test, live IP/wallet tracking, and UX improvements.
- [x] **v0.0.1** — Core TequilAPI integration, node discovery, and wallet management.
- [x] **v0.0.1b** — Initial public beta release with TequilAPI integration.
- [x] Built-in bandwidth testing and speed benchmarks.
- [ ] Auto-reconnect background daemon & Kill-switch.
- [ ] Multi-hop node routing support.
