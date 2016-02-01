# Software to be installed on OS X

## Mac App Store

List of applications to install:

- Dash 3
- Telegram Desktop or Telegram
- Go2Shell
- Caffeine
- Slack
- 1Password
- Alfred
- Xcode
- Keynote

## Homebrew Cask

To install [Homebrew](http://brew.sh/)

```
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

To install [Cask](http://caskroom.io/)

```
brew tap caskroom/cask
```

List of applications to install:

- Firefox
- Google Chrome
- Atom
- Sublime Text
- Transmission
- VLC
- TunnelBear
- Private Internet Access
- Seashore
- Calibre
- Handbrake

You can search for applications with [Cask Search](http://caskroom.io/search) or from the Terminal, type: 

```
brew cask search <app name>
```

You can create a `Brewfile`. See [Holman's dotfiles](https://github.com/holman/dotfiles/blob/master/Brewfile) as an example.
