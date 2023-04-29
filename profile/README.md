<img width="500" src="https://user-images.githubusercontent.com/4405263/235300182-bcc6d800-fc3c-4d37-b2c8-ead6df5e97bb.png"/>

Brume Wallet is a non-custodial and private Ethereum wallet with a built-in integration of Tor

### TLDR
- Anonymous requests using Tor, no installation needed, each wallet address has its own IP address
- Built for strong privacy and supply-chain hardened
- Available as an extension and on a website
- Better UX and features than your average wallet

### I don't understand that Tor thing

Brume Wallet sends your transactions through the Tor network (the dark web), so people at the end of the pipe can't use your IP address to: 
- Know your location and ISP
- Link your multiple identities together
- Send your IP address to people you don't like

### Our main projects
- [Brume Wallet](https://github.com/brume-wallet/wallet) / The first private Ethereum wallet with built-in Tor
- [Brume Logs](https://github.com/brume-wallet/logs) / The website to check if your wallet leaks your IP address

### Our main libraries
- [Echalote](https://github.com/hazae41/echalote) / Zero-copy Tor protocol for the web 🏎️ (JS + WebAssembly)
- [Cadenas](https://github.com/hazae41/cadenas) / Zero-copy TLS protocol for the web 🏎️ (JS + WebAssembly)
- [Fleche](https://github.com/hazae41/fleche) / Zero-copy HTTP protocol for the web 🏎️ (JS + WebAssembly)
