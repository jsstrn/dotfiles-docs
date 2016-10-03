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

Go to `Preferences > Keyboard`, click on `Modifier Keys`, and set `No Action` to the `Caps Lock` key

Then install [Seil](https://pqrs.org/osx/karabiner/seil.html.en)
