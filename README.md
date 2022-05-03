# dboard
##### Expandable and customizable dmenu virtual keyboard for Linux with Emoji, Copypasta, Swedish/Finnish, Spanish, Chinese, Japanese, Baybain, and Arabic letter support.

![image](https://user-images.githubusercontent.com/71722170/166553916-2a36c6c7-5b0e-49f2-a670-06a620923b36.png)

## What is this?
dboard is a dmenu "keyboard" that opens a menu (dmenu) prompt with a list of characters. When the user selects one, it is automatically copied to the clipboard using xclip. You can then paste it anywhere you want.

## Motivation
Luke Smith's version only works with emojis, and flag emojis (and other emojis that have multiple characters) are broken because of the way it was written. Therefore I made a (in my opinion) better version which also has more emojis that weren't present in the original board.

## What does it support?
- Emojis (yes, even colored ones)
- Copypasta (comes with two RMS quotes)
- Swedish/Finnish characters
- Spanish characters
- Chinese characters
- Japanese characters
- Baybain characters
- Arabic characters

## Installation
- Download the script and put it in /usr/bin, /usr/local/bin or any other place that's defined in your $PATH variable.
- Make sure to patch dmenu with [this](https://tools.suckless.org/dmenu/patches/allow-color-font) patch and install libXft-bgra. Otherwise dmenu will either crash or not display the fonts
- Make sure to install a color font (such as JoyPixels, Noto Emoji) and define it in config.h (or config.def.h)
- Make sure xclip is installed and running on startup.
- If you want notifications, make sure libnotify is installed.

## Screenshots
![image](https://user-images.githubusercontent.com/71722170/166553999-e3dbb654-6d15-475e-a8ce-bb508c34be75.png)
(boxes because my fonts are a bit weird)
![image](https://user-images.githubusercontent.com/71722170/166553916-2a36c6c7-5b0e-49f2-a670-06a620923b36.png)

## Credits
See the 'credits' screen.

## License
This software is licensed under the GNU GPLv3 license.
