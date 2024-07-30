# dotfiles

This repository contains my dotfiles. I use [GNU Stow](https://www.gnu.org/software/stow/) to manage them.

## Installation

```bash
git clone
cd dotfiles
stow -t ~ *
```

## Uninstallation

```bash
cd dotfiles
stow -t ~ -D *
```

## License

[MIT](LICENSE)

## Files

### Brewfile

This file contains a list of all the packages I have installed using [Homebrew](https://brew.sh/). To install them, run:

```bash
brew bundle
```

To update the file with the latest packages, run:

```bash
brew bundle dump -f
```
