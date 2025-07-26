# ⚙️ My Dotfiles

This repository contains my personal collection of configuration files for various tools, including Neovim, Zsh, and Tmux. It is managed as a central repository that tracks individual configurations as Git submodules.

## ✨ Philosophy

The primary goal is to have a single, version-controlled repository to quickly set up a new machine. Using **Git submodules** allows each configuration (like the Neovim setup) to live in its own dedicated repository, keeping concerns separate and making updates cleaner.

This repository acts as the "parent" that knows which version of each configuration to use.

## 🏗️ Structure

This repository is intended to be cloned into the home directory (`~`). It uses a `.gitignore` file to ignore everything by default, only tracking specific configuration files and directories that are explicitly un-ignored (`!`).

The core configurations are managed as Git submodules:

* **Neovim**: The `~/.config/nvim` directory is a submodule pointing to my [Neovim configuration repository](https://www.google.com/search?q=your_nvim_repo_url).
