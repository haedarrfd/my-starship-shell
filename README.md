# Oh My Starship

> [!WARNING]
> This repository will not receive any further updates, as my **dotfiles** is already set up for general use. For future improvements, please feel free to see my **dotfiles** repo [here](https://github.com/haedarrfd/dotfiles.git).

## Introduction

oh-my-starship is my customized terminal prompt for the [Z shell](https://en.wikipedia.org/wiki/Z_shell) (zsh). While [Starship](https://starship.rs/) is compatible with various shells beyond zsh. I chose Starship over [Powerlevel10k](https://github.com/romkatv/powerlevel10k) due to its ease of customization. Starship allows you to create a prompt that is either minimalistic or feature-rich as you would like it to be.

## 📸 Screenshot

## ⚡️ Requirements

- A compatible shell: **bash**, **zsh**, **fish**, **powershell**, or any other shell.
- A terminal emulator installed. I use **Alacritty** btw.
- A Nerd Font installed and enabled in your terminal.

## 📦 Installation

**_NOTE_**: If you are using other than _zsh_, please refer to the official documentation for installation instructions. See [documentation](https://starship.rs/#prerequisites)

Follow these command to install this Starship:

1. Install Starship.

```shell
curl -sS https://starship.rs/install.sh | sh
```

2. Restart your shell.

```shell
source ~/.zshrc  # Replace with the appropriate file for your shell
```

## 📁 Configuration

Starship is configured through a `starship.toml` file. By default, Starship searches for the file in `~/.config/starship.toml`, but my config file location stores in `~/.config/starship/starship.toml`. For detailed information, please refer to the official documentation.

Follow this command to use this Starship:

```shell
# Adjust according to your preferred storage location.
git clone https://github.com/haedarrfd/oh-my-starship ~/.config/starship
```

After that, reopen your terminal and see what happens.
