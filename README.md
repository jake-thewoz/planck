# Planck
These are my keyboard layouts for the OLBK Planck Keyboard (v6)

## About these Layouts
These layouts are designed with programming in mind, specifically in [Vim](https://www.vim.org/). The goal is to make all the numbers, brackets, math operators, and other programming keys easy to reach and use with simple keystrokes. Personally, I'm always trying to find more comfortable and more efficient ways to use my keyboard while operating computers, whether that's programming in Vim or navigating webpages.

Feel free to use any of these layouts as a starting point to make your own custom layouts! Building your own keyboard layout is a fun and rewarding hobby, so if you're inclined to do it better, go for it!

### Numbers
The numbers in these layouts are arranged like a numpad, or tenkey. As someone who has done some networking, I simply cannot live with typing IP addresses using a number row. The shifted number symbols are in the same place as the numpad, which is a little strange to get used to.

### Brackets | Parenthesis
The brackets and parenthesis are located in an easy-to-use layer, which favors the strong fingers of both left and right hands. This was done because I can't stand trying to enter parenthesis, brackets, and braces on normal keyboards, especially when they're used so often in programming. This makes it much easier to hit the right key with confidence (with a little practice).

## How to View
To view these layouts, follow these steps:
1. Go to the [Online QMK Configurator](https://config.qmk.fm)
2. Select the *Import QMK Keymap JSON File* option
3. Upload one of the JSON files from one of the version folders in this repo

## How to Flash your Planck
It is recommended that you first watch [MechMerlin's videos](https://www.youtube.com/watch?v=fuBJbdCFF0Q) on flashing QMK firmware to keyboards
1. Decide on which version of the layout you prefer (the latest is always recommended)
2. Open the [QMK Toolbox](https://github.com/qmk/qmk_toolbox)
3. In the QMK Toolbox, select the appropriate **bin** file you want to flash to your Planck
   - This is *not* the JSON file. In every version folder, there is the JSON file and the compiled QMK firmware, which is a **.bin** file
4. While your Planck is plugged in to your computer, activate the *reset* command
   - This can be done either by a keypress or by inserting a metal pin into the reset pinhole on the bottom of the Planck
5. Once the keyboard is reset, click the *flash* button in the QMK Toolbox
