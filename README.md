### nvim-config
This is my personal neovim configuration. This is heavily inspired by [theprimeagen](https://github.com/theprimeagen/init.lua)

It uses
* [packer](https://github.com/wbthomason/packer.nvim) as the package manager
* [telescope](https://github.com/nvim-telescope/telescope.nvim) as a fuzzy finder
* [material](https://github.com/marko-cerovac/material.nvim) darker as the theme
* neovim lsp

### Requirements
*  neovim (>0.9)
*  lua


### Getting Started
*  Clone the repo
    ```shell
    git clone git@github.com:pkarakal/nvim-config.git
    ```
*  Install packer
    ```shell
    git clone --depth 1 git@github.com:wbthomason/packer.nvim.git ~/.local/share/nvim/site/pack/packer/start/packer.nvim
    ```
*  Navigate to lua/pkarakal
    ```shell
    cd lua/pkarakal
    ```
*  Open neovim
    ```shell
    nvim packer.lua
    ```
*  In normal mode, type `:so` to source the file
*  In normal mode again, type `:PackerSync` to install all the dependencies
*  Exit nvim `:q`
*  Navigate back to project root
    ```shell
    cd ../../
    ```
*  Run the dev script
    ```shell
    ./dev
    ```
*  Now when you open neovim, the new configuration should be applied.
