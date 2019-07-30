## Table of Contents
- [Table of Contents](#table-of-contents)
- [Installation](#installation)
- [Screenshots](#screenshots)
- [Options](#options)
- [Simulation mode](#simulation-mode)
- [Bugs](#bugs)
- [To be implemented](#to-be-implemented)


## Installation
Clone the repository and run `main.py`. Example:
```
git clone https://github.com/bmeares/chess.git
cd chess/
python3 main.py
```

## Screenshots
<img src="https://i.imgur.com/2NMN1bR.png" alt="Fancy" height=400> <img src="https://i.imgur.com/h96NoMK.png" alt="Sorta fancy" height=400> <img src="https://i.imgur.com/HbfKPGS.png" alt="Classic" height=400>


## Options

Run ```python3 main.py -h``` to display all options or ````python3 main.py -m```` to display all menus instead of using flags.

Below is a list of the currently supported options:

```
 Options:
 ========

 GRAPHICS
   -a .... ASCII-only
   -l .... Limited ANSI
   -u .... Full Unicode / ANSI / TrueColor

 GAME MODES
   -0 .... 0 Player
   -1 .... 1 Player
   -2 .... 2 Player

 SPEED
   -f .... Fast
   -s .... Slow

 AI
   -n .... Normal
   -g .... Aggressive
   -c .... Chill

 MISC
   -m .... Show all menus
   -h .... Show help / options
   -i .... Simulation
```

## Simulation mode

Enter "s" at any menu prompt to enter Simulation Mode. From here you can run up to 1,000,000 games and see the resulting statistics.

**Features:**
- Autosaves your progress
- Outputs each turn to a .txt file
- Prevents players from entering check
- Easy-to-use input
- Can be paused/quit and resumed
- Displays the remaining number of pieces on the board
- Exchange pawns for other pieces when reaching the other side of the board
- 0, 1, or 2 player modes


I should have caught most bugs! Let me know how you break my code.

## Bugs
- Check indicator seems to sometimes display check when not in check

## To be implemented
- Castling

