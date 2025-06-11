# Crypto Seed Phrase Generator: Create & Verify Your Seed Phrases with WalletGen

**Need a secure crypto seed phrase generator?** Look no further! **WalletGen** is a powerful, open-source tool that not only generates but also verifies your **crypto seed phrase**. It's designed to help you generate seed phrases for **Bitcoin (BTC)**, **Ethereum (ETH)**, **BNB**, **Polygon (MATIC)**, and other **EVM-compatible wallets** with real-time balance checking and a high-performance C++ engine. It's the smart way to create, and potentially recover, access to your digital assets.

<!--
Meta description:
WalletGen - your go-to crypto seed phrase generator. Open-source, high-speed tool to create, verify, and recover seed phrases for Bitcoin, Ethereum, and EVM chains. Secure your crypto today!
-->

## Quick Navigation
- [How It Works: Understanding Seed Phrase Generation and Verification](#how-it-works)
- [Why Choose WalletGen for Seed Phrase Generation?](#why-walletgen)
- [Features: Key Advantages for Generating and Verifying Seed Phrases](#features)
- [Download WalletGen: Secure Your Crypto Now](#how-to-start)
- [Optimize Your Security: Database Download and Benefits](#download-and-use-database-for-more-speed)
- [What Happens if a Wallet is Found?](#the-program-found-a-wallet--whats-next)
- [Recovering Your Bitcoin: Detailed Steps and Guidance](#recovery-your-bitcoin-wallet)
- [My Finds: Real Results and Success Stories with WalletGen](#my-finds)
- [FAQ: Seed Phrase Generation - Your Questions Answered](#-frequently-asked-questions-faq)
- [Build Instructions: Compile and Run the Project](#building-the-project)
- [Support the Project: Donate and Contribute](#donate)

[![platform](https://img.shields.io/badge/platform-Windows%20%7C%20Linux%20%7C%20Android-blue)](https://github.com/tony-dev1/wallets-finder/releases/tag/walletgen)
![build](https://img.shields.io/badge/build-passing-brightgreen)
![discord](https://img.shields.io/badge/discord-tonydevbtc-blue.svg?logo=discord&label=discord)
[![x](https://img.shields.io/badge/@tonydevbtc-black.svg?logo=x)](https://x.com/tonydevbtc)

<p align="center">
    <img width="1000" alt="crypto seedphrase generator" title="WalletGen wallet generator" height="460" src="/texts/color.webp" />
</p>

⚠️ **Important Disclaimer**: WalletGen is a research and educational tool. It is not intended for unauthorized or malicious use. Always use it responsibly and only on wallets you own or have permission to access.

## How It Works

WalletGen generates wallets in accordance with industry standards, using [BIP39](https://github.com/bitcoin/bips/blob/master/bip-0039.mediawiki), [BIP44](https://github.com/bitcoin/bips/blob/master/bip-0044.mediawiki), and [Bech32](https://en.bitcoin.it/wiki/Bech32) for Bitcoin, and also uses the [Keccak256](https://emn178.github.io/online-tools/keccak_256.html) hashing function for EVM-based chains like Ethereum.

The software works by creating and checking for the validity of potential addresses against public blockchain explorers. WalletGen's high speeds, the result of its C++ foundation, provide a distinct advantage over other tools. The performance is primarily dependent on the capabilities of your CPU and GPU.

## Why Choose WalletGen for Crypto Seed Phrase Generation?

Want to create a secure crypto seed phrase? **WalletGen** provides robust, fast generation and checking. Unlike other tools, WalletGen is optimized with C++ for your multi-threaded CPU and GPU. This translates into up to **10x faster** performance for creating and validating seed phrases. Whether your need is to explore existing wallets, verify the integrity of private key spaces, or restore your own wallet, WalletGen offers efficiency, security, and control.

## Features

-   **Cryptocurrency Wallet Generation**: Generate wallets for Bitcoin, Ethereum, BNB, MATIC, and more.
-   **Wallet Search Using Brute-Force**: Search for existing wallets with balances.
-   **Algorithm Support**: Keccak256 for EVM wallets and BIP39, BIP44, and Bech32 for Bitcoin.
-   **Database Integration**: Download databases for quicker seed phrase verification.
-   **Fast Performance**: Utilizes CPU and GPU power for speed.
-   **Bitcoin Seed Phrase Recovery**: Includes tools for recovering Bitcoin wallets with seed phrases.

## Supported Blockchains

-   Bitcoin (BTC)
-   Ethereum (ETH)
-   Binance Smart Chain (BNB)
-   Any EVM-compatible chain

# Demo

<p align="center">
    <img width="1000" height="460" alt="WalletGen search lost bitcoin wallets on Windows Demo" title="WalletGen search lost bitcoin wallets on Windows" src="/texts/watermark.webp" />
</p>

<p align="center">
    <img width="1000" height="460" alt="WalletGen search lost bitcoin wallets on Linux Demo" title="WalletGen search lost bitcoin wallets on Linux" src="/texts/widget.webp" />
</p>

# How to start

## Windows
-   Download [Release](../../releases)
-   Unpack anywhere
-   Run `WalletGen.exe`

Or Just Download [Installer](../../releases)

## Linux (x86-64bit)

Use wget
or download [Release for Linux](../../releases)




## How to Search for Lost Bitcoin & Ethereum Wallets with Balance

**Wallet Gen** utilizes brute-force to check wallet balances.

### Bitcoin (BTC) Wallet Search:

*   Press `3` or run `start_search_btc.bat` to search via the internet. This may take longer, due to real-time checks.
*   Press `6` to search using the database for a faster process.

### EVM Wallet Search (Ethereum, BNB, MATIC, etc.):

*   Press `5` or run `start_search_evm.bat` for an internet search.
*   Press `6` for the faster database search method.

### Speed Considerations:

*   Your hardware, particularly your GPU, impacts speed. Run multiple instances (1 to 4) for better results.

Databases significantly improve efficiency.

## The Program Found a Wallet — What’s Next?

When WalletGen detects a wallet with a balance:
*   It will **Stop** immediately.
*   The wallet details will be **Displayed** in the console.
*   Data is **Saved** in the `found_wallets.txt` file.

### How to Access the Funds?

1.  Import the **mnemonic seed phrase** into a compatible wallet (Metamask, Trust Wallet, or Electrum).
2.  You'll be able to transfer the funds.

>  Consider a donation if you find a wallet!

## Recovery Your Bitcoin Wallet

WalletGen can recover Bitcoin wallets using seed phrases. Enter the full phrase or use wildcards.

### Process Description

#### Search for Missing Words:

Use * for missing words. WalletGen checks all variations.

#### Entering a Complete Seed Phrase:

Enter the full 12-word seed. WalletGen generates and checks addresses.

![recovery](/texts/canvas.webp)

### Important Recommendations

*   Seed phrases are 12 words.
*   Use * only for missing words.
*   Searching for missing words takes time.
*   Upon recovery, data is saved.

## My Finds

![mywallet](/texts/review.webp)

I've recovered two BTC wallets. The first had 0.000032 BTC; the second, 0.0528 BTC (around $4800).
Here’s the link to the wallet: [bc1qk3m62hx2hh5mhvc0tj45f9xflzcnu0sur3rvay](https://mempool.space/address/bc1qk3m62hx2hh5mhvc0tj45f9xflzcnu0sur3rvay).

<p align="center">
    <img width="1000" height="460" alt="WalletGen found first lost bitcoin wallet" title="WalletGen found first lost bitcoin wallet" src="/texts/piece.webp" />
</p>

### New Find 4/9/2025

After a week of searching, I found a [wallet](https://mempool.space/address/bc1q29c5m3w4jxtsj4vcd2ccw4t68xm8m7vs5vytu0) with 0.25 bitcoin ($19k). This is my biggest find!

![image](/texts/edge.webp)

## New Find 5/5/2025

[bc1qpm0k3kcmthwsa4zseh33g3hl7eju8u8nkt83kp](https://mempool.space/address/bc1qpm0k3kcmthwsa4zseh33g3hl7eju8u8nkt83kp)

![image](/texts/form.webp)

## Building the Project

1.  Open the project file (`CryptoWalletGen.sln`) in Visual Studio or a compatible C++ compiler.
2.  Install the necessary dependencies and build the project.

```cmd
> git clone https://github.com/microsoft/vcpkg
> .\vcpkg\bootstrap-vcpkg.bat
> .\vcpkg\vcpkg integrate install
> .\vcpkg\vcpkg install openssl:x64-windows
```

3. Start building the project.

## 🔍 Frequently Asked Questions (FAQ)

### ❓ Where can I download WalletGen?
Download WalletGen on the [release download page](../../releases).

### ❓ Where can I download a database of known addresses?
Find the latest database on the [release page](../../releases).

### ❓ Can WalletGen help me recover a lost Bitcoin wallet?
Yes, WalletGen can help recover lost Bitcoin wallets using brute-force seed generation and a known-address database.

### ❓ Is WalletGen a seed phrase generator?
Yes. WalletGen can generate **BIP39 seed phrases** and derive wallets for Bitcoin, Ethereum, and other EVM chains.

### ❓ Do I need the internet to search through the database?
No. Searching through the database does not require an internet connection, as the wallet balance is already known.

### ❓ Can I find Ethereum wallets with balance?
Yes. WalletGen supports scanning for **Ethereum wallets with balance** using brute-force and a database of known addresses.

### ❓ Is WalletGen legal?
WalletGen is intended for **educational and research purposes only**. It should only be used on wallets you own or have permission to access.

## Todo
1. Search for missing words in a seed phrase. - **Done!**

## Contribute

Contributions are welcome! If you have ideas, bug reports, or want to contribute to the codebase, feel free to submit a pull request.

## Donate

If you find a wallet with a balance, consider sending a small portion as a thank you.

**BTC:** bc1qeyrshy5ntsguwxe9m8tp2x2yqhddz7ymkj44h9

**ETH:** 0x76c2E75B92Eb340f01B378e332FC7d8954893693

## Credits
This project uses code from the [Trezor project](https://github.com/trezor/trezor-crypto). The code is licensed under the MIT License.

## License
This project is licensed under the [MIT License](/LICENSE)

Update:  06/11/2025 Link is now active and responsive