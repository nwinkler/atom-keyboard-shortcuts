# Atom Keyboard Shortcuts

This page lists keyboard shortcuts for the [Atom text editor](https://atom.io) that I find valuable and use a lot. Feel free to fork the page and add your own favorites. Pull Requests welcome!

This list is by no means meant to be a complete listing of every available shortcut. It simply lists the shortcuts that I use on a regular basis. For a complete listing of all available shortcuts, consult the _Settings > Keybindings_ page in Atom.

Since I'm using a Mac, I have mainly listed the keyboard shortcuts macOS. Please feel free to add the Windows or Linux shortcuts.

Where the shortcut is provided by a package, I have added a link to the package.

## General

Some general keyboard shortcuts that I use frequently.

| Command | macOS | Windows | Linux | Description |
| ------- | -------- | ------- | ----- | ----------- |
| Preferences/Settings | <kbd>cmd</kbd><kbd>,</kbd> | <kbd>ctrl</kbd><kbd>,</kbd>  | <kbd>ctrl</kbd><kbd>,</kbd> | Opens the Preferences/Settings view |
| Command Palette | <kbd>shift</kbd><kbd>cmd</kbd><kbd>p</kbd> | <kbd>shift</kbd><kbd>ctrl</kbd><kbd>p</kbd>  | <kbd>ctrl</kbd><kbd>shift</kbd><kbd>p</kbd> | Opens & closes the command palette |
| Open File (Fuzzy) | <kbd>cmd</kbd><kbd>p</kbd> <br/>or<br/> <kbd>cmd</kbd><kbd>t</kbd> | <kbd>ctrl</kbd><kbd>p</kbd> <br/>or<br/> <kbd>ctrl</kbd><kbd>t</kbd>  | <kbd>ctrl</kbd><kbd>p</kbd> <br/>or<br/> <kbd>ctrl</kbd><kbd>t</kbd> | Opens the Fuzzy Finder palette in which you can search and open files  |
| Browse Open Files | <kbd>cmd</kbd><kbd>b</kbd> | <kbd>ctrl</kbd><kbd>b</kbd>  | <kbd>ctrl</kbd><kbd>b</kbd> | Browse tabs within the window  |
| Previous Tab | <kbd>alt</kbd><kbd>cmd</kbd><kbd>left</kbd> | <kbd>ctrl</kbd><kbd>pageup</kbd> | <kbd>ctrl</kbd><kbd>pageup</kbd>| Cycles left through open tabs (in the active pane) |
| Next Tab | <kbd>alt</kbd><kbd>cmd</kbd><kbd>right</kbd> | <kbd>ctrl</kbd><kbd>pagedown</kbd> | <kbd>ctrl</kbd><kbd>pagedown</kbd> | Cycles right through open tabs (in the active page) |
| Grammar Selector | <kbd>ctrl</kbd><kbd>shift</kbd><kbd>l</kbd> | <kbd>ctrl</kbd><kbd>shift</kbd><kbd>l</kbd>  | <kbd>ctrl</kbd><kbd>shift</kbd><kbd>l</kbd> | Selects the language the file is in  |
| Markdown Preview | <kbd>ctrl</kbd><kbd>shift</kbd><kbd>m</kbd> | <kbd>ctrl</kbd><kbd>shift</kbd><kbd>m</kbd>  | <kbd>ctrl</kbd><kbd>shift</kbd><kbd>m</kbd> | Previews the file in the Markdown format |
| Key Binding Resolver | <kbd>cmd</kbd><kbd>.</kbd> | <kbd>ctrl</kbd><kbd>.</kbd>  | <kbd>ctrl</kbd><kbd>.</kbd> | Shows what keybindings the pressed key combination resolves to |
| Toggle Tree View | <kbd>cmd</kbd><kbd>k</kbd> <kbd>cmd</kbd><kbd>b</kbd><br/>or<br/><kbd>cmd</kbd><kbd>\\</kbd> | <kbd>ctrl</kbd><kbd>k</kbd> <kbd>ctrl</kbd><kbd>b</kbd><br/>or<br/><kbd>ctrl</kbd><kbd>\\</kbd> | <kbd>ctrl</kbd><kbd>k</kbd> <kbd>ctrl</kbd><kbd>b</kbd><br/>or<br/><kbd>ctrl</kbd><kbd>\\</kbd>| Toggles Atom's file Tree View |
| Reload Atom | <kbd>ctrl</kbd><kbd>alt</kbd><kbd>cmd</kbd><kbd>l</kbd> | <kbd>alt</kbd><kbd>ctrl</kbd><kbd>r</kbd> | <kbd>alt</kbd><kbd>ctrl</kbd><kbd>r</kbd> | Reloads the Editor  |
| Open Link | <kbd>ctrl</kbd><kbd>shift</kbd><kbd>o</kbd> |  |  | Opens up a HTTP or HTTPS link |
| Toggle Developer Tools | <kbd>alt</kbd><kbd>cmd</kbd><kbd>i</kbd> | <kbd>ctrl</kbd><kbd>alt</kbd><kbd>i</kbd>  | <kbd>ctrl</kbd><kbd>shift</kbd><kbd>i</kbd> | Opens up the Chrome Developer Tools/Console |
| Show Available Snippets | <kbd>alt</kbd><kbd>shift</kbd><kbd>s</kbd> | <kbd>alt</kbd><kbd>shift</kbd><kbd>s</kbd>  | <kbd>alt</kbd><kbd>shift</kbd><kbd>s</kbd> | Shows the snippets available to Atom  |


## Window Management

| Command | macOS | Windows | Linux | Description |
| ------- | -------- | ------- | ----- | ----------- |
| New File | <kbd>cmd</kbd><kbd>n</kbd> | <kbd>ctrl</kbd><kbd>n</kbd>  | <kbd>ctrl</kbd><kbd>n</kbd> | Opens an empty file in a new tab |
| New Window | <kbd>shift</kbd><kbd>cmd</kbd><kbd>n</kbd> | <kbd>ctrl</kbd><kbd>shift</kbd><kbd>n</kbd>  | <kbd>ctrl</kbd><kbd>shift</kbd><kbd>n</kbd> | Opens a new editor window |
| Open | <kbd>cmd</kbd><kbd>o</kbd> | <kbd>ctrl</kbd><kbd>o</kbd>  | <kbd>ctrl</kbd><kbd>o</kbd> | Shows the _Open File_ dialog, which lets you select a file to open in the editor |
| Open Folder | <kbd>cmd</kbd><kbd>shift</kbd><kbd>o</kbd> | <kbd>ctrl</kbd><kbd>shift</kbd><kbd>o</kbd>  | <kbd>ctrl</kbd><kbd>shift</kbd><kbd>o</kbd> | Shows the _Open Folder_ dialog, which lets you select a folder to add to the editor's Tree View |
| Save | <kbd>cmd</kbd><kbd>s</kbd> | <kbd>ctrl</kbd><kbd>s</kbd>  | <kbd>ctrl</kbd><kbd>s</kbd> | Saves the currently active file |
| Save As | <kbd>shift</kbd><kbd>cmd</kbd><kbd>s</kbd> | <kbd>ctrl</kbd><kbd>shift</kbd><kbd>s</kbd>  | <kbd>ctrl</kbd><kbd>shift</kbd><kbd>s</kbd> | Saves the currently active file under a different name  |
| Save All | <kbd>alt</kbd><kbd>cmd</kbd><kbd>s</kbd> |  |  | Saves all changed files |
| Close Tab | <kbd>cmd</kbd><kbd>w</kbd> |  <kbd>ctrl</kbd><kbd>w</kbd> | <kbd>ctrl</kbd><kbd>w</kbd> | Closes the currently active tab|
| Close Window | <kbd>shift</kbd><kbd>cmd</kbd><kbd>w</kbd> | <kbd>ctrl</kbd><kbd>shift</kbd><kbd>w</kbd>  | <kbd>ctrl</kbd><kbd>shift</kbd><kbd>w</kbd> | Closes the currently active editor window  |
| Split Window | <kbd>cmd</kbd><kbd>k </kbd><kbd>&uarr;</kbd>/<kbd>&darr;</kbd>/<kbd>&larr;</kbd>/<kbd>&rarr;</kbd> | <kbd>ctrl</kbd><kbd>k </kbd><kbd>&uarr;</kbd>/<kbd>&darr;</kbd>/<kbd>&larr;</kbd>/<kbd>&rarr;</kbd> | <kbd>ctrl</kbd><kbd>k </kbd><kbd>&uarr;</kbd>/<kbd>&darr;</kbd>/<kbd>&larr;</kbd>/<kbd>&rarr;</kbd> | Split the currently active tab in one of the four directions |
| Focus Pane | <kbd>cmd</kbd><kbd>k</kbd><kbd> cmd</kbd><kbd>&uarr;</kbd>/<kbd>&darr;</kbd>/<kbd>&larr;</kbd>/<kbd>&rarr;</kbd> | <kbd>ctrl</kbd><kbd>k</kbd><kbd> ctrl</kbd><kbd>&uarr;</kbd>/<kbd>&darr;</kbd>/<kbd>&larr;</kbd>/<kbd>&rarr;</kbd> | <kbd>ctrl</kbd><kbd>k</kbd><kbd> ctrl</kbd><kbd>&uarr;</kbd>/<kbd>&darr;</kbd>/<kbd>&larr;</kbd>/<kbd>&rarr;</kbd> | Move the focus to the pane in one of the four directions |
| Toggle full screen | <kbd>ctrl</kbd><kbd>cmd</kbd><kbd>f</kbd> | <kbd>F11</kbd> | <kbd>F11</kbd> | Toggle full screen window |

## Editing

| Command | macOS | Windows | Linux | Description |
| ------- | -------- | ------- | ----- | ----------- |
| Duplicate Lines | <kbd>shift</kbd><kbd>cmd</kbd><kbd>d</kbd> | <kbd>ctrl</kbd><kbd>shift</kbd><kbd>d</kbd> | <kbd>ctrl</kbd><kbd>shift</kbd><kbd>d</kbd> | Duplicates the line of the current cursor position and creates a new line under it with the same contents |
| Delete Line | <kbd>ctrl</kbd><kbd>shift</kbd><kbd>k</kbd> | <kbd>ctrl</kbd><kbd>shift</kbd><kbd>k</kbd> | <kbd>ctrl</kbd><kbd>shift</kbd><kbd>k</kbd> | Deletes the current line |
| Move Line Up | <kbd>ctrl</kbd><kbd>cmd</kbd><kbd>up</kbd> | <kbd>ctrl</kbd><kbd>up</kbd>  | <kbd>ctrl</kbd><kbd>up</kbd> | Moves the contents of the current cursor position up one line. If there is a line above with content, the current lines content will swap with the one above it. |
| Move Line Down | <kbd>ctrl</kbd><kbd>cmd</kbd><kbd>down</kbd> | <kbd>ctrl</kbd><kbd>down</kbd>  | <kbd>ctrl</kbd><kbd>down</kbd> | Moves the contents of the current cursor position down one line. If there is a line below with content, the line's content will swap with the one below it. |
| Find/Replace | <kbd>cmd</kbd><kbd>f</kbd> | <kbd>ctrl</kbd><kbd>f</kbd>  | <kbd>ctrl</kbd><kbd>f</kbd> | Opens up the Find/Replace panel |
| Find Next | <kbd>cmd</kbd><kbd>g</kbd> | <kbd>F3</kbd>  | <kbd>F3</kbd> | Toggles forward through the results of the current buffer in the file while the Find/Replace panel is active |
| Find Previous | <kbd>shift</kbd><kbd>cmd</kbd><kbd>g</kbd> | <kbd>shift</kbd><kbd>F3</kbd>  | <kbd>shift</kbd><kbd>F3</kbd> | Toggles backward through the results of the current buffer in the file while the Find/Replace panel is active|
| Find in Project | <kbd>shift</kbd><kbd>cmd</kbd><kbd>f</kbd> | <kbd>ctrl</kbd><kbd>shift</kbd><kbd>f</kbd>  | <kbd>ctrl</kbd><kbd>shift</kbd><kbd>f</kbd> | Opens the Find in Project Panel |
| Go To Line | <kbd>ctrl</kbd><kbd>g</kbd> | <kbd>ctrl</kbd><kbd>g</kbd>  | <kbd>ctrl</kbd><kbd>g</kbd> | Opens the Go To Line panel |
| Go To Matching Bracket | <kbd>ctrl</kbd><kbd>m</kbd> | <kbd>ctrl</kbd><kbd>m</kbd>  | <kbd>ctrl</kbd><kbd>m</kbd> | The cursor goes to the matching top bracket that the cursor is ecapsulated in  |
| Select Line | <kbd>cmd</kbd><kbd>l</kbd> | <kbd>ctrl</kbd><kbd>l</kbd>  | <kbd>ctrl</kbd><kbd>l</kbd> | Selects the entire line the cursor's current position is in |
| Toggle Comment | <kbd>cmd</kbd><kbd>/</kbd> | <kbd>ctrl</kbd><kbd>/</kbd>  | <kbd>ctrl</kbd><kbd>/</kbd> | Toggles the selected text into a comment of the current grammar |
| Column Selection | <kbd>ctrl</kbd><kbd>shift</kbd><kbd>&uarr;</kbd>/<kbd>&darr;</kbd> | <kbd>ctrl</kbd><kbd>alt</kbd><kbd>&uarr;</kbd>/<kbd>&darr;</kbd> | <kbd>shift</kbd><kbd>alt</kbd><kbd>&uarr;</kbd>/<kbd>&darr;</kbd>  | Allows to select multiple rows, where the same edit will be applied |
| Select Same Words | <kbd>cmd</kbd><kbd>d</kbd> | <kbd>ctrl</kbd><kbd>d</kbd> | <kbd>ctrl</kbd><kbd>d</kbd> | If you select a word, and then hit the key combo for this command, Atom will select the next same word for you. Then you can either type directly (which will replace the old words) or use left or right arrow to append things. |
| Undo Selection | <kbd>cmd</kbd><kbd>u</kbd> | <kbd>ctrl</kbd><kbd>u</kbd> | <kbd>ctrl</kbd><kbd>u</kbd> | This undoes the previous selection, like from Select Same Words. |
| Select All The Same Words At Once | <kbd>cmd</kbd><kbd>ctrl</kbd><kbd>g</kbd> | <kbd>alt</kbd><kbd>f3</kbd>  | <kbd>alt</kbd><kbd>f3</kbd> | This shortcut is similar to <kbd>cmd</kbd><kbd>d</kbd>/<kbd>ctrl</kbd><kbd>d</kbd> but it selects all the matching words at once.  |
| Show Symbols Palette | <kbd>cmd</kbd><kbd>r</kbd> | <kbd>ctrl</kbd><kbd>r</kbd> | <kbd>ctrl</kbd><kbd>r</kbd> | This shortcuts opens a palette that lists all the symbols (or functions) in your current file allowing you to fuzzy search and jump lines. |
| Show auto-completions | <kbd>ctrl</kbd><kbd>space</kbd> | <kbd>ctrl</kbd><kbd>space</kbd> | <kbd>ctrl</kbd><kbd>space</kbd> | Show available auto-completions |
| Fold/Unfold sections of code | <kbd>option</kbd><kbd>cmd</kbd><kbd>[</kbd> <b>and</b> <kbd>option</kbd><kbd>cmd</kbd><kbd>]</kbd> | <kbd>ctrl</kbd><kbd>alt</kbd><kbd>[</kbd> <b>and</b> <kbd>ctrl</kbd><kbd>alt</kbd><kbd>]</kbd> | <kbd>ctrl</kbd><kbd>alt</kbd><kbd>[</kbd> <b>and</b> <kbd>ctrl</kbd><kbd>alt</kbd><kbd>]</kbd> | Fold and Unfold sections of code
| Fold/Unfold at a specific indentation level | <kbd>cmd</kbd><kbd>k</kbd> <b>then</b> <kbd>cmd</kbd>(<kbd>0</kbd>-<kbd>9</kbd>)</kbd> | <kbd>ctrl</kbd><kbd>k</kbd> <b>then</b> <kbd>ctrl</kbd>(<kbd>0</kbd>-<kbd>9</kbd>)</kbd> | <kbd>ctrl</kbd><kbd>k</kbd> <b>then</b> <kbd>ctrl</kbd>(<kbd>0</kbd>-<kbd>9</kbd>)</kbd> | Fold/Unfold at a specific indentation level where the number is the indentation depth

## Various Packages

These are some packages I find useful, and their most useful key bindings. A list of my favorite packages can be found [here](https://atom.io/users/nwinkler/stars).

| Command | macOS | Windows | Linux | Package |
| ------- | -------- | ------- | ----- | ----------- |
| Block Travel up/down | <kbd>alt</kbd><kbd>&uarr;</kbd>, <kbd>alt</kbd><kbd>&darr;</kbd> |  |  | [Block Travel](https://atom.io/packages/block</kbd><kbd>travel) |
| Beautify | <kbd>ctrl</kbd><kbd>alt</kbd><kbd>b</kbd> |  |  | [Beautify](https://atom.io/packages/atom</kbd><kbd>beautify) |
| Build Project | <kbd>cmd</kbd><kbd>alt</kbd><kbd>b</kbd> | <kbd>ctrl</kbd><kbd>alt</kbd><kbd>b</kbd> | <kbd>ctrl</kbd><kbd>alt</kbd><kbd>b</kbd> | [Build](https://atom.io/packages/build) |
| Expand Abbreviation | <kbd>shift</kbd><kbd>cmd</kbd><kbd>e</kbd> | <kbd>ctrl</kbd><kbd>e</kbd> | <kbd>ctrl</kbd><kbd>e</kbd> | [Emmet](https://atom.io/packages/emmet) |
| Git Plus Menu | <kbd>shift</kbd><kbd>cmd</kbd><kbd>h</kbd> | <kbd>ctrl</kbd><kbd>shift</kbd><kbd>h</kbd> | <kbd>ctrl</kbd><kbd>shift</kbd><kbd>h</kbd> | [Git Plus](https://atom.io/packages/git</kbd><kbd>plus) |
| Jumpy | <kbd>shift</kbd><kbd>enter</kbd> |  |  | [Jumpy](https://atom.io/packages/jumpy) |
| Minimap Toggle | <kbd>ctrl</kbd><kbd>k</kbd> <kbd>ctrl</kbd><kbd>m</kbd> |  |  | [Minimap](https://atom.io/packages/minimap) |
| Open File in Browser | <kbd>ctrl</kbd><kbd>alt</kbd><kbd>m</kbd> |  |  | [Open in Browser](https://atom.io/packages/open</kbd><kbd>in</kbd><kbd>browser) |
| Open Project | <kbd>ctrl</kbd><kbd>cmd</kbd><kbd>p</kbd> | <kbd>alt</kbd><kbd>shift</kbd><kbd>p</kbd> | <kbd>ctrl</kbd><kbd>alt</kbd><kbd>shift</kbd><kbd>p</kbd> | [Project Manager](https://atom.io/packages/project</kbd><kbd>manager) |
| Sublime Style Column Selection | <kbd>alt</kbd><kbd>mouse</kbd> |  |  | [Sublime Style Column Selection](https://atom.io/packages/Sublime</kbd><kbd>Style</kbd><kbd>Column</kbd><kbd>Selection) |

## apm

`apm` is Atom's package manager, based on Node's `npm` tool.

| Command | Description |
| ------- | ----------- |
| `apm upgrade` | Updates all locally installed packages |
| `apm upgrade --no-confirm` | Updates all locally installed packages without asking any questions |
| `apm stars --install` | Installs/updates all packages that you have marked as a favorite (_starred_) in your Atom.io profile |
| `apm publish minor` | If you're developing your own package, run this in the package's directory to publish a new version of the package, increasing the minor version number by one. |
