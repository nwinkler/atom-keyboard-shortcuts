# Atom Keyboard Shortcuts

This page lists keyboard shortcuts for the [Atom text editor](https://atom.io) that I find valuable and use a lot. Feel free to fork the page and add your own favorites. Pull Requests welcome!

Since I'm using a Mac, I have mainly listed the keyboard shortcuts for Mac OS X. Please feel free to add the Windows or Linux shortcuts.

Where the shortcut is provided by a package, I have added a link to the package.

## General

Some general keyboard shortcuts that I use frequently.

| Command | Mac OS X | Windows | Linux | Description |
| ------- | -------- | ------- | ----- | ----------- |
| Preferences/Settings | `cmd-,` |  |  |  |
| Command Palette | `cmd-shift-p` |  |  |  |
| Open File (Fuzzy) | `cmd-p` |  |  |  |
| Browse Open Files | `cmd-b` |  |  |  |
| Grammar Selector | `ctrl-shift-l` |  |  |  |
| Markdown Preview | `ctrl-shift-m` |  |  |  |
| Key Binding Resolver | `cmd-.` |  |  |  |
| Toggle Tree View | `cmd-k cmd-b` |  |  |  |
| Reload Atom | `cmd-ctrl-alt-l` |  |  |  |
| Open Link | `ctrl-shift-o` |  |  |  |
| Toggle Developer Tools | `cmd-alt-i` |  |  |  |
| Show Available Snippets | `alt-shift-s` |  |  |  |

## Window Management

| Command | Mac OS X | Windows | Linux | Description |
| ------- | -------- | ------- | ----- | ----------- |
| New File | `cmd-n` |  |  |  |
| New Window | `cmd-shift-n` |  |  |  |
| Open | `cmd-o` |  |  |  |
| Save | `cmd-s` |  |  |  |
| Save As | `cmd-shift-s` |  |  |  |
| Save All | `cmd-alt-s` |  |  |  |
| Close Tab | `cmd-w` |  |  |  |
| Close Window | `cmd-shift-w` |  |  |  |

## Editing

| Command | Mac OS X | Windows | Linux | Description |
| ------- | -------- | ------- | ----- | ----------- |
| Duplicate Lines | `cmd-shift-d` |  |  |  |
| Delete Line | `ctrl-shift-k` |  |  |  |
| Move Line Up | `cmd-ctrl-up` |  |  |  |
| Move Line Down | `cmd-ctrl-down` |  |  |  |
| Find/Replace | `cmd-f` |  |  |  |
| Find Next | `cmd-g` |  |  |  |
| Find in Project | `cmd-shift-f` |  |  |  |
| Go To Line | `ctrl-g` |  |  |  |
| Select Line | `cmd-l` |  |  |  |

## Various Packages

These are some packages I find useful, and their most useful key bindings.

| Command | Mac OS X | Windows | Linux | Package |
| ------- | -------- | ------- | ----- | ----------- |
| Block Travel up/down | `alt-up`, `alt-down` |  |  | [Block Travel](https://atom.io/packages/block-travel) |
| Bookmarklet | `ctrl-alt-b` |  |  | [Bookmarklet](https://atom.io/packages/bookmarklet) |
| Git Plus Menu | `cmd-shift-h` | `ctrl-shift-h` | `ctrl-shift-h` | [Git Plus](https://atom.io/packages/git-plus) |
| Jumpy | `shift-enter` |  |  | [Jumpy](https://atom.io/packages/jumpy) |
| Minimap Toggle | `ctrl-k ctrl-m` |  |  | [Minimap](https://atom.io/packages/minimap) |
| Open File in Browser | `ctrl-alt-m` |  |  | [Open in Browser](https://atom.io/packages/open-in-browser) |
| Run Script | `cmd-i` |  |  | [Script](https://atom.io/packages/script) |
| Open Terminal | `ctrl-alt-t` |  |  | [Term2](https://atom.io/packages/term2) |

## apm

`apm` is Atom's package manager, based on Node's `npm` tool.

| Command | Description |
| ------- | ----------- |
| `apm upgrade` | Updates all locally installed packages |
| `apm stars --install` | Installs/updates all packages that you have marked as a favorite (_starred_) in your Atom.io profile |
| `apm publish minor` | If you're developing your own package, run this in the package's directory to publish a new version of the package, increasing the minor version number by one. |
