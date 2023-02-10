# Dynex Wallet Application

![Dynex Wallet](https://github.com/dynexcoin/Dynex-Wallet-App/raw/main/dynexwallet.png)

With the Dynex Wallet App users can use the Dynex wallet functionality to create wallets, send and receive DNX and manage transactions and recipients

## Build Dynex Wallet from source:

### Install prerequisites

make sure that you have CMake, g++, gcc, libboost-all-dev

### To build it from the source you need to clone at first Cryptonote repo and have it ready for the building,
```
git clone https://github.com/dynexcoin/Dynex.git
```

### Set Symbolic Link

Set symbolic link to coin sources at the same level as src:
```
ln -s ../dynex cryptonote
```

### Install Homebrew
```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```
after installation make sure to export the PATH to use "brew" command in your terminal.
```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```
most likely, Homebrew will be installed and located in "/home/linuxbrew/.linuxbrew", if it is not then make sure to change the paths in the CMakeLists.txt
we need Homebrew to install boost and Qt5

### Install Qt5 and boost

```
brew install qt@5
```
if you run into an error at the end of the installation, please re-run the comand again
Qt5 will be located in "/home/linuxbrew/.linuxbrew/opt/qt@5/"

```
brew install boost
```
Boost will be located in "/home/linuxbrew/.linuxbrew/Cellar/boost/1.81.0_1/"
NOTE: if you install different boost version, make sure to update CMakeLists.txt

### Building/Compiling Dynex Desktop Wallet

```
mkdir build && cd build && cmake .. && make
```

