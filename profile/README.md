# Brume Wallet ☁️

A non-custodial and private Ethereum wallet with a built-in implementation of the Tor network

### TLDR
- Anonymous requests using Tor, no installation needed, each wallet address has its own IP address
- Built for strong privacy and supply-chain hardened
- Available as an extension and on a website
- Pleasant user experience
- Made by french cypherpunks

### I don't understand that Tor thing

Brume Wallet sends your transactions through the Tor network (the dark web), so people at the end of the pipe can't use your IP address to: 
- Know your location and ISP
- Track you and link your multiple identities together
- Send your IP address to people you don't like

MetaMask and similar wallets send your IP address and your wallet address to third-parties (RPC, Coingecko, Etherscan)

They can track you even if you are using on-chain privacy tools such as Aztec Network or Tornado Cash

<img width="762" src="https://user-images.githubusercontent.com/111573119/201625137-293eec93-a6c9-43fd-8eda-56dea0c8e00e.png">

## Getting started

You can use Brume Wallet as an extension and on a website

### Using the website

- Click here https://wallet.brume.money

### Installing the extension

#### Chrome / Brave / Chromium

- [Click here](https://chrome.google.com/webstore/detail/brume-wallet/oljgnlammonjehmmfahdjgjhjclpockd)

#### Firefox

- [Click here](https://github.com/brumewallet/wallet/releases/latest/download/firefox.xpi) or download the `firefox.xpi` file on the [release page](https://github.com/brumewallet/wallet/releases)

### Our main projects
- [Brume Wallet](https://github.com/brume-wallet/wallet) / The private Ethereum wallet with built-in Tor
- [Brume Logs](https://github.com/brume-wallet/logs) / The website to check if your wallet leaks your IP address

### Our main libraries
- [Echalote](https://github.com/hazae41/echalote) / Zero-copy Tor protocol for the web 🏎️ (JS + WebAssembly)
- [Cadenas](https://github.com/hazae41/cadenas) / Zero-copy TLS protocol for the web 🏎️ (JS + WebAssembly)
- [Fleche](https://github.com/hazae41/fleche) / Zero-copy HTTP protocol for the web 🏎️ (JS + WebAssembly)
