# Atom Keyboard Shortcuts

This page lists keyboard shortcuts for the [Atom text editor](https://atom.io) that I find valuable and use a lot. Feel free to fork the page and add your own favorites. Pull Requests welcome!

This list is by no means meant to be a complete listing of every available shortcut. It simply lists the shortcuts that I use on a regular basis. For a complete listing of all available shortcuts, consult the _Settings > Keybindings_ page in Atom.

Since I'm using a Mac, I have mainly listed the keyboard shortcuts macOS. Please feel free to add the Windows or Linux shortcuts.

Where the shortcut is provided by a package, I have added a link to the package.

## General

Some general keyboard shortcuts that I use frequently.

| Command | macOS | Windows | Linux | Description |
| ------- | -------- | ------- | ----- | ----------- |
| Preferences/Settings | `cmd-,` | `ctrl-,`  | `ctrl-,` | Opens the Preferences/Settings view |
| Command Palette | `shift-cmd-p` | `shift-ctrl-p`  | `ctrl-shift-p` | Opens & closes the command palette |
| Open File (Fuzzy) | `cmd-p` <br/>or<br/> `cmd-t` | `ctrl-p` <br/>or<br/> `ctrl-t`  | `ctrl-p` <br/>or<br/> `ctrl-t` | Opens the Fuzzy Finder palette in which you can search and open files  |
| Browse Open Files | `cmd-b` | `ctrl-b`  | `ctrl-b` | Browse tabs within the window  |
| Previous Tab | `alt-cmd-left` | `ctrl-pageup` | `ctrl-pageup`| Cycles left through open tabs (in the active pane) |
| Next Tab | `alt-cmd-right` | `ctrl-pagedown` | `ctrl-pagedown` | Cycles right through open tabs (in the active page) |
| Grammar Selector | `ctrl-shift-l` | `ctrl-shift-l`  | `ctrl-shift-l` | Selects the language the file is in  |
| Markdown Preview | `ctrl-shift-m` | `ctrl-shift-m`  | `ctrl-shift-m` | Previews the file in the Markdown format |
| Key Binding Resolver | `cmd-.` | `ctrl-.`  | `ctrl-.` | Shows what keybindings the pressed key combination resolves to |
| Toggle Tree View | `cmd-k cmd-b`<br/>or<br/>`cmd-\` | `ctrl-k ctrl-b`<br/>or<br/>`ctrl-\` | `ctrl-k ctrl-b`<br/>or<br/>`ctrl-\`| Toggles Atom's file Tree View |
| Reload Atom | `ctrl-alt-cmd-l` | `alt-ctrl-r` | `alt-ctrl-r` | Reloads the Editor  |
| Open Link | `ctrl-shift-o` |  |  | Opens up a HTTP or HTTPS link |
| Toggle Developer Tools | `alt-cmd-i` | `ctrl-alt-i`  | `ctrl-shift-i` | Opens up the Chrome Developer Tools/Console |
| Show Available Snippets | `alt-shift-s` | `alt-shift-s`  | `alt-shift-s` | Shows the snippets available to Atom  |


## Window Management

| Command | macOS | Windows | Linux | Description |
| ------- | -------- | ------- | ----- | ----------- |
| New File | `cmd-n` | `ctrl-n`  | `ctrl-n` | Opens an empty file in a new tab |
| New Window | `shift-cmd-n` | `ctrl-shift-n`  | `ctrl-shift-n` | Opens a new editor window |
| Open | `cmd-o` | `ctrl-o`  | `ctrl-o` | Shows the _Open File_ dialog, which lets you select a file to open in the editor |
| Open Folder | `cmd-shift-o` | `ctrl-shift-o`  | `ctrl-shift-o` | Shows the _Open Folder_ dialog, which lets you select a folder to add to the editor's Tree View |
| Save | `cmd-s` | `ctrl-s`  | `ctrl-s` | Saves the currently active file |
| Save As | `shift-cmd-s` | `ctrl-shift-s`  | `ctrl-shift-s` | Saves the currently active file under a different name  |
| Save All | `alt-cmd-s` |  |  | Saves all changed files |
| Close Tab | `cmd-w` |  `ctrl-w` | `ctrl-w` | Closes the currently active tab|
| Close Window | `shift-cmd-w` | `ctrl-shift-w`  | `ctrl-shift-w` | Closes the currently active editor window  |
| Split Window | `cmd-k up/down/left/right` | `ctrl-k up/down/left/right` | `ctrl-k up/down/left/right` | Split the currently active tab in one of the four directions |
| Focus Pane | `cmd-k cmd-up/down/left/right` | `ctrl-k ctrl-up/down/left/right` | `ctrl-k ctrl-up/down/left/right` | Move the focus to the pane in one of the four directions |
| Toggle full screen | `ctrl-cmd-f` | `F11` | `F11` | Toggle full screen window |

## Editing

| Command | macOS | Windows | Linux | Description |
| ------- | -------- | ------- | ----- | ----------- |
| Duplicate Lines | `shift-cmd-d` | `ctrl-shift-d` | `ctrl-shift-d` | Duplicates the line of the current cursor position and creates a new line under it with the same contents |
| Delete Line | `ctrl-shift-k` | `ctrl-shift-k` | `ctrl-shift-k` | Deletes the current line |
| Move Line Up | `ctrl-cmd-up` | `ctrl-up`  | `ctrl-up` | Moves the contents of the current cursor position up one line. If there is a line above with content, the current lines content will swap with the one above it. |
| Move Line Down | `ctrl-cmd-down` | `ctrl-down`  | `ctrl-down` | Moves the contents of the current cursor position down one line. If there is a line below with content, the line's content will swap with the one below it. |
| Find/Replace | `cmd-f` | `ctrl-f`  | `ctrl-f` | Opens up the Find/Replace panel |
| Find Next | `cmd-g` | `F3`  | `F3` | Toggles forward through the results of the current buffer in the file while the Find/Replace panel is active |
| Find Previous | `shift-cmd-g` | `shift-F3`  | `shift-F3` | Toggles backward through the results of the current buffer in the file while the Find/Replace panel is active|
| Find in Project | `shift-cmd-f` | `ctrl-shift-f`  | `ctrl-shift-f` | Opens the Find in Project Panel |
| Go To Line | `ctrl-g` | `ctrl-g`  | `ctrl-g` | Opens the Go To Line panel |
| Go To Matching Bracket | `ctrl-m` | `ctrl-m`  | `ctrl-m` | The cursor goes to the matching top bracket that the cursor is ecapsulated in  |
| Select Line | `cmd-l` | `ctrl-l`  | `ctrl-l` | Selects the entire line the cursor's current position is in |
| Toggle Comment | `cmd-/` | `ctrl-/`  | `ctrl-/` | Toggles the selected text into a comment of the current grammar |
| Column Selection | `ctrl-shift-up/down` | `ctrl-alt-up/down` | `shift-alt-up/down`  | Allows to select multiple rows, where the same edit will be applied |
| Select Same Words | `cmd-d` | `ctrl-d` | `ctrl-d` | If you select a word, and then hit the key combo for this command, Atom will select the next same word for you. Then you can either type directly (which will replace the old words) or use left or right arrow to append things. |
| Undo Selection | `cmd-u` | `ctrl-u` | `ctrl-u` | This undoes the previous selection, like from Select Same Words. |
| Select All The Same Words At Once | `cmd-ctrl-g` | `alt-f3`  | `alt-f3` | This shortcut is similar to `cmd-d/ctrl-d` but it selects all the matching words at once.  |
| Show Symbols Palette | `cmd-r` | `ctrl-r` | `ctrl-r` | This shortcuts opens a palette that lists all the symbols (or functions) in your current file allowing you to fuzzy search and jump lines. |
| Show auto-completions | `ctrl-space` | `ctrl-space` | `ctrl-space` | Show available auto-completions |
| Fold/Unfold sections of code | `option-cmd-[` <b>and</b> `option-cmd-]` | `ctrl-shift-[` <b>and</b> `ctrl-shift-]` | `ctrl-shift-[` <b>and</b> `ctrl-shift-]` | Fold and Unfold sections of code
| Fold/Unfold at a specific indentation level | `cmd-k` <b>then</b> `cmd-(0-9)` | `ctrl-k` <b>then</b> `ctrl-(0-9)` | `ctrl-k` <b>then</b> `ctrl-(0-9)` | Fold/Unfold at a specific indentation level where the number is the indentation depth

## Various Packages

These are some packages I find useful, and their most useful key bindings. A list of my favorite packages can be found [here](https://atom.io/users/nwinkler/stars).

| Command | macOS | Windows | Linux | Package |
| ------- | -------- | ------- | ----- | ----------- |
| Block Travel up/down | `alt-up`, `alt-down` |  |  | [Block Travel](https://atom.io/packages/block-travel) |
| Beautify | `ctrl-alt-b` |  |  | [Beautify](https://atom.io/packages/atom-beautify) |
| Build Project | `cmd-alt-b` | `ctrl-alt-b` | `ctrl-alt-b` | [Build](https://atom.io/packages/build) |
| Expand Abbreviation | `shift-cmd-e` | `ctrl-e` | `ctrl-e` | [Emmet](https://atom.io/packages/emmet) |
| Git Plus Menu | `shift-cmd-h` | `ctrl-shift-h` | `ctrl-shift-h` | [Git Plus](https://atom.io/packages/git-plus) |
| Jumpy | `shift-enter` |  |  | [Jumpy](https://atom.io/packages/jumpy) |
| Minimap Toggle | `ctrl-k ctrl-m` |  |  | [Minimap](https://atom.io/packages/minimap) |
| Open File in Browser | `ctrl-alt-m` |  |  | [Open in Browser](https://atom.io/packages/open-in-browser) |
| Open Project | `ctrl-cmd-p` | `alt-shift-p` | `ctrl-alt-shift-p` | [Project Manager](https://atom.io/packages/project-manager) |
| Sublime Style Column Selection | `alt-mouse` |  |  | [Sublime Style Column Selection](https://atom.io/packages/Sublime-Style-Column-Selection) |

## apm

`apm` is Atom's package manager, based on Node's `npm` tool.

| Command | Description |
| ------- | ----------- |
| `apm upgrade` | Updates all locally installed packages |
| `apm upgrade --no-confirm` | Updates all locally installed packages without asking any questions |
| `apm stars --install` | Installs/updates all packages that you have marked as a favorite (_starred_) in your Atom.io profile |
| `apm publish minor` | If you're developing your own package, run this in the package's directory to publish a new version of the package, increasing the minor version number by one. |
