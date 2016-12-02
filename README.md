# Sublrc
Sublrc, short for Sublime run command, is my personal Sublime Text settings.  
Sublime Text is a GUI-based text editor. See [official site](https://www.sublimetext.com) for more information.

## Location
The user settings files of Sublime Text 3 lie the following location.

* Mac: `/Users/YOUR_USERNAME/Library/Application Support/Sublime Text 3/Packages/User`

**NOTICE:** You probably need a backslash before each space when pasting on your terminal.  
e.g. `Application Support` => `Application\ Support`

I have no idea about Windows and Linux. Please tell me if you know!

## Description
### Preferences
File name: `Preferences.sublime-settings`. This is the main settings file. Written about genetic settings.

### Default Keymap
File name: `Default (OSX).sublime-keymap`. The customized sublime keymap for Mac. The keymaps of this file override default keymaps.

### Package Control
File name: `Package Control.sublime-settings`. The installed packages, themes and color schemes so far. All packages are shown regardless of my use. You can recognize if I still use these packages by refering to `"ignored_packages"` of `Preferences.sublime-settings` file. The current theme is `"theme"` and current color scheme is `"color_scheme"`.

### Distraction Free
File name: `Distraction Free.sublime-settings`. This is the settings for Distraction Free Mode. See [Distraction Free Mode](https://www.sublimetext.com/docs/3/distraction_free.html) for more information.

### Languages
File name: `LANGUAGE_NAME.sublime-settings` like `HTML.sublime-settings`. These files added automatically from `View -> Syntax -> Open all with current extension as...`. By seleting a language, the file whose filename extension is same as active tab's file always opens with selected language syntax.

### MacTerminal
File name: `MacTerminal.sublime-settings`. This is the settings for MacTerminal. But I maybe delete this package... x(

## Digression
I use text editors of both GUI and CUI. I use these editors depending on the following case.

* GUI editors: When developing and coding (mainly local files including virtual servers)
* CUI editors: When changing settings files (mainly remote files like production servers)

Trying various GUI editors, my most favorite one is Sublime Text at the moment. I will use this from now on.

**I :heart: Sublime Text**
