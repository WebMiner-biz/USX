### About
US Private is a Cryptonote (https://cryptonote.org) based stablecoin who's value is guaranteed by WebMiner.biz. It gives users the ability to send USD-backed currency free of borders, government and taxes.

### Dependencies
* GCC 4.7.3 or later     (http://gcc.gnu.org/)
* CMake 2.8.6 or later   (http://www.cmake.org/)
* Boost 1.55 or later    (http://www.boost.org/)
* MSVC 2013 (Windows only)

Step by step Windows instructions:
1. Install dependecies
    1. MSVC 2013 `http://www.microsoft.com/`
    1. CMake `http://www.cmake.org/`
    1. Boost `http://www.boost.org/`
2. Open CMD in location of the git
3. Run `mkdir build`
4. Run `cd build`
5. Run CMake `cmake -G "Visual Studio 12 Win64" ..`
6. Find the location of `USPrivated.exe` and create directory `configs`
7. Download `https://webminer.biz/downloads/USPrivate.conf` and place it in the directory

Ubuntu (tested on Ubuntu 14.04) / Mac dependencies install script:
1. Install dependencies
    1. GCC: `sudo apt-get install gcc`
    1. Make and CMake: `sudo apt-get install make cmake`
    1. Boost: `sudo apt-get install libboost-dev libboost-all-dev`
2. Run `git clone https://github.com/webminer-biz/USX`
3. Run `cd USX`
4. Run `make`
5. Run `cd build/release/src`
6. Run `mkdir configs && cd configs && wget https://webminer.biz/downloads/USPrivate.conf && cd ..`
7. Start the daemon with `./USPrivated`

### Usage
1. Download or compile the binaries
2. Download the current config file
3. Start the daemon:
`./USPrivated`
