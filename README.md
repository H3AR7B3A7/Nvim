# H3AR7B3A7's init.lua

[The full video of ThePrimeagen setting up this repo](https://www.youtube.com/watch?v=w7i4amO_zaE)

## Prerequisites

### RipGrep

```
choco install ripgrep
```

### Home Env Var

Ensure you have a HOME environment variable set to your user directory.

> C:\Users\Admin

### Install C compiler

https://www.freecodecamp.org/news/how-to-install-c-and-cpp-compiler-on-windows/


## Install Nvim

```
choco install neovim --version=0.9.0
```

## Nvim install dir

```
C:\tools\neovim\nvim-win64\bin
```

_Copy the nvim.exe, and call it vim.exe._

## Nvim settings files location

```
C:\Users\Admin\AppData\Local\nvim
```

## Packer

[Packer Repo](https://github.com/wbthomason/packer.Nvim)

```
git clone https://github.com/wbthomason/packer.nvim "$env:LOCALAPPDATA\nvim-data\site\pack\packer\start\packer.nvim"
```

### Run Packer

```
:PackerSync
```

---
&copy; H3AR7B3A7, December 2023

