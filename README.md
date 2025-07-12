# kbd-formatting-for-SE

[![License](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge&labelColor=555555)](LICENSE)
[![Ko-fi](https://img.shields.io/badge/Support-Ko--fi-FF5E5B?style=for-the-badge&logo=ko-fi&logoColor=white)](https://ko-fi.com/lauloque)

Adds a keyboard shortcut for formatting keyboard shortcuts on Stack Exchange sites.

This Tampermonkey userscript allows you to select text and, <kbd>&#9096; Ctrl</kbd><kbd>Y</kbd>, automatically format common keyboard keys and mouse buttons using HTML `<kbd>` tags. This provides a visually distinct and semantic way to represent user input instructions in your writing.

## Features

- **Effortless Formatting:** Select text containing keyboard key names and press a keyboard shortcut of your choosing  to format them. For example`ctrl shift a` will become <kbd>⎈ Ctrl</kbd> <kbd>⇧ Shift</kbd> <kbd>A</kbd>.
- **Special Keys Recognition:**
  - Common modifier keys: <kbd>&#9096; Ctrl</kbd> <kbd>&#8679; Shift</kbd> <kbd>&#9095; Alt</kbd> <kbd>&#8984; Cmd</kbd> <kbd>Win</kbd> etc.
  - Function keys: <kbd>F1</kbd>-<kbd>F12</kbd>
  - Command keys <kbd>⇥ Tab</kbd>, <kbd>⌦ Delete</kbd> <kbd>⏎ Enter</kbd>
  - Arrow keys "up" and "left" become <kbd>↑ Up</kbd> <kbd>← Left</kbd>
  - Numpad keys such as dot or numbers will be formatted as <kbd>Numpad&nbsp;•</kbd> or <kbd>Numpad&nbsp;5</kbd>
- **Mouse Button Formatting:** "lmb" as <kbd>Left 🖱️</kbd>, "rmb" as <kbd>Right 🖱️</kbd>, "mmb" as <kbd>Middle 🖱️</kbd>, and "wheel" or "scrollwheel" as <kbd>Wheel 🖱️</kbd>.
- **Case-Insensitive Matching:** Key names are recognized regardless of their capitalization (e.g., "Ctrl", "ctrl", and "CTRL" all become <kbd>⎈ Ctrl</kbd>).
- **Single Letter Capitalization:** Capitalizes single-letter words (useful for individual key presses), like "a" becoming <kbd>A</kbd>.

## How to Use

1. **Install the script:**
   
   - You need a userscript extension installed on your web browser:
     - Firefox:   [Greasemonkey – Get this Extension for 🦊 Firefox (en-US)](https://addons.mozilla.org/en-US/firefox/addon/greasemonkey/)
     - Chrome: [Tampermonkey - Chrome Web Store](https://chromewebstore.google.com/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo)
   - Open the raw [Kbd_Formatting_for_SE.user.js](https://github.com/Lauloque/kbd-formatting-for-SE/raw/refs/heads/main/Kbd_Formatting_for_SE.user.js), your userscript extension should detect it and propose you to install it.  
       If not, copy the whole code and refer to your extension's tools to add a script manually.

2. **Format text:**
   
   - Select the text you want to format (e.g., `ctrl shift a`).
   - Press the keyboard shortcut <kbd>&#9096; Ctrl</kbd><kbd>Y</kbd>
   - The selected text will be transformed into: `<kbd>⎈ Ctrl</kbd> <kbd>⇧ Shift</kbd> <kbd>A</kbd>` which looks like this:  
     <kbd>⎈ Ctrl</kbd> <kbd>⇧ Shift</kbd> <kbd>A</kbd>.

---

## License

Original concept and implementation by CoDEmanX and iKlsR
This enhanced version is made and maintained by Lauloque
See https://blender.meta.stackexchange.com/q/388/599 for discussion

Thank you for using Obsidian Keyboard Formatter! If you have any issues or suggestions, please feel free to open an issue on this repository.

---

## Support My Work

[![Support me on Ko-fi](https://img.shields.io/badge/Support-Ko--fi-FF5E5B?style=for-the-badge&logo=ko-fi&logoColor=white)](https://ko-fi.com/lauloque)

If you find this plugin helpful and would like to support its development, you can buy me a coffee on Ko-fi! Your support is greatly appreciated.
