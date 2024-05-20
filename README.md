![Blockly Games](https://raw.githubusercontent.com/wiki/google/blockly-games/title.png)

Google's Blockly Games is a series of educational games that teach programming.
It is based on the [Blockly](https://developers.google.com/blockly/) library.
All code is free and open source.

**The games are available at https://blockly.games/**

**The developer's site is at https://github.com/google/blockly-games/wiki**

## Steps

### 1. Installation

1. Setting up game dependencies on macOS using `Homebrew`.
2. Installing game dependencies using `make deps` doesn't work because github doesn't support svn anymore so I download & import it manually to project via this link [https://github.com/google/blockly-games/raw/offline/generated/blockly-games-en.zip].
3. Then run `make games` to compile necessary files for games.

### 2. Maze Game

1. Add styles of slider in style.css of it's folder
2. Add html tags for slider & images in html.js
3. Then define speedSlider variable to store the slider value and add some math to it then save it to stepSpeed