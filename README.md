# zsh-git-lfs

This plugin adds short aliases for the [`git-lfs (AVH Edition)`](https://github.com/git-lfs/git-lfs) commands.

## Usage

Without typing full `git-lfs` commands in console, like:

   ```zsh
   git lfs track "*.psd"
   ```

there is more convenient alias:

   ```zsh
   glft "*.psd" 
   ```

## Installation

#### zplug

1. Add the following to your `.zshrc`:

   ```zsh
   zplug "nekofar/zsh-git-lfs"
   ```

2. Start a new terminal session.

#### Antigen

1. Add the following to your `.zshrc`:

   ```zsh
   antigen bundle nekofar/zsh-git-lfs
   ```

2. Start a new terminal session.

#### Oh My Zsh

1. Clone this repository into `$ZSH_CUSTOM/plugins` (by default `~/.oh-my-zsh/custom/plugins`)

   ```zsh
   git clone https://github.com/nekofar/zsh-git-lfs \
     ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-git-lfs
   ```

2. Add the plugin to the list of plugins for Oh My Zsh to load (inside `~/.zshrc`):

   ```zsh
   plugins=( [plugins...] zsh-git-lfs)
   ```

3. Start a new terminal session.

## Requirements

1. The git-flow tool has to be [installed](https://github.com/petervanderdoes/gitflow-avh#installing-git-flow)
   separately.
