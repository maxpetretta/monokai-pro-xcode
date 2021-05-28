# Monokai Pro for Xcode
A direct port of the [Monokai Pro theme](https://monokai.pro/) from Visual Studio Code to Xcode, courtesy of [Transmog](https://github.com/inket/Transmog).

![Example code colored using the theme](https://user-images.githubusercontent.com/19291506/119922140-d18fd100-bf34-11eb-9bc0-fcf047512a6a.png) 

## Installation
Run the following commands to install the theme.  Xcode is required:
```
git clone https://github.com/maxpetretta/monokai-pro-xcode.git
cd monokai-pro-xcode/ && sh ./install.sh
```
Restart Xcode and select the theme!

## Font Customization
To customize the theme font without losing text styling, the following steps are recommended:

1. Enable the theme, and change the font **ONLY** for the `Plain Text` entry
2. Quit Xcode, and navigate to `~/Library/Developer/Xcode/UserData/FontAndColorThemes/Monokai\ Pro.xccolortheme`
3. Using your editor of choice, find & replace all instances of `SFMono` with your preferred font, i.e. `FiraCode`
4. Optionally, you can change the default font size of `11.0` using the same method
5. Save the file, and reopen Xcode 🙌

## Credits
Special thanks to [Monokai](https://monokai.nl/) for creating the One True Color Theme <3
