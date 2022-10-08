# winLauncher
C++ command line program launcher for Windows, designed for games.

![https://i.imgur.com/SlIOgrY.png](https://i.imgur.com/SlIOgrY.png)

# Installation
## From release
Simply download the release and run the executable.

## From source
### Requirements
- [msys64](https://www.msys2.org/)
- [pdcurses](https://github.com/wmcbrine/PDCurses)

### Build
1. Clone the repository `git clone https://github.com/TheArchons/WinLauncher`
2. cd into the directory and run `g++ .\winlauncher.cpp -lpdcurses -o winlauncher.exe -static`
3. Run `winlauncher.exe`.

# Usage
When running the program, use Ctrl+A to add a program, Ctrl+Q to quit, and Ctrl+R to remove a program
