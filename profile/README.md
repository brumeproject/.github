# Brume Wallet ☁️

The private Ethereum wallet with built-in Tor

## TLDR
- Anonymous requests using Tor (the dark net)
- Built for strong zero-cost privacy and security
- Available as an extension and on a website
- Won EthBrno 2022 hackathon (+ design award)
- Made by two French cypherpunks
- Almost like with MetaMask

## About 

Brume Wallet is an **Ethereum wallet** (for now), whose killer feature is a built-in implementation of the Tor protocol (the dark net), that makes **all your network requests go through the Tor network**, such that the people at the end of the pipe **can't use your IP address to track you or censor you**.

By using traditional wallets, your IP address is sent to multiple third-party services, who often have access to your multiple wallet addresses too, so they can use these informations to track you and your wallets, and/or censor your transactions.

Brume Wallet prevents that, and does even more in terms of privacy and security.

This project was launched at the privacy-centric EthBrno hackathon, 2022 edition. It won the first place and the design award.

Our team is made of two cypherpunks, Haz and Gabari, who both have a strong background in privacy and security

- Haz is a software engineer and pentester with an impressing GitHub profile, he found high and critical security vulnerabilities in protocols such as Tor, WalletConnect, TornadoCash, and in companies such as FleekHQ.

- Gabari has worked for several DAOs in the top-10 by market cap, and is now at the Head of Marketing & Communication at MangroveDAO, the First Programmable DEX.

We believe privacy and security are the foundations of the crypto ecosystem, and that this should remain true, especially for the Ethereum ecosystem. The story is that we used multiple wallets and never found the right shoe in terms of privacy and security, so **we decided to make our own**.

This project allows us to make privacy and security important again, with a scheme we like to call "**zero-cost privacy**", that is, privacy with almost no cost for the user in terms of UX and features.

We already almost achieved **feature-parity with existing wallets** such as MetaMask, but with the added privacy and security.

For example, we fixed the privacy and security of Ledger and WalletConnect by making our own implementation of these protocols for our wallet, such that there is **no privacy leak possible and no security backdoor**.

All our work is **fully open-source**, MIT licensed, and reproducible. And we will soon provide a best-effort distribution system by publishing the hashes of the builds to IPFS and Ethereum.

## I don't understand that Tor thing

Brume Wallet sends your transactions through the Tor network (the dark web), so people at the end of the pipe can't use your IP address to: 
- Know your location and ISP
- Track you and link your multiple identities together
- Send your IP address to people you don't like

Traditional wallets send your IP address and your wallet address to third-parties (RPC, Coingecko, Etherscan).

They can track you even if you are using on-chain privacy tools such as mixers and private blockchains.

<img width="762" src="https://user-images.githubusercontent.com/111573119/201625137-293eec93-a6c9-43fd-8eda-56dea0c8e00e.png">

## Getting started

You can use Brume Wallet as an extension and on a website

### Using the website

- Click here https://wallet.brume.money

### Installing the extension

#### Chrome / Brave / Chromium

- [Click here](https://chrome.google.com/webstore/detail/brume-wallet/oljgnlammonjehmmfahdjgjhjclpockd)

#### Firefox

- [Click here](https://github.com/brumewallet/wallet/releases/latest/download/firefox.xpi)

## Our projects

### Our main projects
- [Brume Wallet](https://github.com/brume-wallet/wallet) / The private Ethereum wallet with built-in Tor
- [Brume Logs](https://github.com/brume-wallet/logs) / The website to check if your wallet leaks your IP address

### Our main libraries
- [Echalote](https://github.com/hazae41/echalote) / Zero-copy Tor protocol for the web 🏎️ (JS + WebAssembly)
- [Cadenas](https://github.com/hazae41/cadenas) / Zero-copy TLS protocol for the web 🏎️ (JS + WebAssembly)
- [Fleche](https://github.com/hazae41/fleche) / Zero-copy HTTP protocol for the web 🏎️ (JS + WebAssembly)
