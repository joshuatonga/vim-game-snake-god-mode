# VimGameSnake

version 0.1

![animated demonstration](https://cloud.githubusercontent.com/assets/1855714/25851103/5c40d8c2-34ff-11e7-93b2-e161d973e4c8.gif)

## How to play

`:VimGameSnake` to Start
`:echo g:VimSnakeScore` to view score

h   | j   | k   | l   | c        | q
--- | --- | --- | --- | ---      | ---
←   |↓    |↑    |→    | end game | quit

## How to change mode

put this somewhere in your vim config
```vim
let g:VimSnakeMode = 'hard' " easy|hard|godmode - default: hard
```

## Installation

### VimPlug

Place this in your .vimrc:

> Plug 'johngrib/vim-game-snake'

Then run the following in Vim:

> :source %

> :PlugInstall

