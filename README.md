Fork of the Crypto-King Bitdirect-Wallet!


Changed the files... 

1) src/CryptoNoteWrapper.cpp 

2) cryptonote/src/Wallet/LegacyKeysImporter.cpp

3) cryptonote/src/WalletLegacy/WalletLegacySerializer.cpp


Compile instructions for Linux!



```
sudo add-apt-repository universe

sudo apt-get update

sudo apt-get install build-essential git cmake libboost-all-dev

sudo apt-get install qtbase5-dev
```

**1. Clone wallet sources**

```
git clone https://github.com/lukless1990/Bitdirect-Wallet.git

cd Bitdirect-Wallet
```


**2. Build**

```
cp cryptonote/src/Platform/Posix/System/* cryptonote/src/System
mkdir build && cd build && cmake .. && make
```
