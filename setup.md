# Setting up a new macOS machine

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
    - whatever else
  - App Store
    - Tweetbot
    
## Development
1. Install the Xcode cli tools `xcode-select --install` in a terminal
2. Install [git](https://git-scm.com/download/mac)
3. Install [homebrew](http://brew.sh/)
4. `brew install ruby` to install a sane, up-to-date version of Ruby
5. Install [Node](https://nodejs.org/)
6. Install iTerm 2
