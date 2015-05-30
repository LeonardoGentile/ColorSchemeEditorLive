ColorSchemeEditorLive
=================
"Real-time" color scheme editor plugin for Sublime Text 2/3.

## NOTE: I am not the author of this plugin
This package belonged to the user [bobef](https://github.com/bobef/ColorSchemeEditor-ST2) and was called __ColorSchemeEditor__ but his account has disappeared.
By chance I found this extremely useful plugin somewhere on my machine before it went lost forever.
All credits to the original author.

Screenshots
===========
### Automatic scope display
![Real-time scope display](./screenshots/screen1.png)

### Quick color selection (thirdparty plugin)
![Quick color selection (thirdparty plugin)](./screenshots/screen2.png)

### Real-time preview
![Real-time preview](./screenshots/screen3.png)

Usage
=====
- Activate the color scheme you want to edit.
- Open some file and press Shift+F12.
- Your color scheme should open in separate pane.
- As you put the cursor on different source elements, the other pane will find and display the XML element that is affecting this element.
- If more than one style element affect the code element, the most relevant style match is displayed first and you can go to other matches with Ctrl+Alt+Right and Ctrl+Alt+Left.
- Change the styles as you wish and save so Sublime Text will reload the styles and display your changes.
- When you are done editing press Shift+F12 again or close the view of the scheme file.

Authors
=======
Borislav Peev (borislav.asdf at gmail dot com)
