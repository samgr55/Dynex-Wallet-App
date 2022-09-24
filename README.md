# Dynex Wallet Application

![Dynex Wallet](https://github.com/dynexcoin/Dynex-Wallet-App/raw/main/dynexwallet.png)

With the Dynex Wallet App users can use the Dynex wallet functionality to create wallets, send and receive TRGX and manage transactions and recipients. Download the version matching your operating system:

Mirosoft Windows: coming soon (you need to build the binary from source as described below)

Apple MacOS: https://github.com/dynexcoin/Dynex-Wallet-App/raw/main/MacOS_walletapp.zip

Linux: https://github.com/dynexcoin/Dynex-Wallet-App/raw/main/Ubuntu_22.04.1_walletapp.tar.xz

Please note that Linux and MacOS users are required to have the [Boost library](https://www.boost.org) (Version 1.74.0 or better) installed: 

Linux:
```
sudo apt-get install libboost-all-dev 
```

MacOS:
```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"

brew install boost
```

After downloading the precompiled binary, unzip the executable on your machine and start it.

## Build Dynex Wallet from source:

Alternatively, you can build your binaries from source:

```
mkdir build && cd build && cmake .. && make
```

