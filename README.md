Compile instructions for Windows, Linux, Mac.

Need qt5, boost, cmake.

Window users can use Visual Studios.


------------------------------------------
Compile instructions for Linux!
```
sudo add-apt-repository universe

sudo apt-get update

sudo apt-get install build-essential git cmake libboost-all-dev

sudo apt-get install qtbase5-dev
```
1. Clone wallet sources
```
git clone https://github.com/crypto-king/Bitdirect-Wallet.git

cd Bitdirect-Wallet
```
2. Build
```
cp cryptonote/src/Platform/Posix/System/* cryptonote/src/System
mkdir build && cd build && cmake .. && make
```
