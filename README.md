# Dynex GUI Wallet

![Dynex Wallet](https://github.com/dynexcoin/Dynex-Wallet-App/raw/main/dynexwallet.png)

With the Dynex Wallet App users can use the Dynex wallet functionality to create wallets, send and receive DNX and manage transactions and recipients. It is not necessary to run a separate Dynex node, everything is built into the GUI wallet.

## Build Dynex Wallet from source:

### Requirements

make sure that you have boost, Qt5.15 and libcurl installed on your operating system. To build from source:

### Build

```
mkdir build && cd build && cmake .. && make
```

The wallet can be started with

```
cd /build/src/WalletGui/
./dynexwallet
```
