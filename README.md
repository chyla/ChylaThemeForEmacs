# chyla.org Theme for Emacs

This package provides a syntax highlighting theme for Emacs.

## Prerequisites

* [Emacs](https://www.gnu.org/software/emacs/) — An extensible, customizable, free/libre text editor — and more.

## Installation

The theme can either be installed manually by downloading the `chyla-theme.el` file or through [MELPA](https://melpa.org/):

### MELPA

1. Make sure you have enabled MELPA in Emacs. *(Click [here](https://www.emacswiki.org/emacs/MELPA) for instructions.)*
2. Hit `M-x` in Emacs (usually, this means holding down the alt-key and pressing the x-key).
3. Type `package-install` and hit enter.
4. Type `chyla-theme` and hit enter. The theme will now be downloaded and installed by Emacs.

## Usage

To enable the theme, Emacs must be instructed to load it:

1. Hit `M-x` again.
2. Type `load-theme` and hit enter. Emacs will now prompt you for the theme name.
4. Type `chyla` and hit enter. The theme should now be applied.

If you want to apply the theme automatically when Emacs starts, make sure to add the following in your `init.el` file:

`(load-theme 'chyla t)`

## Screenshot

![](screenshots/chyla-theme.png)

