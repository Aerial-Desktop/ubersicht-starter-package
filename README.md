# ubersicht-starter-package
start people on ubersicht with a single script

## Toted as the RainMeter for macintosh computers, Setup Below:
```bash
## This will install ubersicht and a starter plugin that makes an iron man desktop background.
brew tap caskroom/cask &&
brew cask install ubersicht &&
git clone https://github.com/Dellos7/ironman-reactor-ubersicht-widget.git $HOME/Library/Application\ Support/Übersicht/widgets/ironman-reactor-ubersicht-widget &&
open /Applications/Übersicht.app

# For easy access to the widgets folder:
cd $HOME/Library/Application\ Support/Übersicht/widgets

# How to easily shut of Übersicht
osascript -e 'quit app "Übersicht"'

# Easy uninstall the plugin installed in this Readme (Iron Man):
rm -rf $HOME/Library/Application\ Support/Übersicht/widgets/ironman-reactor-ubersicht-widget
```
