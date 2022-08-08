# VimGameSnake

version 0.1

![animated demonstration](https://cloud.githubusercontent.com/assets/1855714/25851103/5c40d8c2-34ff-11e7-93b2-e161d973e4c8.gif)

## How to play

`:VimGameSnake` to Start
`:echo g:VimSnakeScore` to view score

h   | j   | k   | l   | c        | q
--- | --- | --- | --- | ---      | ---
←   |↓    |↑    |→    | end game | quit

## How to configure

Change the game difficulty
```vim
let g:VimSnakeMode = 'hard' " easy|hard|godmode - default: hard
```

Change the gameover policy
  - always - restart the game after sneyk died
  - none - stop the game
```vim
let g:VimSnakeRestart = 'always' " always|none - default: always
```

## Installation

### VimPlug

Place this in your .vimrc:

> Plug 'johngrib/vim-game-snake'

Then run the following in Vim:

> :source %

> :PlugInstall

