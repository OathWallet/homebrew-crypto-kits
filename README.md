# homebrew-crypto-kits

Homebrew tap for OathWallet crypto wallet CLI packages.

GitHub release tags are the source of truth for formula downloads.

## Install

```bash
brew tap OathWallet/crypto-kits
brew install bip39kit
brew install walletkeycheck
brew install walletaddrcheck
```

Or install directly:

```bash
brew install OathWallet/crypto-kits/bip39kit
brew install OathWallet/crypto-kits/walletkeycheck
brew install OathWallet/crypto-kits/walletaddrcheck
```

## Commands

```bash
bip39kit --help
walletkeycheck list-chains --pretty
walletaddrcheck address 1BoatSLRHtKNngkdXEeobR76b53LETtpyT --chain bitcoin --pretty
```

## Packages

- `bip39kit`: from <https://github.com/OathWallet/bip39-mnemonic-kit>
- `walletkeycheck`: from <https://github.com/OathWallet/wallet-key-validator-kit>
- `walletaddrcheck`: from <https://github.com/OathWallet/wallet-address-validator-kit>
