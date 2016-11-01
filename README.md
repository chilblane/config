# config
Everything I need to set up a new dev environment.

## General setup (macOS Sierra)
1. Go through Apple wizards
2. Clean up dock
  - Add Applications folder to Dock
  - Change Applications and Downloads display to "Folder"
3. System preferences (only major/relevant changes shown)
  - General
    - Appearance: graphite
    - Check _Use dark menu bar and Dock_
    - Sidebar icon size: small
  - Dock
    - Size: move to about 30%
  - Mission Control
    - Uncheck _Automatically rearrange Spaces based on most recent use_
    - Hot Corners...
      - Lower-left: _Put Display to Sleep_
  - Trackpad
    - Check _Tap to click_
  - Sounds
    - Check _Play feedback when volume is changed_
    - Check _Show volume in menu bar_
  - App Store
    - Check _Install macOS updates_
  - Sharing
    - Rename computer name
  - Time Machine
    - Set up per hardware requirements/environment
    - Check _Show Time Machine in menu bar_
4. Installing apps
  - Non-App Store
    - Chrome
    - Dropbox
    - 1Password
    - f.lux
    - Bartender
    - iStat Menus
    - whatever else
  - App Store
    - Tweetbot

## Development (macOS Sierra)
### Prerequisites
1. Install the Xcode cli tools `xcode-select --install` in a terminal
2. Install [Git](https://git-scm.com/download/mac)
3. Install [Homebrew](http://brew.sh/)
4. `brew install ruby` to install a sane, up-to-date version of Ruby
5. Install [Node](https://nodejs.org/)

### Setting up Git and GitKraken
1. Follow instructions for [setting up SSH for Github](https://help.github.com/articles/generating-an-ssh-key/)
2. Clone this repo to your project folder: `git clone git@github.com:chilblane/config.git`
3. Note that you may be prompted to approve GitHub to the list of known hosts.
4. Install [GitKraken](https://www.gitkraken.com/)
5. In GitKraken preferences, fix the project folder location and authenticate with GitHub.

### Setting up iTerm and Zsh
1. Install [iTerm 2](https://www.iterm2.com/)
2. Install [oh-my-zsh](https://github.com/robbyrussell/oh-my-zsh)
3. In iTerm's preferences, check _Load preferences from a custom folder or URL:_ and navigate to this repository folder. Copy the settings.
4. Go to _Profiles_ > _Colors_ and select _Solarized Dark_ from the Color Presets.

### Setting up Atom
1. Install [Atom](https://atom.io/)
2. Copy the Atom settings from this repo to your local installation: `cp -R [repo folder]/.atom/ ~/`
