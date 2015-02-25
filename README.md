# Atom Keyboard Shortcuts

This page lists keyboard shortcuts for the [Atom text editor](https://atom.io) that I find valuable and use a lot. Feel free to fork the page and add your own favorites. Pull Requests welcome!

This list is by no means meant to be a complete listing of every available shortcut. It simply lists the shortcuts that I use on a regular basis. For a complete listing of all available shortcuts, consult the _Settings > Keybindings_ page in Atom.

Since I'm using a Mac, I have mainly listed the keyboard shortcuts for Mac OS X. Please feel free to add the Windows or Linux shortcuts.

Where the shortcut is provided by a package, I have added a link to the package.

## General

Some general keyboard shortcuts that I use frequently.

| Command | Mac OS X | Windows | Linux | Description |
| ------- | -------- | ------- | ----- | ----------- |
| Preferences/Settings | `cmd-,` |   | `ctrl-,` |  |
| Command Palette | `shift-cmd-p` |  | `ctrl-shift-p` |  |
| Open File (Fuzzy) | `cmd-p` |  | `ctrl-p` |  |
| Browse Open Files | `cmd-b` |  | `ctrl-b` |  |
| Grammar Selector | `ctrl-shift-l` |  | `ctrl-shift-l` |  |
| Markdown Preview | `ctrl-shift-m` |  | `ctrl-shift-m` |  |
| Key Binding Resolver | `cmd-.` |  | `ctrl-.` |  |
| Toggle Tree View | `cmd-k cmd-b` |  | `ctrl-k ctrl-b` |  |
| Reload Atom | `ctrl-alt-cmd-l` |  |  |  |
| Open Link | `ctrl-shift-o` |  |  |  |
| Toggle Developer Tools | `alt-cmd-i` |  |  |  |
| Show Available Snippets | `alt-shift-s` |  |  |  |

## Window Management

| Command | Mac OS X | Windows | Linux | Description |
| ------- | -------- | ------- | ----- | ----------- |
| New File | `cmd-n` |  | `ctrl-n` |  |
| New Window | `shift-cmd-n` |  | `ctrl-shift-n` |  |
| Open | `cmd-o` |  | `ctrl-o` |  |
| Open Folder |  |  | `ctrl-shift-o` |  |
| Save | `cmd-s` |  | `ctrl-s` |  |
| Save As | `shift-cmd-s` |  | `ctrl-shift-s` |  |
| Save All | `alt-cmd-s` |  |  |  |
| Close Tab | `cmd-w` |  | `ctrl-w` |  |
| Close Window | `shift-cmd-w` |  | `ctrl-shift-w` |  |

## Editing

| Command | Mac OS X | Windows | Linux | Description |
| ------- | -------- | ------- | ----- | ----------- |
| Duplicate Lines | `shift-cmd-d` |  | `shift-cmd-d` |  |
| Delete Line | `ctrl-shift-k` |  | `ctrl-shift-k` |  |
| Move Line Up | `ctrl-cmd-up` |  | `ctrl-up` |  |
| Move Line Down | `ctrl-cmd-down` |  | `ctrl-down` |  |
| Find/Replace | `cmd-f` |  | `ctrl-f` |  |
| Find Next | `cmd-g` |  | `F3` |  |
| Find Previous |  |  | `shift-F3` |  |
| Find in Project | `shift-cmd-f` |  | `ctrl-shift-f` |  |
| Go To Line | `ctrl-g` |  | `ctrl-g` |  |
| Go To Matching Bracket | `ctrl-m` |  | `ctrl-m` |  |
| Select Line | `cmd-l` |  | `cmd-l` |  |
| Toggle Comment | `cmd-/` |  | `cmd-/` |  |

## Various Packages

These are some packages I find useful, and their most useful key bindings. A list of my favorite packages can be found [here](https://atom.io/users/nwinkler/stars).

| Command | Mac OS X | Windows | Linux | Package |
| ------- | -------- | ------- | ----- | ----------- |
| Block Travel up/down | `alt-up`, `alt-down` |  |  | [Block Travel](https://atom.io/packages/block-travel) |
| Bookmarklet | `ctrl-alt-b` |  |  | [Bookmarklet](https://atom.io/packages/bookmarklet) |
| Incremental Search | `cmd-i` |  |  | [Incremental Search](https://atom.io/packages/incremental-search) |
| Git Plus Menu | `shift-cmd-h` | `ctrl-shift-h` | `ctrl-shift-h` | [Git Plus](https://atom.io/packages/git-plus) |
| Jumpy | `shift-enter` |  |  | [Jumpy](https://atom.io/packages/jumpy) |
| Minimap Toggle | `ctrl-k ctrl-m` |  |  | [Minimap](https://atom.io/packages/minimap) |
| Open File in Browser | `ctrl-alt-m` |  |  | [Open in Browser](https://atom.io/packages/open-in-browser) |
| Run Script | `ctrl-cmd-i` |  |  | [Script](https://atom.io/packages/script) - Keybinding remapped from original `cmd-i` to avoid conflict with Incremental Search |
| Open Terminal | `ctrl-alt-t` |  |  | [Term2](https://atom.io/packages/term2) |
| Open Project | `ctrl-cmd-p` | `ctrl-alt-shift-p` | `ctrl-alt-shift-p` | [Project Manager](https://atom.io/packages/project-manager) |
| Open In | `ctrl-alt-o` |  |  | [Open In](https://atom.io/packages/open-in) |

## apm

`apm` is Atom's package manager, based on Node's `npm` tool.

| Command | Description |
| ------- | ----------- |
| `apm upgrade` | Updates all locally installed packages |
| `apm stars --install` | Installs/updates all packages that you have marked as a favorite (_starred_) in your Atom.io profile |
| `apm publish minor` | If you're developing your own package, run this in the package's directory to publish a new version of the package, increasing the minor version number by one. |
