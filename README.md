# These are my dotfiles
There are many like it, but this one is mine

## Basics
* [Git](https://git-scm.com/download/mac)
* [Homebrew](https://brew.sh) for installing packages
```
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```
* [Open SSL](https://www.openssl.org/)
```
brew install openssl
```

## Databases
* [PostgreSQL](https://www.postgresql.org/download/macosx/)
```
brew install postgresql
```
* [Redis](https://redis.io/)
```
brew install redis
```

## Ruby Stuff
* [Rbenv](https://github.com/rbenv/rbenv) for managing Ruby versions
```
brew install rbenv
rbenv init
```
* [Bundler](http://bundler.io/)
```
gem install bundler
```

## JavaScript Stuff
* [Node.js](https://nodejs.org/en/) and [npm](!) - [Tutorial](https://www.dyclassroom.com/howto-mac/how-to-install-nodejs-and-npm-on-mac-using-homebrew)
```
brew install node
```
* [Yarn](https://yarnpkg.com/en)
```
brew install yarn
```

## Shell Stuff
* iTerm2 as terminal - [Download Here](https://www.iterm2.com/downloads.html)
* [Oh My Zsh](http://ohmyz.sh/) as shell configuration - Install via: 
```
sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
```
Load `./zshrc` from this repo for my settings

* [Ansiweather](https://github.com/fcambus/ansiweather) for command line weather updates
```
brew install jq
brew install bc
brew install ansiweather
```
Run `weather` from terminal to get current weather


* [Fuzzy Finder](https://github.com/junegunn/fzf)
```
brew install fzf
$(brew --prefix)/opt/fzf/install
```
* Try this one out when I get a touchbar - [iTerm Touchbar](!https://github.com/iam4x/zsh-iterm-touchbar)

## Text Editor Stuff
* [Sublime Text 3](https://www.sublimetext.com/3)
* User settings at `Preferences.sublime-settings` in this repo
#### Plugins
* A File Icon
* Agila Theme
* Alignment
* Babel
* BracketHighlighter
* Color Highlighter
* Console Wrap
* Git
* GitGutter
* Markdown Preview
* Materialize
* Package Control (install this first if not available immediately)
* Sidebar Enhancements
* SublimeLinter
* SublimeLinter-rubocop
* Theme - Spacegray

## Utilities
* BetterSnapTool - Allows for snapping to corners and sides of the screen
  * Create custom key bindings for snapping to corners, sides, thirds, and small custom area for semi-minimize
* Postico - A way to run SQL statements directly on the Postgres database
* Flux - Color the screen so I don't slowly go blind
* LiceCap - Record screencasts 
* Postman - Call API endpoints on a GUI
* RescueTime - Get weekly reports on productivity and time use breakdown
* Dash - Offline documentation.  Download following docsets:
  * Ruby
  * Ruby on Rails 5
  * Ruby on Rails 4
  * Bootstrap 3
  * Bootstrap 4
  * D3.js
  * CSS
  * Elixir
  * Font Awesome
  * JavaScript
  * jQuery
  * Markdown
  * R
  * React
  * Ruby 2
  * iTerm2
  * Sublime Text 3

## Settings
* Keyboard
  * Crank up `Key Repeat` and `Delay Until Repeat` 
  * Remap key so `CapsLock` becomes `Ctrl`


## Other

* [Heroku CLI](https://devcenter.heroku.com/articles/heroku-cli#download-and-install)
```
brew install heroku/brew/heroku
```


