<h1 align="center">
  <br>
  VS Code - Clipboard History Plus Extension
  <br>
  <br>
    <img src="https://raw.githubusercontent.com/aefernandes/vscode-clipboard-history-extension/master/images/logo.png" alt="logo" width="200">
  <br>
</h1>
<h4 align="center">Keep a history of your copied and cut items and re-paste if needed.</h4>

## Changes in 1.1

- Copying a previously saved item will move it to the top of the list.
- Pasting an item from the list will move it to the top of the list and put it in the system clipboard.

## Key Features

1. Save history of all copied and cut items
2. Paste from history
3. Clear all history
4. Remove selected item from history
5. Edit selected item in history

## Keyboard Shortcuts

**Type Clipboard in the command palette to view all commands.**

`Ctrl+C` copies and `Ctrl+X ` cuts the selected item. These override the default shortcuts to save the item to clipboard. If nothing is selected, the entire line will be saved.

`Ctrl+V` pastes the most recent item.

`Ctrl+Shift+V` opens the clipboard history. Use the arrow keys to scroll and press Enter to paste a selected item.

`Ctrl+Alt+V D` opens the clipboard delete settings. Use the arrow keys to scroll and press Enter to remove a selected item. The "Clear History" option will erase all items from history.

`Ctrl+Alt+V E` opens the clipboard editor settings. Use the arrow keys to scroll and press Enter to edit a selected item.

You can also add custom keyboard short cuts by following the instructions in the [customization documentation](https://code.visualstudio.com/docs/customization/keybindings).

## Configuration

`clipboard.size` is the maximum number of items saved in the clipboard. The default is 12, but this can be changed in [settings](https://code.visualstudio.com/docs/getstarted/settings#_default-settings).


## Demos
### Saving to and Pasting from Clipboard History

![demo](images/demo-1.gif)


### Erasing from Clipboard History

![demo](images/demo-2.gif)

### Editing Clipboard History

![demo](images/demo-3.gif)

## Installation

1. Run `npm install` in the project directory.
2. Run `npx vsce package` to create a VSIX package.
3. In VS Code, open Command Palette, select "Extensions: Install from VSIX..." and select the package.
