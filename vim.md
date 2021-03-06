## Installing Vim

Install the latest Vim with Homebrew

```brew install vim```

Then set your `$PATH` to use `usr/local/bin` 

```export PATH=/usr/local/bin:$PATH```

## Vim configuration

Create a `~/.vimrc` file for configuration

```
" vim configurations

" hybrid line numbers
set relativenumber
set number
  
" syntax highlighting
syntax on
```

## Map Caps Lock key to ESC

Go to `Preferences > Keyboard > Modifier Keys`, and set `No Action` to the `Caps Lock` key

Then install [Seil](https://pqrs.org/osx/karabiner/seil.html.en) and follow instructions [here](http://stackoverflow.com/questions/127591/using-caps-lock-as-esc-in-mac-os-x#8437594).

## Vim Cheat Sheet

| mapping|summary|
|:---|:---|
| `:q` or `:quit`|to quit vim|
| `:w` or `:write`|to save changes|
|`:e.` or `:edit .`|navigate file directory|
|`j`|move down|
|`k`|move up|
|`h`|move left|
|`l`|move right|
|`d`|delete\*|
|`y`|yank|

\* duplicate operator to apply to current line (e.g. `yy` to yank current line)
