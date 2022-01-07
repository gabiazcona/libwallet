# Libwallet

A lightweight and very portable library with simple to understand and use
abstractions that allow creating chain-agnostic crypto wallets able to run in
all kinds of environments like native applications, hosted wallets, the browser
or even embedded hardware.

Core principles:

- **Ease of use**


Portability
Multi-chain
Multi-account
Size

- High level public API that abstracts blockchain and cryptography heavy concepts bringing the
- Created around `Vault`s, an abstraction that makes it easier to support
  multiple backends that store private keys in different ways whether it is a
  cryptographic hardware module, a database or a file system. 
- Chain agnostic, no assumtions are made about what the kind of private keys and
  signatures come from the vault to support any chain.
- Wallet only, to integrate better with more networks and blockchain clients
  the library doesn't provide means to send transactions to the blockchain, it
  leaves that responsability to other libraries.
- Substrate optimized, built around Substrate core crypto primitives and with
  extensions to aid in its integration with the ecosystem chains.
- Multi account, 
- Batch signing,
- WASM and `no_std` friendly

## Virto and future steps



